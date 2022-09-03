<p><span style="color:#212121"><span style="background-color:#ffffff">El tratamiento de los datos faltantes es una parte esencial del proceso de limpieza y preparación de datos, ya que casi todos los datos de la vida real contienen algunos datos perdidos.</span></span></p>

<p><span style="color:#212121"><span style="background-color:#ffffff">Pandas incluye las funciones </span></span><span style="color:#212121"><span style="background-color:#ffffff">isnull()</span></span><span style="color:#212121"><span style="background-color:#ffffff">, </span></span><span style="color:#212121"><span style="background-color:#ffffff">isna()</span></span><span style="color:#212121"><span style="background-color:#ffffff"> para detectar valores faltantes. Ambas funciones hacen los mismo.</span></span></p>

<ul>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">df.isna()</span></span><span style="color:#212121"><span style="background-color:#ffffff"> devuelve el dataframe con returns the dataframe con valores TRUE o FALSE indicando si hay valores faltantes. </span></span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">También podrías elegir utilizar </span></span><span style="color:#212121"><span style="background-color:#ffffff">notna()</span></span><span style="color:#212121"><span style="background-color:#ffffff"> que es basicamente lo opuesto a isna().</span></span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">df.isna().any()</span></span><span style="color:#212121"><span style="background-color:#ffffff"> entrega un valor TRUE o FALSE para cada columna. Si solamente hay un valor faltante en esa columna, el valor será TRUE.</span></span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">df.isna().sum()</span></span><span style="color:#212121"><span style="background-color:#ffffff"> entrega el número de valores faltantes por cada columna.</span></span></li>
</ul>

<p>&nbsp;</p>

<h2><span style="color:#212121">1.&nbsp;</span><span style="color:#212121"><span style="background-color:#ffffff">isna()</span></span></h2>

<p style="text-align:center"><img alt="" height="453" src="https://dphi-courses.s3.ap-south-1.amazonaws.com/introduction-to-eda/Module2/ss10.png" width="549" /></p>

<h3><span style="color:#212121"><strong>Observación:</strong></span></h3>

<p><span style="color:#212121">No hay valores faltantes en ninguna columna.</span></p>

<h2>2.&nbsp;<span style="color:#212121"><span style="background-color:#ffffff">info()</span></span></h2>

<p><span style="color:#212121"><span style="background-color:#ffffff">df.info devuelve información sobre el dataframe, incluyendo los tipos de datos de cada columna, el número de valores nulos en cada columna y el uso de memoria de todos los datos.</span></span></p>

<p style="text-align:center"><img alt="" height="511" src="https://dphi-courses.s3.ap-south-1.amazonaws.com/introduction-to-eda/Module2/ss11.png" width="629" /></p>

<h3><span style="color:#212121"><span style="background-color:#ffffff"><strong>Observaciones:</strong></span></span></h3>

<ul>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">El dataframe tiene solamente datos de tipo float y enteros.</span></span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">No hay datos faltantes</span></span></li>
</ul>