# Informe-Bioinformática-III
Luciano Frez

# **Parte I: El artículo genoma**

*Ve a la base de datos GOLD y busca un genoma eucarionte de interés.*

**¿Cuántos genomas han sido depositados en GOLD? ¿Son los mismos de GENBANK?**

	Entre projectos completados e incompletados da una suma de 64754 projectos totales (Complete Projects 11.598 y Incomplete Projects 53.156, respectivamente). GENBANK posee 80.576 genomas

**¿Cuál es la distribución de procariontes y eucariontes secuenciados?**

	80.576 procariontes y 18.241 eucariontes.(2)

**¿Qué es el N50, L50, NG50?**
 
 **N50:** se define como la longitud de secuencia más corta en el 50% del genoma.uede considerarse como el punto de la mitad de la masa de la distribución; El número de bases de todos los contigs más largos que el N50 estará próximo al número de bases de todos los contigs más cortos que el N50.
 
 **L50:** se define como el número más pequeño de contigs cuya suma de longitud produce N50.
 
 **NG50:** El estadístico NG50 es el mismo que N50 excepto que es 50% del tamaño del genoma conocido o estimado que debe ser de longitud NG50 o más larga

**¿Cuál es el propósito de calcular estas estadísticas?**

	Este conjunto de estadiscticas ayudan a tener una referencia a las longitudes dentro de un contig y de esta forma ayudar en el ensamblaje del genoma.

**¿Cuál es el genoma que escogiste? Adjunta la referencia.**
![imagen](https://github.com/MrPiggie/Informe-Bioinform-tica-III/blob/master/genoma.png?raw=true)
Imagen I: Genoma escogido *Canis lupus familiaris boxer*

**¿Cuál es el N50 del genoma que escogiste? ¿Y el NG50?**

![imagen](https://github.com/MrPiggie/Informe-Bioinform-tica-III/blob/master/perro.jpg?raw=true)

**Imagen II:** N50 del perro, tanto para al CanFam 1.0 y el 2.0

**¿Qué tipo de tecnología se uso para secuenciar el genoma que escogiste?**
	
	se uso ARACHNE2 +, PatternHunter, BLASTZ/MULTIZ, RepeatMasker, DateRepeats. 

**¿Qué organismo escogiste, cuántos cromosomas tiene tu organismo y cuál es su tamaño?**
	
	Canis lupus familiaris boxer. tiene 39 cromosomas contando el sexual y el tamaño es de 2254.63 Mb.

# **Parte II: Predicción de genes**

**¿Cuántos ORF o genes encontró ORFfinder?**

	ORFfinder encontró 7 ORF.

**Imagen II:**

**¿Cuántos ORF o genes encontró Glimmer?**

	Glimmer encontro 10 ORC.

**¿Alguno de los genes predichos por estas herramientas coinciden?**
	
	coinciden con un gen que posee 441 nucleotidos.
 
 **¿En qué hebra están codificados?**
	
		El gen que coincide en ambas herremientas, ORFfinder muestra que esta en la hebra negativa, pero en GLIMMER aparece que es positiva.

**¿Qué tipo de programa es GLIMMER? ¿Ab initio o por homología?**

	Glimmer es un sistema para encontrar genes en el ADN microbiano, especialmente los genomas de bacterias, arqueas y virus. Utiliza modelos de Markov interpolados para identificar las regiones de codificación y distinguirlos del ADN no codificante, osea, funciona por homologias.

*Describe los resultados encontrados con respecto a los genes que encontraste con GLIMMER y ORFfinder*

Con respecto a los genes entregados por ORFfinder, al usar el BLAST se encontraron 2 genes que no encontro semejanza significativ con la base de datos. Tambien se encontraron genes que poseían un gran puntaje de aliniamiento como bajos puntajes de alineamiento. En el caso de GLIMMER los 10 genes que se analizaron tuvieron una semejanza en la base de datos y el puntaje de alineamiento, en cada gen, fue bastante alta en comparacion a los resultados entregados por ORFfinder.
