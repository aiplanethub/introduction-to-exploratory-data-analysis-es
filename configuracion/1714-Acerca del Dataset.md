<p><span style="color:#212121">El dataset que usaremos aquí es el </span><a href="https://archive.ics.uci.edu/ml/datasets/wine+quality" style="text-decoration:none"><span style="color:#1155cc"><u>Wine Quality data</u></span></a><span style="color:#212121">, el cual contiene información acerca vinos rojos y blancos.</span></p>

<p><span style="color:#212121">La calidad del vino se basa en las puntuaciones sensoriales (mediana de al menos 3 evaluaciones realizadas por expertos en vino). Cada experto calificó la calidad del vino entre 0 (muy malo) y 10 (muy excelente).</span></p>

<p><span style="color:#212121">Este popular conjunto de datos se utiliza habitualmente para predecir si un determinado vino es &ldquo;good quality&rdquo; o no lo es.</span></p>

<hr />
<p><span style="color:#212121">REPASO:</span></p>

<p><span style="color:#212121"><u>1. Variable objetivo:</u></span><span style="color:#212121"> La variable objetivo o etiqueta de un conjunto de datos es la característica de un conjunto de datos sobre la que se desea obtener una comprensión más profunda.&nbsp;</span></p>

<p><span style="color:#212121">Es la variable que es, o debería ser la salida del modelo.</span></p>

<p><span style="color:#212121">En el ejemplo de la detección de spam en emails, la etiqueta será la categoría a la que pertenece el correo electrónico, es decir, será &lsquo;spam&rsquo; o &lsquo;not spam&rsquo;.</span></p>

<p><span style="color:#212121"><u>2. Variable de entrada:</u></span><span style="color:#212121">&nbsp; Una o más variables que se utilizan para determinar (o predecir) el &#39;Variable objetivo&#39; se conocen como Variables de entrada. A veces también se les llama Variable de Predicción.</span></p>

<p><span style="color:#212121">En el ejemplo del detector de spam en emails, las variables de entrada podrían incluir lo siguiente:</span></p>

<ul>
	<li style="list-style-type:disc"><span style="color:#212121">Palabras en el texto del email</span></li>
	<li style="list-style-type:disc"><span style="color:#212121">Dirección de correo del remitente</span></li>
	<li style="list-style-type:disc"><span style="color:#212121">Hora del día en que se envío el mail</span></li>
	<li style="list-style-type:disc"><span style="color:#212121">Si el email contiene la frase &quot;Felicidades ganaste $1 billion - Compartenos tu información bancaria.&quot;</span></li>
</ul>

<hr />
<p><span style="color:#212121">¿Cuáles son las variables de entrada y objetivo en el problema de detección de vinos? Démosles una mirada:</span></p>

<p><span style="color:#212121"><strong>Variables de entrada:</strong></span></p>

<ol>
	<li style="list-style-type:decimal"><span style="color:#212121">Acidez fija (fixed acidity)</span></li>
	<li style="list-style-type:decimal"><span style="color:#212121">Volatilidad de la acidez (volatile acidity)</span></li>
	<li style="list-style-type:decimal"><span style="color:#212121">Acidez cítrica (citric acid)</span></li>
	<li style="list-style-type:decimal"><span style="color:#212121">Azúcar residual (residual sugar)</span></li>
	<li style="list-style-type:decimal"><span style="color:#212121">cloruros (chlorides)</span></li>
	<li style="list-style-type:decimal"><span style="color:#212121">Libre de dióxido de sulfuro (free sulfur dioxide)</span></li>
	<li style="list-style-type:decimal"><span style="color:#212121">Dióxido de sulfuro total (total sulfur dioxide)</span></li>
	<li style="list-style-type:decimal"><span style="color:#212121">Densidad (density)</span></li>
	<li style="list-style-type:decimal"><span style="color:#212121">pH</span></li>
	<li style="list-style-type:decimal"><span style="color:#212121">Sulfatos (sulphates)</span></li>
	<li style="list-style-type:decimal"><span style="color:#212121">Alcohol</span></li>
</ol>

<p><span style="color:#212121"><strong>Variable de salida:</strong></span></p>

<ol start="12">
	<li style="list-style-type:decimal"><span style="color:#212121">Calidad del vino (quality, puntos entre 0 y 10)</span></li>
</ol>

<p>&nbsp;</p>

<hr />
<p><span style="color:#212121">En este módulo realizaremos el EDA sobre datos de vino tinto, luego podrá practicar lo aprendido sobre datos de vino blanco.</span></p>

<p>&nbsp;</p>