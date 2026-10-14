---
title: "Proyecto ICARIA: impactos económicos por inundaciones en el Área Metropolitana de Barcelona"
category: "COLABORACIONES"
image: "/images/numero-24/foto_portada_ICARIA.jpg"
sidebar_image: "/images/numero-24/foto_portada_ICARIA.jpg"
sidebar_text: "El ámbito de estudio comprendió los 36 municipios del AMB, con una superficie aproximada de 636 km². La complejidad territorial del área analizada —que combina zonas densamente urbanizadas, infraestructuras críticas, áreas industriales y sectores costeros especialmente expuestos— obligó a desarrollar un modelo de gran escala y elevado nivel de detalle."
summary: "En las últimas dos décadas, las inundaciones globales han afectado a más de 1.600 millones de personas, generando pérdidas económicas multimillonarias (UNDRR, 2020). Las áreas urbanas son especialmente vulnerables a estos eventos debido a su alta densidad demográfica e infraestructural, lo que propicia fallos en cascada en los servicios esenciales"
pdf_download: "/pdf/num24/ICARIA.pdf"
weight: 3
authors:
  - name: "Àlex de la Cruz Coronas "
    institution: "Ingeniero. Climate Change & Resilience Unit, AQUATEC (AGBAR Group). FLUMEN Research Institute, Universitat Politècnica de Catalunya (UPC-BarcelonaTECH) - Centre Internacional de Mètodes Numèrics a l’Enginyeria (CIMNE)"
  - name: "Beniamino Russo"
    institution: " Profesor. FLUMEN Research Institute, Universitat Politècnica de Catalunya (UPC-BarcelonaTECH) - Centre Internacional de Mètodes Numèrics a l’Enginyeria (CIMNE)"
  - name: "Sofía Pacho Gómez"
    institution: "Técnico. Climate Change & Resilience Unit, AQUATEC (AGBAR Group)"
  - name: "Daniel Yubero Peña"
    institution: "Técnico. Climate Change & Resilience Unit, AQUATEC (AGBAR Group)"
---
## Introducción
En las últimas dos décadas, las inundaciones globales han afectado a más de 1.600 millones de personas, generando pérdidas económicas multimillonarias (UNDRR, 2020). Las áreas urbanas son especialmente vulnerables a estos eventos debido a su alta densidad demográfica e infraestructural, lo que propicia fallos en cascada en los servicios esenciales (Cea & Costabile, 2022; Russo et al., 2023). Esta situación se agrava en las regiones costeras —donde reside cerca del 41 % de la población en España y Europa— debido a la confluencia de inundaciones pluviales, fluviales y marítimas. Estos eventos compuestos, al ocurrir de forma simultánea o sucesiva, amplifican drásticamente los impactos en el territorio (Del-Rosal-Salido et al., 2025; Sanuy et al., 2021). Todo esto implica un cambio de paradigma en abordar la cuestión de las inundaciones pluviales urbanas, como se señala en un artículo reciente de Molina-López et al., 2026.

En este marco, el proyecto Horizon Europe ICARIA (https://www.icaria-project.eu/) tiene como objetivo principal promover prácticas de modelización a nivel de activo para mejorar la resiliencia de infraestructuras críticas frente a eventos multipeligro (Leone et al., 2025).

El proyecto, con una duración de 39 meses (enero de 2023 a marzo de 2026), se ha articulado alrededor de 3 casos de estudio representados por 3 regiones europeas con diferentes características climáticas, morfológicas y socioeconómicas: el Área Metropolitana de Barcelona (AMB, España), la región de Salzburgo (Austria) y la región del sur del mar Egeo (Grecia). Para cada caso, se han desarrollado modelos avanzados para distintos peligros climáticos que han hecho posible la evaluación de sus posibles impactos sobre la población, las infraestructuras críticas y los posibles efectos en cascada que se puedan derivar.

El caso del AMB, con 3,3 millones de habitantes, muchos de los cuales son residentes en zonas costeras, es el de una región especialmente sensible a los riesgos vinculados a la ocurrencia de episodios hidrológicos extremos como los relacionados con eventos extremos de precipitación. La investigación que se presenta en este trabajo evalúa el efecto del cambio climático sobre la precipitación extrema y sobre los impactos económicos derivados de las inundaciones urbanas en toda el AMB. Los escenarios considerados han sido: peligro único (inundaciones pluviales), multipeligro (inundaciones urbanas y de temporal marítimo) y adaptación (considerando diferentes medidas de adaptación).

## METODOLOGÍA

A nivel metodológico, el estudio de impactos socioeconómicos de inundaciones en el AMB se ha basado en el esquema de análisis del riesgo recomendado por instituciones como el IPCC (1) (IPCC, 2023) o el UNDRR (2) (UNDRR, 2015). De acuerdo con este marco metodológico, el riesgo se define como la combinación de tres factores: la peligrosidad, la exposición y la vulnerabilidad. En el caso de las inundaciones urbanas y del análisis de los impactos económicos directos sobre los receptores del riesgo, este marco se ha adaptado tal y como se refleja en la Figura 1: la peligrosidad corresponde a los mapas de inundación que muestran los calados de agua observados durante un evento, la exposición refleja la ubicación de edificios e infraestructuras expuestos, y la vulnerabilidad describe los daños que el agua puede causar sobre los elementos afectados.

Es importante destacar que un paso clave de esta metodología es la adecuación de los valores de los mapas de inundación (peligrosidad) al contexto del estudio. En este sentido, se conoce que los daños económicos causados en edificios se deben a la acumulación de agua en el interior de las propiedades, no a los calados de agua en las calles. Debido a la brevedad de las inundaciones pluviales urbanas, es infrecuente que se llegue a una situación estacionaria donde los calados dentro y fuera de las propiedades se igualen. En consecuencia, es fundamental aplicar algún criterio que permita correlacionar los calados fuera y dentro de los edificios. En este estudio se emplearon los coeficientes de estanqueidad propuestos en Martínez-Gomariz et al. (2021).

{{< figura src="/images/numero-24/ICARIA_figura1.png" caption="Figura 1. Metodología de cuantificación del riesgo de inundación." source="elaboración propia." >}}

### Modelo metropolitano de inundación

Para evaluar las inundaciones pluviales en toda la AMB (636 km²) se desarrolló un modelo hidrodinámico acoplado 1D/2D en Infoworks Ultimate (v2026.2). De acuerdo con el estado del arte en la materia, esta clase de modelos constituye la opción más avanzada y precisa para estudiar el fenómeno de las inundaciones en entornos urbanos. Dada la alta complejidad de los espacios urbanizados, con elementos de pequeña escala que alteran los flujos preferenciales de la escorrentía, y la presencia de sistemas de saneamiento que captan el agua de la lluvia, es imprescindible optar por técnicas de modelización que representen ambos medios.

El ámbito de estudio comprendió los 36 municipios del AMB, con una superficie aproximada de 636 km². La complejidad territorial del área analizada —que combina zonas densamente urbanizadas, infraestructuras críticas, áreas industriales y sectores costeros especialmente expuestos— obligó a desarrollar un modelo de gran escala y elevado nivel de detalle.

La componente bidimensional (2D) del modelo representó la escorrentía superficial mediante un modelo digital del terreno de alta resolución y una malla hidráulica variable adaptada a las características urbanas del territorio. En las zonas más urbanizadas se empleó una discretización especialmente fina para reproducir con precisión las acumulaciones de agua y las rutas preferentes de flujo superficial. En total se alcanzó una malla de 6,8 millones de elementos (de La Cruz-Coronas et al., 2026).

La componente unidimensional (1D) reprodujo el comportamiento hidráulico de la red de saneamiento metropolitana y municipal. El modelo integró más de 4.950 kilómetros de colectores y alrededor de 181.000 nodos hidráulicos, incluyendo estaciones de bombeo, depósitos de retención, válvulas, sifones y otros elementos singulares de regulación. Esta integración permitió representar de forma continua el funcionamiento del drenaje urbano a escala metropolitana, algo poco habitual en estudios regionales de inundación.

Cabe destacar que, a escala global, existen muy pocos modelos de inundación que abarquen un territorio de esta escala con tal nivel de detalle. La Figura 2 muestra un esquema del modelo resultante.

{{< figura src="/images/numero-24/ICARIA_figura2.png" caption="Figura 2. Esquema del modelo 1D/2D desarrollado." source="elaboración propia." >}}

### Escenarios simulados

De acuerdo con los objetivos de ICARIA, a partir del modelo desarrollado, se simularon un total de 3 escenarios de inundación:

* El primer escenario, denominado single-hazard (SH), consideró exclusivamente inundaciones generadas por precipitaciones intensas. Se utilizaron tormentas de diseño asociadas a periodos de retorno de 1, 10, 50, 100 y 500 años, representativas de eventos extremos típicos del clima mediterráneo (Ajuntament de Barcelona, 2019). Estas simulaciones se ejecutaron tanto para condiciones históricas como para tres horizontes futuros de cambio climático (2015–2040, 2041–2070 y 2071–2100), incorporando incrementos de intensidad de lluvia derivados de proyecciones climáticas regionalizadas. En total, este escenario comprendió 20 simulaciones (De La Cruz-Coronas et al., 2026).

* El segundo escenario, denominado multi-hazard (MH), incorporó la interacción simultánea entre precipitaciones extremas y temporales marítimos. Este enfoque permitió analizar el denominado backwater effect, fenómeno especialmente relevante en zonas costeras urbanas, donde los elevados niveles del mar dificultan el desagüe de los colectores y agravan las inundaciones. Para ello, se combinaron eventos de lluvia y nivel marino equivalentes para cada periodo de retorno, manteniendo las mismas proyecciones climáticas utilizadas en el escenario SH. Este planteamiento permitió evaluar el efecto adicional que la componente marina puede generar sobre los daños económicos y la afectación urbana, particularmente en municipios litorales. Al igual que el escenario anterior, se realizaron 20 simulaciones multipeligro.

* Finalmente, el escenario de adaptación (AD) evaluó el potencial de distintas medidas de resiliencia urbana para reducir el riesgo de inundación. Las simulaciones incorporaron soluciones basadas en la naturaleza y sistemas urbanos de drenaje sostenible, como pavimentos permeables, cubiertas verdes y zonas de infiltración (De La Cruz-Coronas et al., 2026). Estas actuaciones se representaron mediante modificaciones hidrológicas e hidráulicas en el modelo, principalmente relacionadas con la reducción de escorrentía superficial y el aumento de la capacidad de retención e infiltración del sistema urbano. El escenario AD reprodujo las mismas condiciones climáticas y combinaciones multipeligro consideradas previamente, permitiendo comparar directamente la eficacia de las medidas de adaptación frente a distintos niveles de severidad. Este bloque incluyó otras 20 simulaciones.

### Métodos de cuantificación del riesgo

En el caso de los impactos económicos sobre edificios se emplearon curvas profundidad-daño, que relacionan el nivel de inundación en el interior de las edificaciones con las pérdidas económicas esperadas según la tipología de uso del suelo. Estas curvas constituyen uno de los elementos más relevantes de la metodología, ya que fueron desarrolladas a partir de información real de siniestros facilitada por el Consorcio de Compensación de Seguros (CCS) y del conocimiento de técnicos especializados en peritaje de daños asociados a inundaciones.

Para ello, el CCS proporcionó una extensa base de datos de expedientes de inundación correspondientes al Área Metropolitana de Barcelona, recopilados entre 2010 y 2022. Dichos datos eran georreferenciados a escala de área censal. Esta información permitió calibrar el modelo de daños y validar los resultados al poder relacionar los daños indemnizados con los calados de agua estimados para cada evento mediante modelización hidráulica. En síntesis, se generaron funciones empíricas de daño adaptadas a las condiciones urbanas y socioeconómicas del ámbito de estudio.

El desarrollo de estas curvas se llevó a cabo en el proyecto RESCCUE, en el que dichas funciones fueron calibradas y contrastadas utilizando registros históricos de inundaciones y las correspondientes indemnizaciones gestionadas por el CCS (Martínez-Gomariz et al., 2021; Martínez-Gomariz, Guerrero-Hidalga, et al., 2020). En el proyecto ICARIA esta metodología fue retomada y ampliada con informes de daños recientes para su aplicación a escala metropolitana, manteniendo la misma base conceptual y aprovechando nuevamente la información proporcionada por el Consorcio para garantizar la robustez y representatividad de los resultados. Específicamente, se desarrolló un conjunto de curvas de daño para cada uno de los 36 municipios del AMB partiendo de las curvas de Barcelona como base, las cuales fueron modificadas en función de un conjunto de criterios socioeconómicos definidos en Martínez-Gomariz, Forero-Ortiz, et al., 2020.

Con objeto de facilitar su aplicación operativa, los daños fueron agregados según las 14 categorías de uso recogidas en la información catastral, permitiendo estimar de forma consistente las pérdidas económicas asociadas a distintos escenarios de inundación presentes y futuros.

{{< figura src="/images/numero-24/ICARIA_figura3.png" caption="Figura 3. Curvas de daños económicos en edificios empleadas." source="Martínez-Gomariz et al., 2019." >}}

## Resultados

Los resultados obtenidos muestran una tendencia consistente de incremento del riesgo de inundación en el Área Metropolitana de Barcelona (AMB) bajo escenarios de cambio climático, tanto en términos de daños económicos como de afectación sobre peatones y movilidad urbana. Asimismo, el análisis confirma que los eventos multipeligro —combinando precipitaciones intensas y temporales marítimos— agravan de forma generalizada los impactos respecto a las simulaciones exclusivamente pluviales.

### Impacto económico sobre edificios

Las simulaciones muestran un incremento progresivo y consistente de los daños económicos directos asociados a inundaciones urbanas para todos los periodos de retorno considerados. Bajo el escenario pluvial (single-hazard, SH), los daños asociados a un evento con periodo de retorno de 10 años (T10) aumentan desde aproximadamente 217 M€ en condiciones históricas hasta cerca de 294 M€ a finales de siglo. Para eventos más severos, como T100 y T500, los daños superan los 875 M€ y los 1.450 M€, respectivamente, evidenciando el efecto acumulativo que el cambio climático puede tener sobre las pérdidas económicas derivadas de las inundaciones urbanas.

La incorporación de la componente marina en el escenario multi-hazard (MH) genera incrementos adicionales de daños generalmente comprendidos entre el 4 % y el 7 % respecto a las simulaciones exclusivamente pluviales. Este aumento se explica principalmente por el efecto de retención hidráulica (backwater effect) que producen los niveles elevados del mar sobre los puntos de descarga de la red de drenaje, reduciendo su capacidad de evacuación y favoreciendo la acumulación de agua en superficie. Aunque este efecto resulta especialmente relevante en municipios costeros, su influencia se extiende a buena parte de la red metropolitana de drenaje debido a la elevada interconexión hidráulica existente.

La Figura 4 muestra la distribución espacial de los daños para los distintos municipios del AMB. Barcelona concentra las mayores pérdidas económicas absolutas, alcanzando valores superiores a los 50 M€ para eventos T10 en condiciones actuales y superando los 80 M€ en las proyecciones de finales de siglo. Otros municipios con elevada exposición, como Badalona, Castelldefels, Sant Boi de Llobregat, Sant Cugat del Vallès, Montcada i Reixac o Viladecans, también presentan daños potenciales significativos. En general, la distribución espacial de las pérdidas está fuertemente condicionada por la concentración de activos expuestos y por las características hidráulicas locales, observándose una clara correlación entre densidad urbana y magnitud de los daños.

{{< figura src="/images/numero-24/ICARIA_figura4.png" caption="Figura 4. Daños económicos por municipio del AMB correspondientes al escenario pluvial (single-hazard SH)." source="elaboración propia." >}}

Más allá de los daños asociados a eventos individuales, el indicador Expected Annual Damage (EAD) proporciona una visión más completa del riesgo al integrar la probabilidad de ocurrencia de distintos escenarios de inundación. Los resultados muestran un incremento sostenido del EAD en todos los escenarios analizados. En el caso del escenario SH, el EAD aumenta desde 139,8 M€ en condiciones históricas hasta 190,3 M€ a finales de siglo, lo que representa un incremento superior al 36 %. Bajo condiciones MH, el EAD alcanza los 199,2 M€, confirmando que la interacción entre inundación pluvial y forzamiento marino amplifica de forma sistemática el riesgo económico metropolitano (ver Tabla 1).

{{< tabla caption="Tabla 1. Resultados de Expected Annual Damage para el AMB." >}}
| Período de proyección climática | EAD para el escenario SH | EAD para el escenario MH | EAD para el escenario AD |
| :--- | :---: | :---: | :---: |
| Histórico | 139,8 M€ | 145,9 M€ | 121,2 M€ |
| Periodo 1 (2015-2040) | 162,3 M€ | 170,2 M€ | 144,6 M€ |
| Periodo 2 (2041-2070) | 171,1 M€ | 179,4 M€ | 154,7 M€ |
| Periodo 3 (2071-2100) | 190,3 M€ | 199,2 M€ | 167,9 M€ |
{{< /tabla >}}

### Efecto de las medidas de adaptación

El escenario de adaptación muestra una reducción consistente de los impactos en comparación con las simulaciones multipeligro. Las medidas basadas en drenaje urbano sostenible y soluciones basadas en la naturaleza, como pavimentos permeables, cubiertas verdes y áreas de infiltración permiten reducir los daños económicos entre un 10 % y un 18 % para eventos frecuentes e intermedios, al favorecer la retención temporal de escorrentía y disminuir las aportaciones de caudal a la red de drenaje durante las fases iniciales de las tormentas.

Los beneficios son especialmente significativos para eventos de menor periodo de retorno, en los que este tipo de actuaciones consiguen reducir de forma apreciable tanto los volúmenes inundados como la frecuencia de activación de situaciones de riesgo. En términos de daño anual esperado (EAD), las simulaciones muestran reducciones comprendidas entre el 12 % y el 17 % respecto al escenario MH, lo que confirma el potencial de estas medidas para mejorar la resiliencia urbana frente a los impactos recurrentes de las inundaciones. Sin embargo, la efectividad de estas medidas disminuye progresivamente a medida que aumenta la severidad de los eventos. Durante episodios extremos, la capacidad de infiltración y almacenamiento proporcionada por las soluciones basadas en la naturaleza resulta insuficiente para compensar completamente los incrementos de escorrentía asociados al cambio climático y a la interacción con los temporales marítimos.

En conjunto, los resultados ponen de manifiesto que las estrategias de adaptación basadas en soluciones naturales constituyen una herramienta eficaz para reducir el riesgo de inundación urbana, especialmente frente a eventos frecuentes y moderados. No obstante, su implementación debería complementarse con actuaciones estructurales convencionales, mejoras en la capacidad del sistema de drenaje y medidas de planificación territorial para afrontar adecuadamente los escenarios más extremos previstos para finales de siglo.

## DSS: Sistema de soporte a la toma de decisiones

Un aspecto fundamental del proyecto ICARIA ha sido garantizar la transferibilidad y replicabilidad de las metodologías desarrolladas para la evaluación del riesgo climático. Con este objetivo se ha desarrollado el ICARIA Decision Support System (ICARIA DSS), una plataforma web abierta, diseñada para apoyar la toma de decisiones en materia de adaptación y resiliencia climática. La herramienta integra información climática, modelos de riesgo multiamenaza, capacidades GIS y metodologías de evaluación de impactos para activos como edificios, infraestructuras y servicios urbanos. Entre sus principales funcionalidades destaca el módulo de evaluación de riesgos, Risk Assessment, que combina información de peligrosidad, exposición y vulnerabilidad para automatizar el análisis de impactos asociados a eventos climáticos extremos. En el ámbito específico de las inundaciones, el DSS incorpora de forma nativa las curvas profundidad-daño desarrolladas a partir de la información histórica de siniestros facilitada por el Consorcio de Compensación de Seguros (CCS y previamente empleadas en los proyectos RESCCUE e ICARIA. De esta forma, la plataforma permite semiautomatizar la estimación de daños económicos sobre edificios a partir de cartografía de inundación, facilitando la aplicación de la metodología presentada en este trabajo en nuevos territorios y escenarios de análisis.

Con el fin de favorecer su utilización en otras regiones y contextos geográficos, la herramienta permite asimismo incorporar curvas de vulnerabilidad personalizadas, de modo que los usuarios puedan adaptar los modelos de daño a las características constructivas, económicas o aseguradoras de sus propios ámbitos de estudio. Para la estimación de daños económicos por inundación, el DSS requiere cuatro conjuntos principales de información de entrada:

* Peligrosidad: mapa de inundación que contenga los calados máximos de agua asociados al evento analizado.
* Exposición: base de datos de edificios o activos expuestos, utilizando en este estudio la información catastral disponible para el Área Metropolitana de Barcelona.
* Vulnerabilidad: curvas profundidad-daño, incluyendo las desarrolladas a partir de los registros históricos de indemnizaciones del CCS o cualquier otra curva definida por el usuario.
* Agregación de resultados: delimitación administrativa o territorial sobre la que se desea sintetizar la información de daños (municipios, distritos, barrios u otras unidades de análisis).

La Figura 5 muestra un ejemplo de resultados generados a través del DSS de ICARIA donde los daños por inundación pluvial en edificios están agregados por distrito censal.

{{< figura src="/images/numero-24/ICARIA_figura5.png" caption="Figura 5. Ejemplo de resultados generados a través del DSS de ICARIA." source="ICARIA" >}}

Además del análisis de riesgos, el ICARIA DSS incorpora un amplio catálogo de medidas de adaptación y un marco metodológico de evaluación de resiliencia climática (Resilience Assessment Framework, RAF), que permite comparar distintos escenarios climáticos, analizar estrategias de adaptación y evaluar su eficacia mediante indicadores de reducción del riesgo y análisis coste-beneficio. La herramienta está disponible de forma abierta y gratuita a través del portal del proyecto ICARIA (https://www.icaria-project.eu/toolkit/).

{{< destacado-rojo >}}
## Conclusiones

La intensificación de los riesgos climáticos obliga a repensar el papel del seguro. Su función compensatoria seguirá siendo indispensable, especialmente ante eventos de gran magnitud como la DANA de 2024 o eventos más recientes como los de Andalucía o Portugal. Pero la escala creciente de los daños y la persistencia de la brecha de protección muestran que indemnizar después del desastre no puede ser la única respuesta. La próxima frontera del seguro climático no está únicamente en compensar mejor las pérdidas, sino en contribuir a prevenirlas, de acuerdo con las prioridades de la Estrategia Europea de Resiliencia Hídrica (CE, 2025).

MERLIN aporta una lección central: el seguro no puede construir prevención por sí solo, pero sí puede ayudar a que aumente el número y la escala de actuaciones territoriales que pueden reducir el riesgo. Para ello, la restauración debe expresarse en un lenguaje operativo para la gestión aseguradora: exposición, daños esperados, pérdidas evitadas, mantenimiento, responsabilidades y evidencia verificable. En este sentido, el principal desafío no es demostrar que la restauración genera beneficios ambientales, sino traducir esos beneficios a métricas y evidencias que puedan incorporarse a los procesos de evaluación, tarificación y gestión del riesgo utilizados por el sector asegurador.

Los casos analizados muestran dos dimensiones complementarias. El País Vasco permite ver cómo una intervención fluvial puede conectarse con cartografía de peligrosidad, modelización hidráulica y estimaciones económicas, en este caso gracias a la colaboración directa y al apoyo del Consorcio de Compensación de Seguros y los datos facilitados sobre daños. Rumanía empieza a adoptar nuevos sistemas innovadores de seguros en la reducción del riesgo para el sector agrario. Hungría muestra el problema desde otro ángulo: cuando fenómenos como la sequía tensionan la asegurabilidad, la inversión preventiva deja de ser un complemento ambiental y se convierte en una condición para sostener la protección futura.

La conexión entre restauración, adaptación y seguro no debe plantearse como una sustitución de responsabilidades. La planificación pública, la gestión territorial y la restauración ecológica siguen siendo indispensables. El futuro programa de trabajo del Plan Nacional de Adaptación al Cambio Climático (PNACC) de España ya incluye de forma explícita la restauración como una medida clave de adaptación, y con un valor añadido considerando el reciente análisis de riesgos complejos a nivel nacional del ERICC (OECC, 2025).

Esta evaluación ha demostrado que los riesgos climáticos no operan de forma aislada, sino que están profundamente interconectados. La restauración a gran escala de ecosistemas fluviales actúa de forma directa en las conexiones críticas entre dos sectores, con claras interdependencias y con posibles efectos en cascada identificados como claves. En concreto, los sectores del agua y los recursos hídricos, junto con los riesgos para el patrimonio natural y el sector forestal, son los que tienen mayor capacidad para desencadenar directamente otros riesgos. A la vez que los riesgos para el patrimonio natural, el sector agrícola y los sectores del agua son clave para la propagación de los impactos.

Estos son riesgos compartidos, no solo en el momento del pago, sino a lo largo de todo el ciclo de desastres y de adaptación al cambio climático. Por tanto, es importante ver el valor añadido que el sector asegurador tiene al aportar información, incentivos, criterios financieros y capacidad de aprendizaje para que las decisiones preventivas sean concretas, comparables y sostenibles. El seguro es un elemento clave en la prevención frente al riesgo del cambio climático y la degradación de ecosistemas que disminuyen la resiliencia a escala territorial. En un contexto de aumento del riesgo, el sector tiene una oportunidad, mediante la restauración de ecosistemas a gran escala, para dar un giro hacia la prevención en la gestión de riesgos para el sector asegurador y sus clientes (asegurados e inversores): la oportunidad de la restauración como medida de adaptación y reducción del riesgo con claros retornos económicos.
{{< /destacado-rojo >}}

## Agradecimientos

Financiado por el proyecto Horizon Europe ICARIA: Improving Climate Resilence of Critical Assets (GA 101093806).

{{< referencias >}}

Ajuntament de Barcelona. (2019). Pla Director Integral de Sanejament de la Ciutat de Barcelona—PDISBA: Estudi de Pluges.

Cea, L., & Costabile, P. (2022). Flood Risk in Urban Areas: Modelling, Management and Adaptation to Climate Change. A Review. Hydrology, 9(3), 50. https://doi.org/10.3390/hydrology9030050

De La Cruz-Coronas, À., Russo, B., Pacho-Gómez, S., & Yubero-Peña, D. (2026). Socio-Economic Impacts of Pluvial Floods in the Metropolitan Area of Barcelona in a Climate Change Context. Sustainability, 18(9), 4530. https://doi.org/10.3390/su18094530

Del-Rosal-Salido, J., Bermúdez, M., Ortega-Sánchez, M., Sanuy, M., Silva-Santana, M., & Jiménez, J. A. (2025). A composite index framework for compound flood risk assessment. Communications Earth & Environment, 6(1), 342. https://doi.org/10.1038/s43247-025-02331-z

IPCC. (2023). Climate Change 2022 – Impacts, Adaptation and Vulnerability: Working Group II Contribution to the Sixth Assessment Report of the Intergovernmental Panel on Climate Change (1.a ed.). Cambridge University Press. https://doi.org/10.1017/9781009325844

Leone, M. F., Zuccaro, G., De Gregorio, D., Turchi, A., Tedeschi, A., Büegelmayer-Blaschek, M., Sfetsos, A., Zarikos, I., Coronas, A. D. L. C., & Russo, B. (2025). A holistic asset-level modelling framework for a comprehensive multi-hazard risk/impact assessment: Insights from the ICARIA project. International Journal of Disaster Risk Reduction, 119, 105319. https://doi.org/10.1016/j.ijdrr.2025.105319

Martínez-Gomariz, E., Forero-Ortiz, E., Guerrero-Hidalga, M., Castán, S., & Gómez, M. (2020). Flood Depth-Damage Curves for Spanish Urban Areas. Sustainability, 12(7), 2666. https://doi.org/10.3390/su12072666

Martínez-Gomariz, E., Forero-Ortiz, E., Russo, B., Locatelli, L., Guerrero-Hidalga, M., Yubero, D., & Castan, S. (2021). A novel expert opinion-based approach to compute estimations of flood damage to property in dense urban environments. Barcelona case study. Journal of Hydrology, 598, 126244. https://doi.org/10.1016/J.JHYDROL.2021.126244

Martínez-Gomariz, E., Guerrero-Hidalga, M., Forero-Ortiz, E., Castán, S., Velasco, M., & Villanueva, Á. (2020). Inundaciones pluviales en zonas urbanas españolas: Un modelo de estimación de daños basado en la experiencia pericial. Consorseguros, (12). https://consorsegurosdigital.com/almacen/pdf/inundaciones-pluviales-en-zonas-urbanas-espanolas-un-modelo-de-estimacion-de-danos-basado-en-la-experiencia-pericial.pdf

Martínez-Gomariz, E., Guerrero-Hidalga, M., Russo, B., Yubero, D., Gómez, M., & Castán, S. (2019). Desarrollo y aplicación de curvas de daño y estanqueidad para la estimación del impacto económico de las inundaciones en zonas urbanas españolas. Ingeniería del agua, 23(4), 229. https://doi.org/10.4995/ia.2019.12137

Molina-López, P., De La Cruz-Coronas, À., Russo, B., & Bladé I Castellet, E. (2026). Flood risk assessment: current status and future perspectives in Spain. Ingeniería del Agua, 30(2), 136-152. https://doi.org/10.4995/ia.24696

Russo, B., Coronas, À. de la C., Leone, M., Evans, B., Brito, R. S., Havlik, D., Bügelmayer-Blaschek, M., Pacheco, D., & Sfetsos, A. (2023). Improving Climate Resilience of Critical Assets: The ICARIA Project. Sustainability, 15(19), 14090.

Sanuy, M., Rigo, T., Jiménez, J. A., & Llasat, M. C. (2021). Classifying compound coastal storm and heavy rainfall events in the north-western Spanish Mediterranean. Hydrology and Earth System Sciences, 25(6), 3759-3781. https://doi.org/10.5194/hess-25-3759-2021

UNDRR. (2015). Sendai Framework for Disaster Risk Reduction 2015—2030 (p. 37). https://www.undrr.org/media/16176/download?startDownload=20250107

UNDRR. (2020). Human cost for disasters: An overview of the last 20 years. https://www.undrr.org/publication/human-cost-disasters-overview-last-20-years-2000-2019

{{< /referencias >}}