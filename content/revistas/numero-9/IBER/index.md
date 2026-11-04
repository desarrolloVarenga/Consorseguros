---
title: "El modelo IBER y su aplicación al estudio de inundaciones"
category: "Análisis"
pdf_download: "/pdf/num22/editorial.pdf"
sidebar_image: "/images/numero-9/foto_portada09_IBER.png"
sidebar_text: "Iber dispone de opciones para la introducción de los diferentes tipos de condiciones iniciales y de condiciones de contorno de entrada y salida de caudales. Dispone de herramientas para la asignación automática de la rugosidad del cauce, y además incorpora opciones de configuración de condiciones de contorno internas, para definir vertederos, compuertas, puentes, alcantarillas o tramos de cauce cubiertos. El postproceso consiste en la visualización de los resultados de modo que sean fácilmente interpretables, para lo cual pueden hacerse representaciones por colores, curvas de nivel, etiquetas, vectores, gráficas, animaciones, etc."
weight: 4
image: "/images/numero-9/foto_portada09_IBER.png"
summary: "En los episodios de avenida las variables más importantes para evaluar los riesgos de inundación son la velocidad y el nivel alcanzado por el agua, así como el tiempo de permanencia. Existen diferentes formas de evaluar el riesgo asociado a un evento de avenida en función de estos parámetros."
authors:
    - name: "David López Gómez"
      institution: "Dr. Ingeniero de Caminos, Canales y Puertos. Centro de Estudios Hidrográficos. CEDEX"
    - name: "Juan J. Rebollo Cillán"
      institution: "Ingeniero de Caminos, Canales y Puertos. Centro de Estudios Hidrográficos. CEDEX"
---
Durante las crecidas de los ríos el caudal circulante por su cauce aumenta llegando a desbordar el cauce principal y ocupando las llanuras de inundación. Mientras el flujo del agua queda confinado en el cauce principal, los modelos unidimensionales son capaces de describir suficientemente bien el movimiento del agua, es decir, permiten conocer el calado y la velocidad del agua a lo largo del eje del río; sin embargo, una vez que las aguas ocupan las llanuras de inundación, el flujo se convierte en bidimensional, es decir, que la dirección del agua ya no sigue el eje del cauce principal, sino que puede tomar cualquier dirección en función de la topografía y obstáculos que encuentren los caudales desbordados, por tanto, los eventos de inundación deben analizarse con modelos bidimensionales.

{{< figura src="/images/numero-9/IBER_Guadalhorce1.png" caption="" source="" >}}

El modelo Iber, que toma el nombre de la raíz latina del río Ebro y que a su vez da nombre a la península ibérica, ha sido desarrollado por instituciones españolas repartidas por diferentes puntos de nuestra geografía. En concreto, la Universidad Politécnica de Cataluña, la Universidad de A Coruña, el Centro Internacional de Métodos Numéricos para la Ingeniería (CIMNE) y el Centro de Estudios y Experimentación de Obras Públicas (CEDEX), con la financiación de la Dirección General del Agua. 

Una de las ventajas del modelo Iber es que es un software de libre descarga, lo que ha facilitado su empleo de forma habitual tanto por empresas de consultoría como por Administraciones públicas, facilitando la interacción entre los diferentes agentes. También en el mundo académico este software ha sido ampliamente aceptado, con gran número de usuarios en Europa e Iberoamérica. A esto ha contribuido la posibilidad de configurar el idioma de Iber en castellano o en inglés.

Los ficheros ejecutables de instalación se pueden descargar en la página web www.iberaula.es (se abre en una ventana nueva), donde además se puede encontrar material didáctico con manuales, ejemplos y vídeos tutoriales que pueden ser muy útiles para el aprendizaje. Igualmente existe un foro bastante activo dónde consultar dudas y hacer aportaciones. También se puede encontrar información sobre cursos presenciales y online. 

El motor numérico de Iber es el código FORTRAN F90, que resuelve las ecuaciones de Navier Stokes 2D integradas en profundidad para aguas poco profundas, conocidas como de Saint Venant o ecuaciones en aguas someras 2D, con ecuaciones de cierre turbulento y en régimen variable. Para resolver estas ecuaciones se emplea el método numérico de los volúmenes finitos. Iber emplea un esquema numérico explícito tipo “upwind”. De entre los diferentes esquemas numéricos existentes, este es el que mejor se adapta a los flujos bidimensionales en lámina libre, pues sin artificios de cálculo es capaz de resolver problemas de frentes de onda y cambios de régimen.

Iber dispone de herramientas que permiten generar modelos y analizar resultados en la misma aplicación informática. Podríamos decir que Iber se encuentra encapsulado en el entorno gráfico de GiD (www.gidhome.com (se abre en una ventana nueva)), que proporciona las utilidades de preproceso y postproceso. GiD está desarrollado para la definición y preparación de los datos que constituyen una simulación numérica, así como para la visualización de sus resultados. La creación de los datos implica la definición de la geometría del problema y la asignación a esa geometría de la información necesaria para generar los ficheros internos que necesita el motor de cálculo de Iber para ejecutarse. GiD dispone de un motor de CAD que permite generar geometrías nuevas o importarlas de otros sistemas de CAD para su posterior ajuste. El programa permite además generar una malla y transferirle los datos asociados a la geometría.

Todos los cálculos se realizan sobre una malla tridimensional que reproduce la geometría del cauce. Los elementos de la malla sirven para definir los volúmenes finitos sobre los que se realiza el cálculo. Iber puede calcular sobre elementos de malla estructurada y no estructurada, de forma triangular o de cuadriláteros.

{{< figura src="/images/numero-9/IBER_Mogon.png" caption="" source="" >}}

Iber dispone de opciones para la introducción de los diferentes tipos de condiciones iniciales y de condiciones de contorno de entrada y salida de caudales. Dispone de herramientas para la asignación automática de la rugosidad del cauce, y además incorpora opciones de configuración de condiciones de contorno internas, para definir vertederos, compuertas, puentes, alcantarillas o tramos de cauce cubiertos.

El postproceso consiste en la visualización de los resultados de modo que sean fácilmente interpretables, para lo cual pueden hacerse representaciones por colores, curvas de nivel, etiquetas, vectores, gráficas, animaciones, etc.

En los episodios de avenida las variables más importantes para evaluar los riesgos de inundación son la velocidad y el nivel alcanzado por el agua, así como el tiempo de permanencia. Existen diferentes formas de evaluar el riesgo asociado a un evento de avenida en función de estos parámetros. Iber permite zonificar el riesgo de inundación de acuerdo con la reglamentación nacional española, la reglamentación autonómica catalana o cualquier otra que se desee implementar con la opción de clasificación personalizada. Además, Iber dispone de utilidades que permiten generar mapas raster con estos resultados que pueden ser exportados a sistemas de información geográfica; esto permite cruzar los mapas de riesgos con los de usos de suelo para poder evaluar los daños generados por una inundación, lo cual proporciona una herramienta para realizar una evaluación económica de los daños.

Aunque en un proceso de inundaciones la hidrodinámica ocupa un papel central, existen otros fenómenos que afectan al flujo en los cauces, como el transporte de sedimentos o el arrastre de troncos.  Iber dispone de diferentes módulos que permiten abordar este tipo de estudios. El módulo de transporte de sedimentos aborda dos tipos de fenómenos: por un lado, el arrastre de material de fondo, con arenas y gravas, que tiene gran influencia en la geometría del lecho del cauce principal; por otro, el transporte en suspensión, que se enfoca al movimiento del material fino (arcillas y limos) que se moviliza también en las llanuras de inundación. Iber dispone de diferentes formulaciones que permiten analizar la evolución del lecho de ríos y embalses.

Recientemente se ha incorporado un nuevo módulo de lluvias que permite realizar estudios de precipitación-escorrentía en cuencas, de forma que, partiendo de un escenario de lluvias, sea posible calcular qué cantidad de agua llega a los cauces para posteriormente realizar los estudios de inundabilidad. 

La participación de universidades en el proyecto Iber proporciona gran dinamismo, pues permite incorporar nuevos desarrollos procedentes de proyectos de investigación o tesis doctorales, que mejoran y aumentan las capacidades de cálculo y los campos de aplicación de este modelo. 

Aunque el código numérico de Iber se encuentra optimizado, el empleo de algunos de los módulos como el de transporte de sedimentos o el de lluvias suponen tiempos de ejecución muy elevados. En la actualidad se está trabajando en el desarrollo de una versión del código para supercomputación basada en tarjetas gráficas. Esto permitirá reducir considerablemente los tiempos cálculo o abordar estudios de mayores dimensiones. 

Entre los módulos en vía de desarrollo, pronto verá la luz el módulo de hidrología urbana que permitirá realizar simulaciones en las que se podrán incorporar las redes de alcantarillado que permitirán simular procesos de puesta en carga en dichas conducciones y el flujo de escorrentía superficial.  