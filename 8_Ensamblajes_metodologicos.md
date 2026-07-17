# 8\. Ensamblajes metodológicos: Algoritmos, Métodos visuales y etnográficos. ¿Qué hace un modelo de visión computarizada? They see your photos (construcción de base de datos)

3/09/26



##### Descripción de la sesión:



En esta sesión veremos las posibilidades combinatorias de los métodos digitales. Cuando tenemos una construcción teórica y empírica sólida podemos tomar herramientas técnicas y convertirlas en un *ensamblaje metodológico*, o como John Law lo nombra, un *agenciamiento de método*. Esto consiste en una construcción robusta y basada en distintas aproximaciones a los fenómenos que nos permiten ver su complejidad y sus múltiples aristas para arrivar a conclusiones más interesantes y novedosas para ejercer agencia sobre aquello que investigamos. Esta aproximación se sale del diagnóstico para convertirse en una forma de participación digital sobre lo que estudiamos



El taller girará alrededor de una forma muy precaria y "*low-tech*" para construir una base de datos usando una implementación sobre la API de Google Visión llamada [*They See Your Photos*](https://theyseeyourphotos.com/). Esta herramienta nos permite subir retratos de personas para ver las inferencias que arroja el modelo de visión computarizada de Google en varias aristas en la pestaña *"Data*":

* People. La(s) persona(s) que aparece(n) en la foto
* Race. "Raza" inferida de la(s) persona(s) en la foto
* Income Range. Rango salarial inferido de la(s) persona(s) en la foto
* Religion. Religión inferida de la(s) persona(s) en la foto
* Sexual Orientation. Orientación sexual inferida de la(s) persona(s) en la foto
* Emotions. Emociones inferidas de la(s) persona(s) en la foto
* Clothing. Ropa de la(s) persona(s) en la foto
* Interests. Intereses inferidos de la(s) persona(s) en la foto
* Political Affiliation. Afiliación política inferida de la(s) persona(s) en la foto
* Biases. Sesgos inferidos de la(s) persona(s) en la foto
* Objects. Objetos que aparecen en la imagen
* Insights. Notas en lenguaje natural sobre lo que puede representar la foto
* Targeted Ads. Posibles anuncios que serían mostrados a la(s) persona(s) en la foto según inferencia



Al igual que estos datos en una tabla, hay una descripción en lenguaje natural sobre las personas y si la foto posee metadatos de localización, dónde fue tomada.



Al ser este un tema **muy delicado**, utilizaremos fotografías de stock como [iStock](https://www.istockphoto.com/photos/portrait), [Pexels](https://www.pexels.com/search/portrait/), [Unsplash](https://unsplash.com/s/photos/portrait) o [Adobe Stock](https://stock.adobe.com/search?k=portrait) para encontrar retratos de personas que tienen un **consentimiento informado sobre el uso de su imagen, y teniendo en cuenta que esto sólo establece fines educativos y requiere discresión**. Bajo ninguna circunstancia se recomienda subir imágenes de ustedes y mucho menos de terceros, debemos recordar que en Colombia la cara es un dato biométrico y como tal está protegido por leyes de privacidad y manejo de la información que no podemos garantizar.



Al ser imágenes de *stock*, cada una tiene un URL, por lo que registraremos los URL de las imágenes que seleccionemos (unas 10 como mínimo) en una hoja de cálculo (Excel, LibreO, OpenO, Google, etc.) y entraremos en el papel de un(a) anotador(a) de contenido. Si bien en la sesión pasada hablamos de IA, podemos ponernos en el lugar de las cientos de miles de personas que día a día anotan todo tipo de información para el entrenamiento de estos modelos cada vez más hambrientos de datos. Para ello, seleccionaremos 3 de las 13 dimensiones analizadas por el modelo de visión computarizada de Google en [They See Your Photos](https://theyseeyourphotos.com/) y usaremos nuestro criterio **y respeto** para completar esta información como si de nosotros dependiese categorizar.



Posteriormente, usaremos estas mismas 10 imágenes y las correremos por la página de [They See Your Photos](https://theyseeyourphotos.com/) de la siguiente manera:



|URL|Emotions\_mia|Religion\_mia|Clothing\_mia|People\_theyseeyourphotos|...|
|-|-|-|-|-|-|
|gGTVJ5148|Alegre|Islam|Camisa de botones|Father, toddler, young boy|...|
|hgbIB9257|Enojado|Agnostico|Pantalones de seda|Partners, Late Twenties|...|
|JHklmN895|Triste|Catolico|Pantaloneta y camiseta|Married couple, children|...|
|JBhvtVCDJ|Enojado|Agnostico|Chaqueta de cuero|Friends, adolescents in their late teens, early twenties|...|
|959ggUBYV|Alegre|Cristiano|Vestido de gala|Lone individual, mid-to-late 20s, solitary presence|...|
|...|...|...|...|...|...|



\*Nótese que los nombres de las columnas deben distinguir aquellas dimensiones anotadas por ustedes de las de *They See Your Photos* **sin espacios** y procuremos no usar tildes en las celdas.

\*\*No guardaremos ninguna imagen de los actores y actrices que están retratados en las imágenes, sólo las URL.



##### ¿Qué productos salen de esta sesión?



Base de datos **privada** que podremos utilizar en la sesión de minería de texto para extraer diversos *clusters* sobre las personas en las imágenes de *stock*.



###### Lecturas obligatorias

* Omena, J. J., Lobo, T., Tucci, G., Bitencourt, E., de Keulenaar, E., Kerche, F. W., Chao, J., Liedtke, M., Li, M., Paschoal, M. L., \& Lavrov, I. (2024). Quali-quanti visual methods and political bots: A cross-platform study of pro- \& anti-bolsobots. *Journal of Digital Social Research*, 6(1), 50–73. https://doi.org/10.33621/jdsr.v6i1.215 https://jdsr.se/ojs/index.php/jdsr/article/view/215/104



* Colombo, G., \& Niederer, S. (2021). Visual methods for online images: Collection, circulation, and machine co-creation. *Diseña*, (19), Introduction. https://doi.org/10.7764/disena.19.Intro https://revistadisena.uc.cl/index.php/Disena/article/view/41551/33503



###### Lecturas complementarias

* Seaver, N. (2017). Algorithms as culture: Some tactics for the ethnography of algorithmic systems. *Big Data \& Society*. https://doi.org/10.1177/2053951717738104



* Maldonado, O.J. 2021. Connective data: Markov chain models and the datafication of cervical cancer and HPV vaccination in Colombia. *Tapuya: Latin American Science, Technology and Society*. https://doi.org/10.1080/25729861.2021.1874744 .



* Cellard, L. (2022). Algorithms as figures: Towards a post-digital ethnography of algorithmic contexts. *New Media and Society*, 24(4), 982–1000. https://doi.org/10.1177/14614448221079032

