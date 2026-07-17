# 3\. Redes sociales 1

13/08/26



##### Descripción de la sesión:



Puesto que esta sesión no contiene lecturas complementarias ni una presentación por parte del docente, nos enfocaremos en la discusión y el taller.



El taller consiste en hacer nuestra propia base de datos para poderla visualizar en Gephi durante la siguiente clase. Estos datos podrán ser recolectados de dos formas: una manual y la otra automatizada o asistida por Hyphe.



##### Tutorial de construcción de *web crawling* "a mano"



Durante la última década el *surfeo* en Internet ha sido reemplazado por el *scrolling*. Esto está íntimamente relacionado a la captura de nuestro tiempo por parte de las grandes plataformas, expresado en la lectura de Greene como "terratenientes" (*landlords*) del Internet. Por ello, este ejercicio *low-tech* nos ayudará a tener en cuenta distintas aproximaciones al Internet a través del *surfeo* de sitios web.



1. Localiza un sitio web (de preferencia no redes sociales) que tenga distintos enlaces fuera de su sitio (*outbound*).
2. Una vez elijas el punto de inicio (puede ser en una página de Wikipedia) haz *click* derecho en algún elemento y debería aparecer en el menú desplegable "Inspeccionar".
3. Una vez hemos entrado en la **consola**, vemos que en la parte superior tiene unos menús en fila o *ribbon* y seleccionamos el título "*Network*".
4. Una vez dentro de este título podemos dar *click* en cualquiera de los elementos que hemos pedido al servidor que aparecen en una lista (se hace más fácil dejar de grabar las solicitudes con un pequeño botón rojo en la parte superior).
5. Una vez estamos allí, veremos que se despliega una nueva columna a la derecha que dice "*Remote Address*" seguido de una dirección IP y su respectivo puerto. Ejemplo: 140.82.114.5:443
6. Copiamos sólo los números antes de los dos puntos, pues esta es la IP del servidor en donde está alojada la página web que estamos inspeccionando.
7. Registramos esa IP en una tabla de Excel o Google Sheets con el nombre del sitio y su respectivo URL o *link*.
8. Hacemos *click* en un *link* presente en la página que nos lleve a otro sitio (en el caso de Wikipedia sería en la sección de "Enlaces externos"
9. Repetimos otra vez hasta tener unas 15-20 páginas web


\*Si no encontramos un hilo conductor en una página web (esto quiere decir que no tenga enlaces hacia afuera de ella) podemos volver a Wikipedia para iniciar nuevamente, teniendo en cuenta cuándo llegamos a este callejón sin salida y anotando el nuevo punto de partida (ojalá relacionado con la búsqueda inicial). Podemos registrarlo de una manera que nos sea útil en la tabla que estamos construyendo.



\*\*Si hay dos sitios web conectados a un tercero también lo registramos en nuestra base.



¿Para qué nos sirven las IP en este sentido? Para poder visibilizar la heterogeneidad y multiplicidad de Internet, en este caso en el ámbito de la World Wide Web. El Internet no es un lugar único hacia donde nos conectamos, es una red global que sigue un tipo de estándares técnicos para ser intertextual. Debido a ello, en vez de colapsar dicha multiplicidad en el concepto único, podemos materializar las localizaciones del viaje de *surfeo* *web* que acabamos de hacer. Para ello, haremos lo siguiente:



1. Ingresamos a alguno de los siguientes servicios: [whatismyipadress](https://whatismyipaddress.com/ip-lookup), [iplocation.net](https://www.iplocation.net/), [iplocation.io](https://iplocation.io/) o [NordVPN](https://nordvpn.com/es-mx/ip-lookup/?srsltid=AfmBOoo7pP7ocbtIM0iDihNFLhyWqxbh_xyTr8iSuB6OB2Jyj1KGPRwv).
2. Buscamos las IP que tenemos recolectadas una a una y registramos la ubicación en nuestra tabla teniendo en cuenta los países (de querer seguir el ejercicio puede valer la pena registrar las ciudades)



De esta forma tendremos una base de datos que posteriormente podemos convertir a un formato que acepte Gephi en la siguiente sesión.



##### *Web crawling* con el demo de Hyphe



Esta herramienta fue desarrollada por el MediaLab de SciencePo Paris en 2017 y (al menos en su estado demo) es muy sencilla para hacer *web crawling*. Simplemente debemos entrar al sitio [Hyphe demo](https://hyphe.medialab.sciences-po.fr/demo) y seguir las instrucciones. Debemos tener en cuenta la página en donde queramos comenzar nuestro crawl que idealmente no sea la misma del ejercicio anterior. No obstante, si queremos comparar nuestros esfuerzos "a mano" contra la herramienta demo podemos hacerlo, teniendo en cuenta que tendremos dos bases de datos muy similares para la siguiente sesión.



Una vez hayamos decidido nuestro punto de inicio lo estableceremos como una "entidad web" (*web entity*) y comenzaremos a hacer el *crawling* de este primer sitio. Una vez haya terminado esta primera iteración, en la opción "*prospect"* podemos ver las otras "entidades web" que ha encontrado en el *crawl* y podemos ingresarlas a nuestro crawl, permanecer indecisos o descartarlas y hacer un segundo *crawl* sobre los sitios que dejamos entrar en nuestra muestra.



Posteriormente, en la pestaña "*Network*" podemos ver un pequeño grafo de lo recolectado y descargarlo como .gefx (archivo listo para Gephi).



Se adjunta al folder del repositorio de GitHub para esta sesión un pequeño test que hice en menos de 15 minutos.



Documentación del proyecto: [Repo GitHub de Hyphe](https://github.com/medialab/hyphe)



##### ¿Qué productos salen de esta sesión?



El producto de esta sesión serán (idealmente) dos bases de datos con las que trabajar en la próxima sesión: una construida "a mano" y la otra con el demo de Hyphe.



###### Lecturas obligatorias



* Bonacich, P. and Lu, P. (2012). Introduction to Mathematical Sociology. Princeton: Princeton University Press. Chapter 5. Networks and Graphs.



* Salganik, M. J. (2017/2018). Observing behavior. In Bit by bit: Social research in the digital age (Chapter 3). Princeton University Press. https://www.bitbybitbook.com/en/1st-ed/asking-questions/



* Mol, A., \& Law, J. (1994). Regions, Networks and Fluids: Anaemia and Social Topology. In Social Studies of Science (Vol. 24, Issue 4). https://doi.org/10.1177/030631279402400402

