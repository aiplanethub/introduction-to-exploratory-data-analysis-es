<p>&nbsp;&nbsp;</p>

<h2>1. Head - Vista previa de datos</h2>

<p><span style="color:#212121">Para darle una mirada cercana a los datos, tomamos la ayuda de la función &ldquo; .head()&rdquo; de la librería pandas, la cual nos retorna las primera 5 filas de observaciones en el dataset. Similarmente, &ldquo;.tail()&rdquo; nos devuelve las últimas 5 observaciones del dataset.</span></p>

<p><span style="color:#212121">Verás que es una forma estupenda de tener una primera noción de tus datos y quizá ya los entiendas un poco mejor.</span></p>

<p style="text-align:center"><img alt="" height="488" src="https://dphi-courses.s3.ap-south-1.amazonaws.com/introduction-to-eda/Module2/ss3.png" width="1561" /></p>

<p>&nbsp;</p>

<p>&nbsp;</p>

<h2>2. Shape - Tamaño del dataset</h2>

<p><span style="color:#212121">Obtén el número total de filas y columnas del conjunto de datos mediante &ldquo;.shape()&rdquo;.</span></p>

<p style="text-align:center"><img alt="" height="89" src="https://dphi-courses.s3.ap-south-1.amazonaws.com/introduction-to-eda/Module2/ss4.png" width="213" /></p>

<h3><span style="color:#212121"><strong>Observaciones:</strong></span></h3>

<ul>
	<li style="list-style-type:disc"><span style="color:#212121">El Dataset comprende 1599 observaciones(filas) y 12 variables(columnas).</span></li>
	<li style="list-style-type:disc"><span style="color:#212121">De las 12 variables, una es la variable objetivo y las 11 restantes son variables de entrada.</span></li>
</ul>

<p>&nbsp;</p>

<h2><span style="color:#212121">3.&nbsp;&nbsp;Obtener un resumen estadístico usando Describe()</span></h2>

<p><span style="color:#212121">La función describe() en pandas es muy útil para obtener varios estadísticos de resumen. Esta función devuelve el recuento, la media, la desviación estándar, los valores mínimos y máximos y los cuantiles de los datos.</span></p>

<hr />
<p><span style="color:#212121">REPASO: Los datos outliers son observaciones que son significativamente diferentes de otros puntos de datos.</span></p>

<hr />
<p><span style="color:#212121">Siempre es interesante conocer las características estadísticas básicas de cada variable numérica.</span></p>

<p style="text-align:center"><img alt="" height="425" src="https://dphi-courses.s3.ap-south-1.amazonaws.com/introduction-to-eda/Module2/ss5.png" width="1779" /></p>

<p>&nbsp;</p>

<p><span style="color:#212121">Exploremos diferentes medidas estadísticas que hemos obtenido de describe().</span></p>

<ul>
	<li style="list-style-type:disc"><span style="color:#212121"><strong>count:</strong></span><span style="color:#212121"> recuento total de valores no nulos en la columna</span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><strong>mean</strong></span><span style="color:#212121">: la media de todos los valores de esa columna</span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><strong>min:</strong></span><span style="color:#212121"> el valor mínimo de la columna</span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><strong>max:</strong></span><span style="color:#212121"> el valor máximo de la columna</span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><strong>25%:</strong></span><span style="color:#212121"> primer cuartil de la columna después de ordenar esos valores en orden ascendente</span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><strong>50%:</strong></span><span style="color:#212121"> es la mediana o el segundo cuartil</span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><strong>75%:</strong></span><span style="color:#212121"> el tercer cuartil</span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><strong>std:</strong></span><span style="color:#212121"> se trata de la desviación estándar (es decir, la medida de depreciación, que deberías haber leído en el material de estudio de Fundamentos de la Estadística)</span></li>
</ul>

<p><span style="color:#212121"><strong>Note:</strong></span><span style="color:#212121"> El 25%, el 50% y el 75% no son más que los valores percentiles correspondientes</span></p>

<p>&nbsp;</p>

<h3><span style="color:#212121"><strong>Observaciones:</strong></span></h3>

<ul>
	<li style="list-style-type:disc"><span style="color:#212121">Aquí, como puede observar, el valor medio es inferior al valor de la mediana de cada columna. La mediana está representada por el 50% (percentil 50) en la columna del índice.</span> Esto significa la presencia de valores atípicos. Por ejemplo, un conjunto de datos incluye valores 30, 31, 32 y 2. El valor medio (23,75), que es inferior a la mediana de los datos (30,5), se ve muy afectado por el punto de datos extremo (2).&nbsp;</li>
	<li style="list-style-type:disc"><span style="color:#212121">Hay una gran diferencia entre el 75 % y los valores máximos de los predictores &ldquo;residual sugar&rdquo;, &rdquo; free sulfur dioxide&rdquo;, &rdquo; total sulfur dioxide&rdquo;.&nbsp;</span><span style="color:#212121">Esto indica que algunos valores de estas 3 variables se encuentran mucho más lejos del rango general de valores ( hasta el 75% cuantil)&nbsp;</span></li>
	<li style="list-style-type:disc"><span style="color:#212121">Así, las observaciones 1 y 2 sugieren que hay valores extremos, es decir, outliers, en nuestro conjunto de datos.&nbsp;</span></li>
</ul>