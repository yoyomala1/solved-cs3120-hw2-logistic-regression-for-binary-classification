Download Link: https://assignmentchef.com/product/solved-cs3120-hw2-logistic-regression-for-binary-classification
<br>
(NumPy, Pandas and data visualization packages are allowed.)

(SKLearn regression models are allowed!)

Reference code: 2_Logostic_ExSKLearn_Demo.py in blackboard




<ol>

 <li>S<strong>elect a dataset with binary target values</strong> using <a href="https://machinelearningmastery.com/standard-machine-learning-datasets/">https://machinelearningmastery.com/standard-machine-learning-datasets</a><a href="https://machinelearningmastery.com/standard-machine-learning-datasets/">/</a></li>

</ol>

e.g. banknote or diabetes dataset




<ol start="2">

 <li><strong>Use pandas to read CSV file as dataframe. (1pt)</strong></li>

</ol>

<strong>e.g. The following code helps import pima diabetes dataset</strong>

<em>col_names = [‘pregnant’, ‘glucose’, ‘bp’, ‘skin’, ‘insulin’, ‘bmi’, ‘pedigree’, ‘age’, ‘label’]</em>

<em># load dataset</em>

<em>pima = pd.read_csv(“pima-indians-diabetes-database.csv”, header=None, names=col_names)</em>

<em> </em>

<ol start="3">

 <li><strong>Select 5 (if not possible then select 4) features from the chosen dataset. (1pt) </strong></li>

</ol>

<strong>List all features you selected in your report.</strong>

For example, the following code will select two features

<em>feature_cols = [‘pregnant’, ‘age’]</em>

<em>X = pima[feature_cols]</em>




<ol start="4">

 <li>Use “train _test_split” from “sklearn.cross_validationtrain” to split test and training data by 40% testing + 60% training. <strong> (1pt)</strong></li>

</ol>

<strong> </strong>

<ol start="5">

 <li>Fit your model with training data and test your model after fitting.</li>

</ol>




<ol start="6">

 <li>Calculate and plot out</li>

</ol>

the confusion matrix  <strong>(1pt)</strong>

precision score, recall score, F score <strong>(3pts)</strong>

<strong>Copy your console output (these scores) to your report</strong>.




<ol start="7">

 <li>Plot out the ROC curve and print out the ROC_AUC score (sklearn.metrics.roc_curve() and sklearn.metrics.roc_auc_score() can be used.) <strong>(3pts)</strong></li>

</ol>




<em>——————————————————————————————————————–</em>

<strong>Submit your report and your code in two different files. </strong>

<strong>Please include the required figure/plot in your report.</strong>

<strong>e.g.</strong>

<strong>File1: Assignment2_FirstnameLastname.doc/.pdf (this is the report)</strong>

<strong>+</strong>

<strong>File2: Assignment2_ FirstnameLastname.py (this is the code. only “.py” files accepted. </strong>

<strong><em>            OR</em></strong>

<strong><em>          Assignment2_ FirstnameLastname.zip if you have multiple “.py” files.</em></strong><strong>)</strong>