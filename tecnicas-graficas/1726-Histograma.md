<p><span style="color:#212121">Histograms use bars to visualize data as well. Many people may not even realize there is a difference between a histogram and a bar chart. They practically look the same from a distance.</span></p>

<p><span style="color:#212121">The key is that a histogram looks solely at quantitative variables while a bar chart looks at categorical variables. That&rsquo;s why the bars in a histogram are typically grouped together without spacing in between the bars.</span></p>

<p style="text-align:center"><img alt="" src="https://www.edrawsoft.com/howto/charts-comparison.png" /></p>

<p>Let&#39;s plot a histogram now! On calling the hist( ) method on a DataFrame, you&#39;ll get histograms for all the Series.</p>

<p style="text-align:center"><img alt="" height="974" src="https://dphi-courses.s3.ap-south-1.amazonaws.com/introduction-to-eda/Module3/eda3m3.png" width="1202" /></p>

<p>&nbsp;</p>

<h3><span style="color:#212121"><strong>Observations:</strong></span></h3>

<ul>
	<li style="list-style-type:disc"><span style="color:#212121">The distribution of the attribute &ldquo;alcohol&rdquo; seems to be positively skewed&nbsp;</span><span style="color:#212121">i.e the curve is shifted towards the left.</span></li>
	<li style="list-style-type:disc"><span style="color:#212121">The attributes &#39;</span><span style="color:#212121"><strong>density</strong></span><span style="color:#212121">&#39; and &#39;</span><span style="color:#212121"><strong>pH</strong></span><span style="color:#212121">&#39; are quite normally distributed.</span></li>
	<li style="list-style-type:disc"><span style="color:#212121">Now looking at the attribute </span><span style="color:#212121"><strong>quality</strong></span><span style="color:#212121">, we can observe that the wines with average quality (i.e. quality rating 5 to 7) are more than wines with bad(1-4) or good(8-10) quality.</span></li>
</ul>