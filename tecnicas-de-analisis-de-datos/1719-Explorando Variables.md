# Explorando los Features/Variables

<p><span style="color:#212121">Las variables y features son lo mismo, a menudo se utilizan indistintamente. Todos los nombres de columnas de un conjunto de datos son variables.</span></p>

<p><span style="color:#212121">Exploremos los features/columnas del dataset.</span></p>

<p style="text-align:center"><img alt="" height="149" src="https://dphi-courses.s3.ap-south-1.amazonaws.com/introduction-to-eda/Module2/ss6.png" width="758" /></p>

<p>&nbsp;</p>

<p>&nbsp;</p>

<h4><span style="color:#212121"><strong>Variable objetivo:</strong></span></h4>

<p><span style="color:#212121">La variable objetivo de un conjunto de datos es la variable de un dataset sobre la que se desea obtener una comprensión más profunda. Es la variable que es, o debería ser la salida del modelo.</span></p>

<p><span style="color:#212121">Aquí </span><span style="color:#212121"><strong>quality</strong></span><span style="color:#212121"> es la variable objetivo dado que estamos intentando predecir cual de los dos vinos tiene mejor calidad.</span></p>

<p>&nbsp;</p>

<h4><span style="color:#212121"><strong>Variables de entrada:</strong></span></h4>

<p><span style="color:#212121">Una o más variables que se utilizan para determinar (o predecir) la &#39;Variable objetivo&#39; son conocidas como variables de entrada. En algunos casos también se les conoce como Variables predictoras</span></p>

<p><span style="color:#212121">En nuestro ejemplo las variables de entrada, son: &#39;fixed acidity&#39;, &#39;volatile acidity&#39;, &#39;citric acid&#39;, &#39;residual sugar&#39;, &#39;chlorides&#39;, &#39;free sulfur dioxide&#39;, &#39;total sulfur dioxide&#39;, &#39;density&#39;, &#39;pH&#39;, &#39;sulphates&#39;, y &#39;alcohol&#39;.</span></p>

<p><span style="color:#212121">Todas estas variables nos ayudarán a predecir la calidad del vino.</span></p>

<p>&nbsp;</p>

<p><span style="color:#212121"><span style="background-color:#ffffff">Después de cargar los datos, es importante examinarlos. Por lo general, no se recomienda introducir directamente todos los datos en el modelo sin entenderlos. Este paso siempre ayuda a mejorar nuestro modelo.</span></span></p>

<p>&nbsp;</p>

<h2><span style="color:#212121"><span style="background-color:#ffffff">1.&nbsp;Valores únicos de calidad (Variable objetivo)</span></span></h2>

<p style="text-align:center"><img alt="" height="271" src="https://dphi-courses.s3.ap-south-1.amazonaws.com/introduction-to-eda/Module2/ss7.png" width="499" /></p>

<p>&nbsp;</p>

<h3><span style="color:#212121"><span style="background-color:#ffffff"><strong>Observaciones:</strong></span></span></h3>

<p><span style="color:#212121"><span style="background-color:#ffffff">A continuación se exponen algunas ideas clave con sólo observar la variable objetivo:</span></span></p>

<ul>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">Variable objetivo/Variable dependiente es discreta y de naturaleza categórica .</span></span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff"> La escala del puntaje de &ldquo;quality&rdquo; tiene un rango desde 1 hasta 10; 1 siendo el peor y 10 siendo el mejor.</span></span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">Los puntaje de calidad de 1,2,9 &amp; 10 no están asignados a ninguna observación. Los únicos puntajes obtenidos están en el rango de 3 hasta 8.</span></span></li>
</ul>

<p>&nbsp;</p>

<h2><span style="color:#212121"><span style="background-color:#ffffff">2.&nbsp;Frequency Counts of each Quality Value</span></span></h2>

<p style="text-align:center"><img alt="" height="338" src="https://dphi-courses.s3.ap-south-1.amazonaws.com/introduction-to-eda/Module2/ss8.png" width="556" /></p>

<h3><span style="color:#212121"><span style="background-color:#ffffff"><strong>Observaciones:</strong></span></span></h3>

<ul>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">Esto nos indica el recuento de votos de cada puntuación de calidad en orden descendente.</span></span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">&ldquo;quality&rdquo; tiene la mayoría de los valores concentrados en las categorías 5, 6 y 7.</span></span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">Sólo se han hecho algunas observaciones para las categorías 3 &amp; 8.</span></span></li>
</ul>

<p>&nbsp;</p>

<h2><span style="color:#212121"><span style="background-color:#ffffff">3.&nbsp; Renombrar Columnas </span></span></h2>

<p><span style="color:#212121"><span style="background-color:#ffffff">Cambiemos el nombre de las columnas que contienen espacios en sus nombres y sustituyamos los espacios por guiones bajos.</span></span></p>

<p style="text-align:center"><img alt="" height="447" src="https://dphi-courses.s3.ap-south-1.amazonaws.com/introduction-to-eda/Module2/ss9.png" width="1318" /></p>

<p>&nbsp;</p>