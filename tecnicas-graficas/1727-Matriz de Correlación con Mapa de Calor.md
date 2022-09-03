<h2><span style="color:#000000">Correlación:</span></h2>

<p><span style="color:#000000">Es una correlación es una medida estadística. </span><span style="color:#212121">La correlación de datos es una forma de entender la relación entre múltiples valores o características en su conjunto de datos.</span></p>

<p><span style="color:#212121">Todos los proyectos de ciencia de datos que tienen éxito giran en torno a la búsqueda de correlaciones precisas entre las variables de entrada y las de destino. Sin embargo, a menudo nos olvidamos de la importancia del análisis de correlación.&nbsp;</span></p>

<p><span style="color:#212121">Se recomienda realizar un análisis de correlación antes y después de las fases de recopilación y transformación de datos de un proyecto de ciencia de datos.</span></p>

<p><span style="color:#212121">&nbsp;Hay tres tipos diferentes de correlaciones:</span></p>

<ol>
	<li style="list-style-type:decimal"><span style="color:#212121"><strong>Correlación Positiva:</strong> Dos variables pueden estar positivamente correlacionadas entre sí. Significa que cuando el valor de una variable aumenta, el valor de la(s) otra(s) variable(s) también aumenta (también disminuye cuando la otra disminuye).<br />
	Por ejemplo, cuanto más tiempo pases corriendo en una cinta, más calorías quemarás.</span></li>
	<li style="list-style-type:decimal"><span style="color:#212121"><strong>Correlación Negativa:</strong> Dos variables pueden estar negativamente correlacionadas entre sí. Esto ocurre cuando el valor de una variable aumenta y el valor de otra(s) variable(s) disminuye (inversamente proporcional).<br />
	Por ejemplo, a medida que el tiempo se vuelve más frío, los costes del aire acondicionado disminuyen.</span></li>
	<li style="list-style-type:decimal"><span style="color:#212121"><strong>Sin Correlación:</strong> Dos variables pueden no tener ninguna relación entre sí. Esto ocurre cuando se cambia el valor de una variable y el valor de la otra no se ve afectado.<br />
	Por ejemplo, no hay relación entre la cantidad de té que se bebe y el nivel de inteligencia.</span></li>
</ol>

<ul>
	<li><span style="color:#212121">Cada uno de estos tipos de correlación existe en un espectro representado por valores de -1 a +1 donde las características de correlación positiva leve o alta pueden ser como 0,5 o 0,7.</span></li>
	<li><span style="color:#212121">Una correlación positiva muy fuerte y perfecta está representada por una puntuación de correlación de 0,9 o 1.</span></li>
	<li><span style="color:#212121">Si hay una fuerte correlación negativa, se representará con un valor de -0,9 o -1. Los valores cercanos a cero indican que no hay correlación.</span></li>
</ul>

<p><span style="color:#212121">Podemos comprobar cómo se relaciona cada característica con las demás utilizando la función </span><span style="color:#212121">corr()</span><span style="color:#212121">.</span></p>

<p>&nbsp;</p>

<p style="text-align:center"><img alt="" height="459" src="https://dphi-courses.s3.ap-south-1.amazonaws.com/introduction-to-eda/Module3/eda3m4.png" width="1435" /></p>

<p>&nbsp;</p>

<p><span style="color:#212121"><span style="background-color:#ffffff">La creación de una visualización de la matriz de correlación anterior mediante un mapa de calor ayuda a una mejor comprensión. Podemos hacerlo utilizando la función Heatmap de Seaborn.</span></span></p>

<p style="text-align:center"><img alt="" height="966" src="https://dphi-courses.s3.ap-south-1.amazonaws.com/introduction-to-eda/Module3/eda3m5.png" width="1247" /></p>

<h2><span style="color:#212121"><span style="background-color:#ffffff"><strong>Observaciones:</strong></span></span></h2>

<ul>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff"><strong>Alcohol</strong> es la variable que presenta la mayor correlación positiva con la calidad del vino, seguida de otras variables como la acidez, los sulfatos, la densidad y los cloruros.</span></span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">Existe una correlación positiva relativamente alta entre la acidez fija y el ácido cítrico, la acidez fija y la densidad.</span></span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">Existe una correlación negativa relativamente alta entre fixed_acidity y pH.</span></span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">La densidad tiene una fuerte correlación positiva con fixed_acidity, mientras que tiene una fuerte correlación negativa con el alcohol.</span></span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">ácido cítrico & la acidez volátil tienen una correlación negativa.</span></span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">Dióxido de azufre libre &amp; dióxido de azufre total tienen una correlación positiva.</span></span></li>
</ul>