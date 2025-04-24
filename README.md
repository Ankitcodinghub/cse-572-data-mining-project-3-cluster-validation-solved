# cse-572-data-mining-project-3-cluster-validation-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cse-572-data-mining-project-3-cluster-validation-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;67001&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE 572: Data Mining  Project 3: Cluster Validation Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
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
            5/5 - (3 votes)    </div>
    </div>
<strong>Purpose</strong>

In this project you will apply the cluster validation technique to data extracted from a provided data set.

<h2>Objectives</h2>
Students will be able to:

<ul>
<li>Develop code that performs clustering.</li>
<li>Test and analyze the results of the clustering code.</li>
<li>Assess the accuracy of the clustering using SSE and supervised cluster validity metrics.</li>
</ul>
&nbsp;

<h2>Technology Requirements</h2>
Python 3.6 to 3.8 (do not use 3.9).&nbsp; scikit-learn==0.21.2 pandas==0.25.1

Python pickle

<h2>Project Description</h2>
For this project you will write a program, using Python, that takes a dataset and performs clustering. Using the provided training data set you will perform cluster validation to determine the amount of carbohydrates in each meal.

<h2>Directions</h2>
There are two main parts to the process:

<ol>
<li>Extract features from Meal data</li>
<li>Cluster Meal data based on the amount of carbohydrates in each meal</li>
</ol>
Data:

Use the Project 1 data files

&nbsp;

&nbsp;

CGMData.csv

InsulinData.csv

Extracting Ground Truth:

Derive the max and min value of meal intake amount from the Y column of the Insulin data. Discretize the meal amount in bins of size 20. Consider each row in the meal data matrix that you generated in Project 2. Put them in the respective bins according to their meal amount label.

In total you should have n = (max-min/20) bins.

Performing clustering:

Use the features in your Project 2 to cluster the meal data into n clusters. Use DBSCAN and KMeans.

Report your accuracy of clustering based on SSE, entropy and purity metrics.

Expected Output:

A Result.csv file which contains a 1 X 6 vector. The vector should have the following format

&nbsp;

<table width="720">
<tbody>
<tr>
<td width="120">SSE for Kmeans</td>
<td width="120">SSE for

DBSCAN
</td>
<td width="120">Entropy for

KMeans
</td>
<td width="120">Entropy for

DBSCAN
</td>
<td width="120">Purity for

KMeans
</td>
<td width="120">Purity for

DBSCAN
</td>
</tr>
<tr>
<td width="120"></td>
<td width="120"></td>
<td width="120"></td>
<td width="120"></td>
<td width="120"></td>
<td width="120"></td>
</tr>
</tbody>
</table>
&nbsp;

The Result.csv file should not have any headers, just the six values in six columns.

&nbsp;

<h2>Submission Directions for Project Deliverables</h2>
A zip file which has all your code. In the code you should have one main python file which the autograder can run and generate Result.csv file according to specifications. Assume that CGMData.csv and InsulinData.csv are already in the execution folder. You can have as many auxiliary python files as you want but the autograder will only run the main.py and it should generate the Result.csv.

<h2>Evaluation</h2>
50 points for developing a code in Python that takes the dataset and performs clustering

20 points for developing a code in Python that implements a function to compute SSE, entropy and purity metrics. These two can be written in the same file.

2

&nbsp;

&nbsp;

30 points will be evaluated on the supervised cluster validation results obtained by your code. This will be compared against class average to determine the final score.

&nbsp;

<em>&nbsp;</em>

&nbsp;

3
