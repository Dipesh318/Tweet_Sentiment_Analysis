<h1>Tweet_Sentiment_Analysis</h1>

<h4>Every Tweet is divided into three class i.e.,</h4>
<ul>
  <li>Positive/Extremely Positive(label = 1)</li>
  <li>Negative/Extremely Negactive(label = -1)</li>
  <li>Netural(label = 0)</li>
</ul>
<h4>Preprocessing is required to clean tweets.</h4>
As it is text data, I have used both <li><b><i>CountVectorization</i></b></li> <li><b><i>TfidVectorization</i></b></li>

<h4>Machine Learning Models used : </h4>
<ul>
  <li> Decision Tree (with various Depth)</li>
  <li> MultinomialNB </li>
  <li> RigidClassifier</li>
  <li> LogisticRegression </li>
</ul>


<p> For every model, their ROC_AUC Score as well as Accuracy Score are predicted with different parameter. </p>

<p> PS : spellchecker() requires a lot of time to run. </p>
