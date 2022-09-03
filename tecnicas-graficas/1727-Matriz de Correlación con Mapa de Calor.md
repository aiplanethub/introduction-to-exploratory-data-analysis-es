<h2><span style="color:#000000">Correlation:</span></h2>

<p><span style="color:#000000">Correlation is a statistical measure. </span><span style="color:#212121">Data correlation is a way to understand the relationship between multiple values or features in your dataset.</span></p>

<p><span style="color:#212121">Every single successful data science project revolves around finding accurate correlations between the input and target variables. However more than often, we oversee how crucial correlation analysis is.&nbsp;</span></p>

<p><span style="color:#212121">It is recommended to perform correlation analysis before and after data gathering and transformation phases of a data science project.</span></p>

<p><span style="color:#212121">&nbsp;There are three different types of correlations:</span></p>

<ol>
	<li style="list-style-type:decimal"><span style="color:#212121"><strong>Positive Correlation:</strong> Two features (variables) can be positively correlated with each other. It means that when the value of one variable increases then the value of the other variable(s) also increases (also decreases when the other decreases).<br />
	Eg. The more time you spend running on a treadmill, the more calories you will burn.</span></li>
	<li style="list-style-type:decimal"><span style="color:#212121"><strong>Negative Correlation:</strong> Two features (variables) can be negatively correlated with each other. This occurs when the value of one variable increases and the value of another variable(s) decreases (inversely proportional).<br />
	Eg. As the weather gets colder, air conditioning costs decrease.</span></li>
	<li style="list-style-type:decimal"><span style="color:#212121"><strong>No Correlation:</strong> Two features might not have any relationship with each other. This happens when the value of a variable is changed then the value of the other variable is not impacted.<br />
	Eg. There is no relationship between the amount of tea drunk and level of intelligence.</span></li>
</ol>

<ul>
	<li><span style="color:#212121">Each of these correlation types exists in a spectrum represented by values from -1 to +1 where slight or high positive correlation features can be like 0.5 or 0.7.</span></li>
	<li><span style="color:#212121">A very strong and perfect positive correlation is represented by a correlation score of 0.9 or 1.</span></li>
	<li><span style="color:#212121">If there is a strong negative correlation, it will be represented by a value of -0.9 or -1. Values close to zero indicates no correlation.</span></li>
</ul>

<p><span style="color:#212121">We can check how each feature is related to others using </span><span style="color:#212121">corr()</span><span style="color:#212121"> function.</span></p>

<p>&nbsp;</p>

<p style="text-align:center"><img alt="" height="459" src="https://dphi-courses.s3.ap-south-1.amazonaws.com/introduction-to-eda/Module3/eda3m4.png" width="1435" /></p>

<p>&nbsp;</p>

<p><span style="color:#212121"><span style="background-color:#ffffff">Creating a pictorial visualisation of the above correlation matrix using a heatmap helps in better understanding. We can do that using Seaborn&#39;s Heatmap function.</span></span></p>

<p style="text-align:center"><img alt="" height="966" src="https://dphi-courses.s3.ap-south-1.amazonaws.com/introduction-to-eda/Module3/eda3m5.png" width="1247" /></p>

<h2><span style="color:#212121"><span style="background-color:#ffffff"><strong>Observations:</strong></span></span></h2>

<ul>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff"><strong>Alcohol</strong> has the highest positive correlation with wine quality, followed by the various other variables such as acidity, sulphates, density &amp; chlorides.</span></span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">There is a relatively high positive correlation between fixed_acidity and citric_acid, fixed_acidity and density.</span></span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">There is a relatively high negative correlation between fixed_acidity and pH.</span></span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">Density has a strong positive correlation with fixed_acidity, whereas it has a strong negative correlation with alcohol.</span></span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">citric acid &amp; volatile acidity have negative correlation.</span></span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">free sulphur dioxide &amp; total sulphur dioxide have positive correlation.</span></span></li>
</ul>