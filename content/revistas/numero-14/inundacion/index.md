---
title: "Análisis de los daños por inundación en España a nivel municipal"
category: "Análisis"
pdf_download: "/pdf/num22/editorial.pdf"
sidebar_image: "/images/numero-14/foto_portada14_inundacion.png"
sidebar_text: "En este trabajo se presenta una herramienta, un visor, que permite visualizar las indemnizaciones por inundación abonadas por el CCS –sin considerar en este caso la inundación costera o embate de mar–, por municipio, en el periodo de los últimos 15 años comprendidos entre 2006 y 2020. La información que contiene este visor, que aprovecha el potencial del caudal de datos de indemnizaciones por inundación que posee el Consorcio de Compensación de Seguros se pone aquí a disposición de todos los interesados. El mayor valor de estos datos y de este visor es, sin duda, facilitar la toma de conciencia sobre el riesgo de inundación y servir de indicador para la adopción de medidas de reducción del riesgo por las administraciones competentes y por los propios asegurados. "
weight: 2
image: "/images/numero-14/foto_portada14_inundacion.png"
summary: "En este trabajo se presenta una herramienta, un visor, que permite visualizar las indemnizaciones por inundación abonadas por el CCS -sin considerar en este caso la inundación costera o embate de mar-, por municipio, en el periodo de los últimos 15 años comprendidos entre 2006 y 2020."
authors:
    - name: "Francisco Espejo Gil"
      institution: "Subdirector de Estudios y Relaciones Internacionales"
    - name: "Pablo López Vilares"
      institution: "Responsable de área, Subdirección de Tasaciones"
    - name: "Angélica Guerrero López"
      institution: "Subdirección de Tasaciones"
    - name: "Bin Pu "
      institution: "Subdirección de Tasaciones"
    - name: "Javier Rosa Corral"
      institution: "Subdirección de Tasaciones"
    - institution: "Consorcio de Compensación de Seguros"
      
---

## Introducción
En el anterior número de la revista se presentó una representación del riesgo de inundación en España a partir de los datos del seguro de riesgos extraordinarios. Ese trabajo tenía una resolución provincial y se hacían una serie de suposiciones, como la extrapolación de los datos de daños al porcentaje de viviendas no aseguradas, con la finalidad de tener una mejor representación del nivel de riesgo.

En ese estudio se veían una serie de características espaciales que favorecían que se produjesen más daños: proximidad al mar o a grandes colectores fluviales, conjuntamente con una exposición elevada. Recordamos aquí que las indemnizaciones por inundación -incluido el embate de mar en la costa, según la definición de inundación recogida en el artículo 2 del Reglamento de RREE- suponen el 69 % de la totalidad de las del seguro de riesgos extraordinarios durante los últimos 25 años. La importancia de este hecho y la visualización de los daños a nivel provincial hizo que nos planteásemos de inmediato buscar un medio para representar el riesgo con un mayor nivel de granularidad, y es por ello que en este trabajo se presenta una herramienta, un visor, que permite visualizar las indemnizaciones por inundación abonadas por el CCS –sin considerar en este caso la inundación costera o embate de mar–, por municipio, en el periodo de los últimos 15 años comprendidos entre 2006 y 2020 (Figura 1). Este aumento de la resolución de las 50 provincias más dos ciudades autónomas a los 8.131 municipios de España supone multiplicar la resolución de la información por un factor de más de 150, y de aquí la necesidad de utilizar un visor para poder sacar todo el partido a tal caudal de información. A diferencia del anterior trabajo, aquí no se realizarán suposiciones ni extrapolaciones, sino que se representarán los datos reales, con los todos los valores económicos actualizados a 31 de diciembre de 2020.

Aunque el seguro de riesgos extraordinarios cubre también los daños en las personas y la pérdida de beneficios, la baja proporción de estos daños con respecto al total indemnizado -el 97 % de las indemnizaciones son a daños en los bienes-, junto con el hecho de que, en el caso de los daños personales las indemnizaciones no dependen de criterios objetivos sino de la cantidad establecida como valor asegurado por la persona en cuestión, hará que nos restrinjamos en este estudio, que pretende hacer una radiografía de los daños indemnizados por el seguro por causa de inundación en España, a los daños sobre los bienes.

## Metodología
El visor se ha realizado sobre la plataforma ArcGis y se han realizado tanto mapas que reflejan el riesgo globalmente –el montante total de las indemnizaciones-, como otros que intentan reflejar mejor la peligrosidad –resultado de dividir ese montante entre alguno de estos elementos indicadores de la exposición–:
 
* Población municipal. Fuente: Instituto Nacional de Estadística (INE).
* Parque municipal de viviendas. Fuente: censos de población y viviendas 2011 (INE).
* Parque municipal de vehículos. Fuente: Dirección General de Tráfico (DGT).
* Número de empresas por municipios. Fuente: INE.
* Valor catastral de construcción agregado para cada término municipal. Fuente: elaboración propia a partir de la información estadística publicada por la Dirección General del Catastro (Ministerio de Asuntos Económicos y Transformación Digital) y de la información facilitada por los Catastros de Bizkaia y Gipuzkoa. A fecha de redacción del artículo no se dispone de los valores catastrales de Álava y Navarra.

Algunos mapas se refieren a la totalidad de los daños sobre todos los bienes asegurados, pero se han elaborado además mapas específicos para las siguientes clases de riesgo: 
 
* Viviendas.
* Comercios, industrias y riesgos similares.
* Infraestructuras.
* Vehículos automóviles.

Con la finalidad de facilitar la comprensión y el análisis de la cartografía resultante, se han añadido al visor las siguientes capas de información geográfica:
 
* Mapa base de España. Fuente: IGN.
* Límites de las Comunidades autónomas. Fuente: IGN.
* Límites provinciales. Fuente: IGN.
* Principales cursos fluviales (aquellos cuya superficie de cuenca es superior a 500 km2). Fuente: Ministerio para la Transición * Ecológica y el Reto Demográfico.
* Cuencas hidrográficas de los principales cursos fluviales. Fuente: Ministerio para la Transición Ecológica y el Reto Demográfico.
* Zonas inundables con periodo de retorno de 500 años. Fuente: Sistema Nacional de Cartografía de Zonas Inundables (Ministerio para la Transición Ecológica y el Reto Demográfico).

La Tabla 1 resume los mapas que se pueden visualizar en el visor y sus características principales.

{{< tabla caption="Relación de mapas de indemnizaciones por tipo de bien, riesgo y unidad de medida." >}}
| Nº mapa | Descripción | Unidades | Observaciones |
| :---: | :--- | :---: | :--- |
| 1 | Todos los bienes. Indemnización total por municipio. | € | |
| 2 | Todos los bienes. Indemnización media anual por municipio. | € | |
| 3 | Todos los bienes. Indemnización media anual por municipio y habitante | € | |
| 4 | Todos los bienes. Indemnización media anual por municipio y valor catastral de construcción | Tanto por millón | Euros indemnizados por cada millón de euros de valor catastral de construcción expuesto. |
| 5 | Inundación. Viviendas: Indemnización media anual por municipio | € | |
| 6 | Inundación. Viviendas: Indemnización media anual por municipio y habitante | € | |
| 7 | Inundación. Viviendas: Indemnización media anual por vivienda | € | Euros indemnizados por municipio y vivienda expuesta. |
| 8 | Inundación. Viviendas: Indemnización media anual por municipio y valor catastral de construcción | Tanto por millón | Euros indemnizados en viviendas por cada millón de euros de valor catastral de construcción de viviendas expuestas. |
| 9 | Inundación. Vehículos automóviles: Indemnización media anual por municipio | € | |
| 10 | Inundación. Vehículos automóviles: Indemnización media anual por municipio y vehículo | € | Euros indemnizados por municipio y vehículo expuesto. |
| 11 | Inundación. Industrias, comercios y riesgos similares: Indemnización media anual por municipio | € | |
| 12 | Inundación. Industrias, comercios y riesgos similares: Indemnización media anual por municipio y empresa | € | |
| 13 | Inundación. Industrias, comercios y riesgos similares: indemnización media anual por municipio y valor catastral de construcción | Tanto por millón | Euros indemnizados en industrias, comercios y riesgos similares por cada millón de euros de valor catastral de construcción de industrias, comercios y riesgos similares expuestos. |
| 14 | Inundación. Infraestructuras: Indemnización media anual por municipio | € | |
{{< /tabla >}}

## Resultados
Realizar aquí una descripción exhaustiva de todos los posibles resultados extraíbles de esta información excedería con mucho la extensión y el alcance de este artículo, por lo que ceñiremos nuestros comentarios a una selección limitada de mapas y a alguna de sus características.

La Figura 2 muestra la media anual de indemnizaciones del seguro de riesgos extraordinarios por inundación y municipio a lo largo del periodo de estudio. Los diez municipios que reciben una media anual mayor de indemnizaciones por inundación figuran en la Tabla 2. Conviene en este punto recordar que estos son los datos totales indemnizados por municipio, y esas indemnizaciones son sobre los bienes asegurados. Es decir, aquí no se representan todos los daños producidos por inundación, sino únicamente los asegurados e indemnizados, por tanto, por el CCS. 

A nivel total, se estima que el seguro de riesgos extraordinarios cubre del orden del 50-60 % del total de los daños, siendo las infraestructuras y otros bienes de titularidad pública la principal fuente de esa brecha de cobertura, puesto que la administración se autoasegura en buena medida. Esta es la razón por la que no se harán comentarios en este trabajo de la información, que sí se proporciona en el visor, sobre daños por inundación en las infraestructuras, puesto que son fuertemente dependientes de la política de asegurarlas o no de la administración titular de la misma. Otro factor relevante es el distinto nivel de aseguramiento entre unas regiones y otras, así como la variación entre el medio urbano y el medio rural. No obstante, hechas estas apreciaciones, se observan unas características espaciales coherentes.

{{< figura src="/images/numero-14/inundacion_municipio02%20grande.png" caption="Figura 2. Indemnización media anual del seguro de riesgos extraordinarios por causa de inundación, por municipio (2006-2020)." source="" >}}

{{< tabla caption="Ranking de municipios según la media anual de indemnizaciones por daños (€/año)." >}}
| Nº | Municipio | Cuenca | Provincia | Daños (€/año) |
| :---: | :--- | :--- | :--- | :---: |
| 1 | Orihuela | Segura | Alicante | 7.098.641,51 |
| 2 | Los Alcázares | Segura | Murcia | 5.350.222,91 |
| 3 | Murcia | Segura | Murcia | 4.182.169,95 |
| 4 | Vera | Mediterráneas de Andalucía | Almería | 4.128.396,24 |
| 5 | Málaga | Mediterráneas de Andalucía | Málaga | 4.095.421,18 |
| 6 | Marbella | Mediterráneas de Andalucía | Málaga | 3.201.282,98 |
| 7 | Tarragona | Internas de Cataluña | Tarragona | 2.861.505,74 |
| 8 | San Javier | Segura | Murcia | 2.744.628,13 |
| 9 | Lorca | Segura | Murcia | 2.645.056,48 |
| 10 | Donostia/San Sebastián | Internas del País Vasco | Gipuzkoa | 2.522.306,66 |
{{< /tabla >}}

De nuevo es el cruce entre peligrosidad y exposición el que determina la mayor cantidad de indemnizaciones. Así, juegan un papel muy relevante en esta mayor cantidad de daños la coincidencia entre orografía y litoral, en particular en el litoral mediterráneo andaluz, murciano y de la Comunidad Valenciana y sur de Cataluña, así como el del Golfo de Vizcaya, junto con la exposición. Los grandes municipios cerca de grandes cursos fluviales, casos de Zaragoza o Córdoba, por ejemplo, también reflejan este cruce entre peligrosidad y exposición. El propio peso de la exposición en las grandes áreas metropolitanas de Madrid y Barcelona también hace que acumulen más daños. Además de en la Figura 2 y, por supuesto, en el propio visor, el análisis de los municipios con mayores daños por inundación según cuencas, que figuran en la Tabla 3, arroja más luz sobre esta cuestión.

Resulta evidente que las cuencas que presentan más daños son la del Segura -cinco de los diez municipios que, a nivel nacional, sufren más daños, pertenecen a esta cuenca-, las cuencas mediterráneas de Andalucía –tres de cuyos municipios también están entre los diez primeros de España- y otras, como la del Júcar, o las internas de Cataluña y País Vasco. Las grandes cuencas, como las del Ebro o del Guadalquivir también presentan municipios con grandes daños, resultado de la gran exposición o de afluentes del curso principal que producen inundaciones importantes y que responden más a procesos más parecidos a los que causan inundaciones en el litoral que a los de inundación por desbordamiento de un gran curso fluvial: casos de Tafalla, Écija, Lucena o Jaén.

{{< figura src="/images/numero-14/inundacion_municipio_tabla03.png" caption="Tabla 3. Los cinco municipios con mayor media anual de indemnizaciones por inundación, según cuencas, en el periodo 2006-2020." source="" >}}

La ausencia de relieves importantes junto a grandes núcleos urbanos y la baja densidad de población hacen que otras grandes cuencas, como las del Duero, Tajo (con la excepción de Madrid y su área metropolitana, resultado de la gran exposición), Guadiana o Miño-Sil, presenten relativamente daños menores. En cuanto a la costa gallega y cantábrica (con la excepción de la costa vasca), la menor torrencialidad de las precipitaciones –pueden alcanzar grandes acumulaciones, pero con menor intensidad que en el litoral mediterráneo-, junto con un menor nivel de urbanización, o una urbanización más dispersa, hacen que, salvo en los grandes núcleos de población de Galicia y Asturias, no lleguen a producirse tantos daños como en otras zonas litorales. 

Baleares y Canarias responden, lógicamente, a dinámicas de inundación análogas a las de otras zonas litorales altamente urbanizadas, donde se cruza la torrencialidad de las precipitaciones con el relieve, que genera cursos con poco tiempo de respuesta y corrientes con mucha energía, con una exposición alta.

La Figura 3 representa estas mismas indemnizaciones medias por municipio y año, divididas entre el número de habitantes, con la finalidad de relativizar el efecto de la exposición. En este mapa desaparecen los efectos de los grandes núcleos de población y se ven mejor otros, que reflejan mejor el nivel real de peligrosidad. Los municipios que aparecen con mayores daños por habitante suelen obedecer, en general, a dinámicas de inundaciones repentinas que se producen en cauces cortos, con fuertes pendientes y pocos tiempos de acumulación. Además de en las zonas litorales mediterráneas y del Cantábrico Oriental, ya comentadas, estos efectos aparecen en los Pirineos, la Cordillera Cantábrica (especialmente en su cara sur), la Navarra Media y a ambos lados de las cordilleras Costero Catalana y Penibética (en su sector más occidental). En menor medida, lo mismo sucede en Sierra Morena y los Montes de Toledo.

{{< figura src="/images/numero-14/inundacion_municipio03.png" caption="Figura 3. Indemnización media anual del seguro de riesgos extraordinarios por causa de inundación,  por municipio y habitante (2006-2020)." source="" >}}
