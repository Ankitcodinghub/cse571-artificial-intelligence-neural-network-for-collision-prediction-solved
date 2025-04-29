# cse571-artificial-intelligence-neural-network-for-collision-prediction-solved
**TO GET THIS SOLUTION VISIT:** [CSE571: Artificial Intelligence Neural Network for Collision Prediction Solved](https://www.ankitcodinghub.com/product/cse571-artificial-intelligence-neural-network-for-collision-prediction-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;98809&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE571: Artificial Intelligence  Neural Network for Collision Prediction Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
<h1>Purpose</h1>
The purpose of this assignment is to familiarize you with neural networks and their applications. More specifically, you will learn to collect training data for a robotics task and, in turn, design a neural network that can process this data. In the assignment your goal is to help a small robot navigate a simulated environment without any collisions. To accomplish this, you will need to train a neural network using backpropagation that predicts whether the robot is going to collide with any walls or objects in the next time step. All of the theories and best-practices introduced in the class are applicable here. Your task is to make sure the little fellow can safely explore its environment!

<h1>Objectives</h1>
Students will be able to:

<ul>
<li>Collect and manage a dataset used to train and test a neural network. ● Define and use PyTorch DataLoaders to manage a PyTorch Datasets.</li>
<li>Design your own neural network architecture in PyTorch.</li>
<li>Evaluate and improve a neural network model and verify an application in simulation.</li>
</ul>
<h1>Technology Requirements</h1>
<ul>
<li>System designed for use with Ubuntu 18.04</li>
<li>Python and its related libraries. Using Anaconda is recommended.</li>
<li>Python libraries: cython matplotlib sklearn scipy pymunk pygame pillow numpy noise torch</li>
</ul>
<h1>Project Description</h1>
<h2>Part 1</h2>
The first task is to collect data that can be used to train the model. Collect a single sample per action containing, in order, the 5 distance sensor readings, the action, and whether or not a collision occurred (0: no collision, 1: collision). This data should be saved as a .csv file with 7 untitled columns. For grading purposes, submit your ‘submission.csv’ containing 100 data samples. For training in the future parts, you will need to collect much more than this.

Files to edit: collect_data.py

The robot should wander around with no regard for its environment or avoiding collisions. Also, see below a sample of what your submission.csv should look like.

<h2>Part 2</h2>
Now that you have collected your training data, you can package it into an iterable PyTorch DataLoader for ease of use. You may be required to prune your collected data to balance out their distribution. If your dataset is 99% 0s and 1% 1s, a model that outputs only 0 would achieve good loss, but it would not have learned anything useful. Make sure to create both a training and testing DataLoader. Use training_data.csv collected from the previous part. Make sure to use the PyTorch classes mentioned in the comments of Data_Loaders.py.

Files to edit:

Data_Loaders.py saved/training_data.csv

<h2>Part 3</h2>
For Part 3, you will be designing your own custom neural network using PyTorch’s torch.nn class. You will need to initialize a custom architecture, define a forward pass through the network, and build a method for evaluating the fit of a given model.

Files to edit:

Data_Loaders.py Networks.py saved/*

<h2>Part 4</h2>
In Part 4, you must train a model using your custom network architecture, which accurately predicts collisions given sensor and action information. Your grade will depend on the accuracy of the model. You may need to try many different strategies and architectures to achieve a well fit model. Keep track of your training and testing loss throughout the epochs, and generate a plot with these lines at the end. To see an application demo of the learning your robot has done, run goal_seeking.py, which will have the robot seek out goals while only taking possible actions it deems to be safe.

Files to edit:

Data_Loaders.py Networks.py train_model.py saved/*

<h1>Submission Directions for Project Deliverables</h1>
<h2>Part 1</h2>
Files to submit: submission.csv

<h2>Part 2</h2>
Files to submit:

Data_Loaders.py

<h2>Part 3</h2>
Files to submit:

submission.zip – containing:

&gt; Data_Loaders.py

&gt; Networks.py

<h2>Part 4</h2>
Files to submit:

submission.zip – containing:

&gt; Networks.py

&gt; saved/

&gt;saved_model.pkl

&gt;scaler.pkl

<h1>Evaluation</h1>
<strong>Part 1</strong>

Pass/Fail 1 point

<strong>Part 2</strong>

Pass/Fail 1 point

<strong>Part 3</strong>

Pass/Fail 1 point

<h2>Part 4</h2>
0-7 points. 3% of the max score will be deducted for every missed collision. 1% of the max score will be deducted for every false positive above 10.
