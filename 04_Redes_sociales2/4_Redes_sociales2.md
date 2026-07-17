# 4\. Redes sociales 2: Visualización de redes sociales (SNV)

20/08/26



##### Descripción de la sesión:



En esta sesión vamos a convertir los datos que hicimos a mano en dos tablas necesarias para su importación en Gephi. No está de más decir que si traen su computador deben [instalarlo](https://gephi.org/) pues a pesar de que existe una [versión web](https://lite.gephi.org/v1.0.2/) esta no cuenta con todas las funcionalidades.



Para preparar un archivo para Gephi necesitamos de dos archivos separados por comas (.csv) que haremos ya sea en Excel(local u online), LibreOffice, OpenOffice o Google Sheets. .cvs es un formato transversal y se puede lograr con cualquier herramienta de tablas de cálculo.



Cuando iniciamos un grafo en Gephi con tablas de cálculo necesitamos dos tipos de archivos: 'nodes.csv' y 'edges.csv'. El primero debe contener los actantes y el segundo sus conexiones, con la posibilidad de establecer atributos.



Ejemplo:



'nodes.csv'





|id|label|attribute|
|-|-|-|
|1|Wikipedia|Wiki|
|2|Facebook|Social media|
|3|GitHub|Repositorio|
|4|TikTok|Social media|
|...|...|...|



'edges.csv.



|source|target|type|
|-|-|-|
|1|2|Directed|
|4|2|Directed|
|4|1|Directed|
|3|2|Directed|
|...|...|...|



Habiendo hecho nuestras tablas de esta manera, podemos entrar a Gephi y cargarlas como *nodes* (nodos, actores) o *edges* (aristas, relaciones) respectivamente.



En cuanto a la base de datos creada con el demo de Hyphe, la podemos abrir directamente con Gephi, pues viene en un archivo que es leído directamente sin necesidad de las dos tablas de nodos y aristas (.gefx).



Si lo desean, pueden subir sus archivos .gefx al repositorio de GitHub en la carpeta '04\_Redes\_sociales2/' para compartir sus grafos con sus compañeras(os).



##### ¿Qué productos salen de esta sesión?



Diversas imágenes de grafos que dan cuenta de la exploración por parte de las(os) estudiantes de la experimentación con los diversos algoritmos de Gephi.



###### Lecturas obligatorias

* Salganik, M. J. (2017/2018). Observing behavior. In *Bit by bit: Social research in the digital age (Chapter 4)*. Princeton University Press. https://www.bitbybitbook.com/en/1st-ed/running-experiments/



* Milgram, S. (1967). The small world problem. *Psychology Today*, 1:62-67. https://snap.stanford.edu/class/cs224w-readings/milgram67smallworld.pdf



* Paola Tubaro. Disembedded or Deeply Embedded? A Multi-Level Network Analysis of Online Labour Platforms. *Sociology*, 2021, 55 (5), pp.927-944. ff10.1177/0038038520986082ff. ffhal-03127861f https://hal.science/hal-03127861v1/file/Tubaro\_Sociology\_HAL.pdf



###### Lectura complementaria

* Venturini, T., Jacomy, M., \& Pereira, D. (2014). *Visual network analysis* (Working Paper). Sciences Po médialab. https://www.tommasoventurini.it/wp/wp-content/uploads/2014/08/Venturini-Jacomy\_Visual-Network-Analysis\_WorkingPaper.pdf

