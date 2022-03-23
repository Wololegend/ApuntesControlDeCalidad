# Apuntes - Control De Calidad
## Jaime Simeón Palomar Blumenthal - alu0101228587@ull.edu.es

## Entorno de la calidad total

A mayor calidad menos inconvenientes para el usuario.

La calidad tiene escalas: relación calidad precio. Es subjetiva, depende de quien utilice el producto/servicio.

En la era industrial la calidad ya no sólo depende del producto en sí: Costes, plazo de entrega, servicio postventa, etc...

**Prioridad:**

* Más demanda y menos capacidad de oferta => Gestión empresarial orientada a la producción masiva. CALIDAD NO PRIORITARIA.

* Menos demanda y más capacidad de oferta => Gestión empresarial orientada al cliente con CALIDAD PRIORITARIA.

**La calidad estratégica como factor de competitividad indstrial**.

### Proceso de control de calidad

En un principio se realizaba un control al final de la cadena de producción (Inspección). El problema es la fatiga del inspector, que al final del día empieza a pasar productos defectuosos y la falta de comunicación entre inspector y responsable del proceso que reajusta la cadena.

Ahora, en cada paso del proceso se realizan reajustes de la cadena de producción y mediciones para el control de calidad. Además una medición final.

Más recientemente se implementan las especativas del cliente mediante la Investigación dle Mercado, que es básicamente, feedback del cliente para saber sus necesidades.

**El control de calidad es una actividad globalizadora, que incluye, no sólo a todas las personas y procesos de una cierta empresa, sino también a los proveedores y a los distribuidores.**


### Mantenimiento, mejora e innvación

* **Mantenimiento**: Actividades que tienden a conservar los estándares tecnológicos, de gestión y de operación de la cadena de producción. Por ejemplo, al saltar de un helicóptero de rescate, el estándar es comprobar el equipo y mirar izquierda, centro y derecha.

  Los estándares tienen que estar registrados y ser CLAROS. El cumplimiento de los estándares es responsabilidad de la gestión de la empresa.

* **Mejora contínua**: Las situaciones dirigidas hacia la mejora constante de los estándares actuales.

  Todos los procesos generan información suficiente para mejorarlo. Cuando un estándar está más de seis meses sin se mejorado, puede ser debido a que nadie realiza un seguimiento en la organización.

* **Innovación**: Feedback obtenido de los empleados que sirve para mejorar, añadir o cambiar productos/servicios a favor de los intereses del cliente.

### Círculo de Deming

1. **PLAN**: Definir objetivos, medidas para realizar mediciones, equipo responsable de la mejora y de recursos necesarios para alcanzar los objetivos.

2. **DO**: Educar al personal sobre la implementación de la mejora y puesta en práctica de las mejoras.

3. **CHECK**: Verificar los resultados y si se han aplicado todas las soluciones propuestas.

4. **ACTION**: Mejorar el plan de mejora constante, fijando nuevos objetivos, o moduficando el proceso de educación, los recursos, etc...

5. **REPETIR EL PROCESO**.

### Pilares de la Calidad Total

* **Cultura de la calidad**: Sorprender al cliente y empleado atendiendo a sus necesidades (Limpieza, rediseño, mejora de calidad de vida de los trabajadores).

* **Sistemas y recursos humanos**: Involucrar tanto a empleados como a subcontratadas en los estándares de calidad de la organización.

* **Uso de la estadística**: Uso del método científico, basado en la evidencia, no en opiniones. Hoy en día todo se puede medir. Todo el personal tiene que tener cierta idea de estadística.


## Introducción a las herramientas estadísticas de Control de Calidad

Tomar, clasificar y representar datos, y extraer consecuencias científicas de ellos.

* **Estadística Descriptiva**: Recoger, clasificar y representar datos.
* **Inferencia estadística**: Llegar a conclusiones válidas a partir de los datos.

El fichero a utilizar con los datos es _habitos.sav_, con datos de 175 estudiantes sobre 26 variables de interés: id, sexo, estudios, asistencia anual al cine, fútbol, conciertos, etc...

### **Estadística descriptiva**

Existen dos tipos de datos:

* **Cuantitativos**: Se expresan numericamente. Son discretos (valores numéricos aislados) o Continuos.
* **Categóricos o Cualitativos**: No se expresan numéricamente. Son ordinales (Admiten una ordenación lógica y ascendente) y No Ordinales.

#### **Síntesis de datos**

Trata de reducir la información de una muestra de datos: medias, mediana, desviación típica, etc...

El alfabeto griego hace referencia a toda la población, y el afabeto latino representa una muestra de la población. Nunca vamos a conocer la población (mu) porque hace referencia a todos los usuarios, por ejemplo, pero se puede estimar mediante la media.


### **Operaciones con variables**

Con las variable cualitativas se pueden hacer tablas de frecuencias y representar la información en grafos de barras.

Las variables cuantitativas permiten muchas más operaciones: medias, etc... y se representa en histogramas (cuando son contínuas) y diagramas de barras (si son discretas).

Viendo el histograma, podemos determinar si la distribución es normal (Campana de Gauss). Sabiendo si es o no normal, la medida representativa será la media o la mediana.

Los **Percentiles** determinan cuántas de las medidas se han dejado atrás: el percentil 95 de la variable Horas de TV es 22, es decir, que el 95% de los usuarios ven menos de 22 horas de TV. Los percentiles sirven para compararnos entre nuestros semejantes.

La **Mediana** es el valor que deja el 50% de los valores por encima y por debajo.

La **Media recortada al 5%**, recorta los percentiles del 95 en adelante y del 0 al 5, antes de hacer la media.

Si yo voy tomando muestras aleatorias, calculando sus medias, y las represento en un histograma obtengo una distribución normal SIEMPRE. Si calculamos la desviación típica de las medias, obtengo el **error típico**. Es lo que se desvía la media de nuestra muestra global de la media de toda la población.

La **Desviación típica** sirve para saber cuánto se desvían los datos de la media.

* Medidas de posición: Media y mediana.
* Medidas de dispersión: Desviación típica.

### **Forma de la distribución**

El diagrama de cajas nos representa la mediana (Línea en negrita), el mínimo y máximo (Bordes de las líneas), los cuartiles (Mínimo hasta la caja, comienzo de la caja hasta la mediana, mediana hasta el final de la caja, y final de la caja hasta el máximo). El rango intercuartil es la caja, y es donde se encuentra el mejor 50% de los datos.

Midiendo a mano la caja, si encontramos datos por encima de una vez y media el largo de la caja, son datos MUY RAROS, y se representan con circulitos y estrellitas. Son **puntos anómalos** y van encima del bigote que determinaría el máximo en otro caso. Si encontramos datos por encima de tres veces el largo de la caja (rango intercuartil), se denominan **datos extremos**.

El diagrama de datos y bigotes se utiliza principalmente para encontrar esos puntos extremos.


### **Relación entre dos variables**

* [**Dos cuantitativas contínuas**](https://campusingenieriaytecnologia2122.ull.es/mod/resource/view.php?id=29033): Se hace mediante un gráfico de dispersión o nube de puntos.

* [**Una cualitativa y otra cuantitativa**](https://campusingenieriaytecnologia2122.ull.es/mod/resource/view.php?id=29034): Es un diagrama de barras con medias. Por ejemplo, si hacemos el número de horas de TV semanales según el sexo, calculamos la media y la desviación típica de cadauno de los sexos y lo representamos. Si hay relación entre las dos variables, las medias son distintas.

* [**Dos variables cualitativas**](https://campusingenieriaytecnologia2122.ull.es/mod/resource/view.php?id=29032): Grafo de barras apiladas. Si hay diferencia entre los porcentajes, hay relación entre las dos variables.


# Componentes principales

Es una técnica que permite analizar factores abstractos (amor, odio, etc) a partir de variables aleatorias cuantitativas.

A nivel práctico, consiste en resumir varias variables en una creada por nosotros y con un significado propio. Por ejemplo, podemos agrupar el peso y altura en una nueva variable que se llame Tamaño. Esto lo podemos hacer porque las variables están correlacionadas: a más altura, más peso (por lo general).

Para saber si nuestras variables están relacionadas, necesitamos la Matriz de Correlaciones.