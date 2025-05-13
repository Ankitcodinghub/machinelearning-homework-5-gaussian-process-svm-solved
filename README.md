# machinelearning-homework-5-gaussian-process-svm-solved
**TO GET THIS SOLUTION VISIT:** [MachineLearning Homework 5-Gaussian Process & SVM Solved](https://www.ankitcodinghub.com/product/machinelearning-homework-5-gaussian-process-svm-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92075&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MachineLearning Homework 5-Gaussian Process \u0026amp; SVM Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

I. Gaussian Process

In this section, you are going to implement the Gaussian Process and visualize the result.

● Training data

o input.dataisa34x2matrix.Everyrowcorrespondstoa2Ddatapoint

(Xi,Yi).

o Yi = f(Xi) + 𝜖i is a noisy observation, where 𝜖i ~ N(∙|0, β-1). You can use β =

5 in this implementation. ● What you are going to do

o Part1:ApplyGaussianProcessRegressiontopredictthedistributionoff and visualize the result. Please use a rational quadratic kernel to compute similarities between different points.

Details of the visualization:

– Show all training data points.

– Draw a line to represent the mean of f in range [-60,60]. – Mark the 95% confidence interval of f.

(You can use matplotlib.pyplot to visualize the result, e.g. use matplotlib.pyplot.fill_between to mark the 95% confidence interval, or you can use any other package you like.)

o Part2:Optimizethekernelparametersbyminimizingnegativemarginal log-likelihood, and visualize the result again. (You can use scipy.optimize.minimize to optimize the parameters.)

II. SVM on MNIST dataset

Use SVM models to tackle classification on images of hand-written digits (digit class only ranges from 0 to 4, as the figure shown below).

● Training data

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
III. Report

</div>
</div>
<div class="layoutArea">
<div class="column">
o X_train.csvisa5000x784matrix.Everyrowcorrespondstoa28x28gray- scale image.

o Y_train.csvisa5000x1matrix,whichrecordstheclassofthetraining samples.

● Testing data

o X_test.csvisa2500x784matrix.Everyrowcorrespondstoa28x28gray-

scale image.

o Y_test.csvisa2500x1matrix,whichrecordstheclassofthetestsamples.

● What you are going to do

o Part1:Usedifferentkernelfunctions(linear,polynomial,andRBFkernels)

</div>
</div>
<div class="layoutArea">
<div class="column">
and have comparison between their performance.

o Part2:PleaseuseC-SVC(youcanchoosebysettingparametersinthe

function input, C-SVC is soft-margin SVM). Since there are some parameters you need to tune for, please do the grid search for finding parameters of the best performing model. For instance, in C-SVC you have a parameter C, and if you use RBF kernel you have another parameter 𝛾, you can search for a set of (C, 𝛾) which gives you best performance in cross-validation. (There are lots of sources on the internet, just google for it.)

o Part3:Uselinearkernel+RBFkerneltogether(thereforeanewkernel function) and compare its performance with respect to others. You would need to find out how to use a user-defined kernel in libsvm.

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>● &nbsp;Submit a report in pdf format. The report should be written in English.</li>
<li>● &nbsp;Report format:
◼ I. Gaussian Process

<ul>
<li>a. code with detailed explanations (20%)
<ul>
<li>● &nbsp;For example, show the formula of rational quadratic kernel and the process you optimize the kernel parameters</li>
<li>● &nbsp;Note that if you don’t explain your code, you cannot get any points in section 2 and 3 either.
<ul>
<li>○ &nbsp;Part1 (10%)</li>
<li>○ &nbsp;Part2 (10%)</li>
</ul>
</li>
</ul>
</li>
<li>b. experiments settings and results (20%)
<ul>
<li>● &nbsp;Show the figures and the hyperparameters we asked you to show</li>
<li>● &nbsp;Note that if you don’t explain your code in the above section, you
cannot get any points in this section either.

<ul>
<li>○ &nbsp;Part1 (10%)</li>
<li>○ &nbsp;Part2 (10%)</li>
</ul>
</li>
</ul>
</li>
</ul>
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
IV. Turn in

</div>
</div>
<div class="layoutArea">
<div class="column">
■ c. observations and discussion (10%)

● Anything you want to discuss, such as comparing the performance

when using different hyperparameters.

◼ II. SVM

■ a. code with detailed explanations (20%)

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>● &nbsp;Paste the screenshot of your functions with comments and explain your code. For example, show the formula of different kernel functions and the process you search for the kernel parameters, etc.</li>
<li>● &nbsp;Note that if you don’t explain your code, you cannot get any points in section b and c either.
<ul>
<li>○ &nbsp;Part1 (5%)</li>
<li>○ &nbsp;Part2 (10%)</li>
<li>○ &nbsp;Part3 (5%)</li>
</ul>
</li>
</ul>
■ b. experiments settings and results (20%)

● Show everything we asked you to show

<ul>
<li>○ &nbsp;Part1 (5%)</li>
<li>○ &nbsp;Part2 (10%)</li>
<li>○ &nbsp;Part3 (5%)</li>
</ul>
■ c. observations and discussion (10%)

● Anything you want to discuss, such as trying different user-

defined kernel functions and comparing the performance.

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol>
<li>Report (.pdf)</li>
<li>Source code (e.g. gaussian_process.py, svm.py …)</li>
</ol>
You should zip source code and report in one file and name it like ML_HW5_yourstudentID_name.zip, e.g. ML_HW5_0856XXX_王小明.zip.

P.S. If the zip file name has format error or the report is not in pdf format, there will be a penalty (-10). Please submit your homework before the deadline, late submission is not allowed.

Packages allowed in this assignment:

You are only allowed to use numpy, scipy.optimize, scipy.spatial.distance, and package for visualizing results. Official introductions can be found online.

Important: scikit-learn is not allowed.

</div>
</div>
</div>
