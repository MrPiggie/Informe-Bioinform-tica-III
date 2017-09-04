# Informe-Bioinformática-III
Luciano Frez

# **Parte I: El artículo genoma**

*Ve a la base de datos GOLD y busca un genoma eucarionte de interés.*

**¿Cuántos genomas han sido depositados en GOLD? ¿Son los mismos de GENBANK?**

	Hay un total de 64.754 proyectos de genomas depositados en GOLD, de los cuales 11.598 son de proyectos de genomas completos y 53.156 son incompletos(la mayor proporción de estos es porqué siempre se están actualizando. Se descubren nuevos datos).En el caso de GENBANK, la cantidad de genomas depositados es de 80.576.
	

**¿Cuál es la distribución de procariontes y eucariontes secuenciados?**

	La distribución de procariontes y eucariontes secuenciados es de 80.576(procariontes)/18.241(eucariontes). 

**¿Qué es el N50, L50, NG50?**
 
 **N50:** Se define como la longitud de secuencia más corta en el 50% del genoma.uede considerarse como el punto de la mitad de la masa de la distribución; El número de bases de todos los contigs más largos que el N50 estará próximo al número de bases de todos los contigs más cortos que el N50.
 
 **L50:** Se define como el número más pequeño de contigs cuya suma de longitud produce N50.
 
 **NG50:** El estadístico NG50 es el mismo que N50 excepto que es 50% del tamaño del genoma conocido o estimado que debe ser de longitud NG50 o más larga

**¿Cuál es el propósito de calcular estas estadísticas?**

	El propósito de calcular estas estadísticas es para tener una mejor idea del largo de los reads o contig(dependiendo del largo del genoma o fragmento que se quiera ensamblar) ara así generar el ensamblaje del genoma deseado de mejor manera.

**¿Cuál es el genoma que escogiste? Adjunta la referencia.**
![imagen](https://github.com/MrPiggie/Informe-Bioinform-tica-III/blob/master/genoma.png?raw=true)
**Imagen I:** Genoma escogido *Canis lupus familiaris boxer*

**¿Cuál es el N50 del genoma que escogiste? ¿Y el NG50?**

![imagen](https://github.com/MrPiggie/Informe-Bioinform-tica-III/blob/master/perro.jpg?raw=true)

**Imagen II:** N50 del perro, tanto para al CanFam 1.0 y el 2.0

**¿Qué tipo de tecnología se uso para secuenciar el genoma que escogiste?**
	
	La tecnología que se usopara secuenciar el genoma fue: ARACHNE2 +.(1)

**¿Qué organismo escogiste, cuántos cromosomas tiene tu organismo y cuál es su tamaño?**
	
	El organismo que escogí fue el *Canis lupus familiaris boxer*, el cual tiene 39 cromosomas(contando el sexual) y el tamaño del genoma corresponde a 2254.63 Mb(Mega bases).

# **Parte II: Predicción de genes**

**¿Cuántos ORF o genes encontró ORFfinder?**

	ORFfinder encontró 7 ORF o genes.

![imagen](https://github.com/MrPiggie/Informe-Bioinform-tica-III/blob/master/orf%20encontrados.png?raw=true)
**Imagen III:** ORF o genes encontrados por el programa *ORFfinder*

**¿Cuántos ORF o genes encontró Glimmer?**

	Glimmer encontro 10 ORF o genes.

**¿Alguno de los genes predichos por estas herramientas coinciden?**
	
	Coinciden en un gen que posee 441 nucleótidos.
 
 **¿En qué hebra están codificados?**
	
		El gen en común que predijeron ambas herramientas dice que, en el caso de ORFfinder, el gen se encuentra en la hebra negativa. Por el contrario que en GLIMMER, el cual aparece en la hebra positiva.

**¿Qué tipo de programa es GLIMMER? ¿Ab initio o por homología?**

	Glimmer es un sistema para encontrar genes en el ADN microbiano, especialmente los genomas de bacterias, arqueas y virus. Utiliza modelos de Markov interpolados para identificar las regiones de codificación y distinguirlos del ADN no codificante, osea, funciona por homologias.(2) 

*Describe los resultados encontrados con respecto a los genes que encontraste con GLIMMER y ORFfinder*

	Los resultados entregados con respecto a semejanzas encontradas en la base de datos, tanto para ORFfinder y GLIMMER muestran qué: al usar BLAST(ORFfinder)el programa no encontró semejanza significativa para 2 de los genes analizados; en el caso de GLIMMER para los 10 genes analizados se le encontró una semejanza . En referencia a los puntajes de alinemamientos obtenidos(ORFfinder), habían dos grupos, unos con un muy alto puntaje y otros que no **(ver Imagen III)** , para GLIMMER, el puntaje otorgado por este programa para cada gen fue notoriamente más alta en comparacion a los entregados por ORFfinder.
	
	
# **Bibliografía:**
(1) https://www.nature.com/nature/journal/v438/n7069/full/nature04338.html#Methods 01/09/2017 22:03

(2) https://ccb.jhu.edu/software/glimmer/ 04/09/2017 12:37

