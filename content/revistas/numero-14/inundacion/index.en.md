---
title: "Analysis of flood loss data in Spain at the municipal level"
category: "Analysis"
pdf_download: "/pdf/num22/editorial.pdf"
sidebar_image: "/images/numero-14/foto_portada14_inundacion.png"
sidebar_text: "The previous volume of this magazine published a depiction of flood risk in Spain based on Extraordinary Risk Insurance Scheme data. Resolution in that study was down to the provincial level, and a series of assumptions were made to refine the plot of the level of risk, e.g. extrapolation of loss data onto the percentage uninsured homes."
weight: 2
image: "/images/numero-14/foto_portada14_inundacion.png"
summary: "That study disclosed a series of spatial characteristics that predispose to higher losses: proximity to the sea or to large river drainage basins and high exposure."
authors:
    - name: "Francisco Espejo Gil"
      institution: "Deputy Director for Studies and International Relations"
    - name: "Pablo López Vilares"
      institution: "Senior Expert, Sub-Directorate for Expertise"
    - name: "Angélica Guerrero López"
      institution: "Sub-Directorate for Expertise"
    - name: "Bin Pu"
      institution: "Sub-Directorate for Expertise"
    - name: "Javier Rosa Corral"
      institution: "Sub-Directorate for Expertise"
    - institution: "Consorcio de Compensación de Seguros"
---

## Introduction

The previous volume of this magazine published a depiction of flood risk in Spain based on Extraordinary Risk Insurance Scheme data. Resolution in that study was down to the provincial level, and a series of assumptions were made to refine the plot of the level of risk, e.g. extrapolation of loss data onto the percentage uninsured homes.

That study disclosed a series of spatial characteristics that predispose to higher losses: proximity to the sea or to large river drainage basins and high exposure. Let us just point out here that indemnities for flood losses, including coastal flood, as floods are defined in section 2 of the Extraordinary Risks Regulation, make up 69% of all compensation paid out under the extraordinary risk insurance scheme in the past 25 years. This important consideration and the plots of losses at the provincial level immediately led us to look for a way to plot risk at a higher level of granularity. That is why this study presents a tool, a viewer, for plotting the indemnities paid out by the CCS for floods, though excluding coastal flood, by municipality, in the last 15 years, from 2006 to 2020 (Figure 1). This increase in resolution from Spain's 50 provinces and its 2 autonomous cities to its 8,131 municipalities has multiplied data resolution by a factor of more than 150, and hence the need to use a viewer to take full advantage of such a wealth of information. Unlike the previous study, no assumptions or extrapolations have been made here. Instead, the actual data have been plotted, with economic values updated to 31 December 2020.

{{< figura src="/images/numero-14/foto_portada14_inundacion.png" caption="Figure 1. First page of the CCS flood loss compensation data viewer." source="" >}}

The extraordinary risk insurance scheme also covers personal injury and business interruption. However, these losses are low in proportion to the indemnities paid out for property damage, accounting for 97% of the total, plus compensation for personal injury results not from objective criteria but instead depends on the sum established as insured by the person in question. For this reason, since the goal of this study is to provide an x-ray of flood losses indemnified by the insurance scheme, its focus has been placed on property damage only.

## Methodology

The viewer has been developed using the ArcGIS platform, and maps that plot the risk globally (i.e., total compensation data) have been created, along with others that attempt to refine the depiction of flood risk by dividing that amount by the various factors indicative of exposure:

- Population of the municipality. Source: Instituto Nacional de Estadística [Spain's National Institute of Statistics] (INE, from the Spanish abbreviation).
- Number of homes in the municipality. Source: population and residential park censuses 2011 (INE).
- Number of motor vehicles in the municipality. Source: Dirección General de Tráfico [Directorate-General for Traffic] (DGT, from the Spanish abbreviation).
- Number of companies per municipality. Source: INE.
- Aggregate assessed value of construction in each municipality. Source: compiled by the authors from statistical data released by the Land Survey Office [Spanish Ministry of Economic Affairs and Digital Transformation] and information furnished by the Land Survey Offices of Bizkaia and Gipuzkoa. At the time of this writing no data are available from the Land Survey Offices of Álava or Navarre.

Some maps plot all losses for all insured property, but other maps have also been drawn up plotting the following specific risk categories:

- Homes.
- Business, industry, and similar risks.
- Infrastructure.
- Motor vehicles.

For ease of reference and the ensuing cartographic analysis, the following layers of geographic data have been added to the viewer:

- Basic map of Spain. Source: Instituto Geográfico Nacional [Spain's National Geographic Institute] (IGN, from the Spanish abbreviation).
- Borders of Spain's Autonomous Regions. Source: IGN.
- Provincial borders. Source: IGN.
- Main rivers (rivers draining a basin with a surface area larger than 500 km2). Source: Spanish Ministry for the Ecological Transition and the Demographic Challenge.
- Drainage basins for the main rivers. Source: Spanish Ministry for the Ecological Transition and the Demographic Challenge.
- Flood-prone zones with 500-year return periods. Source: National Flood Zone Mapping Service (Ministry for the Ecological Transition and the Demographic Challenge).

Table 1 lists the maps that can be viewed using the viewer and the main features of those maps.

{{< tabla caption="Table 1. List of maps on the viewer and their main features." >}}
| Map number | Features | Units | Remarks |
| :---: | :--- | :---: | :--- |
| 1 | All properties. Total loss by municipality | € | |
| 2 | All properties. Mean yearly loss by municipality | € | |
| 3 | All properties. Mean yearly loss by municipality and inhabitant | € | |
| 4 | All properties. Mean yearly loss by municipality and aggregate assessed value of construction | Parts per million | Indemnified euros by each million of assessed (cadastral) value of construction exposed. |
| 5 | Flood: residential properties. Mean yearly loss by municipality | € | |
| 6 | Flood: residential properties. Mean yearly loss by municipality and inhabitant | € | |
| 7 | Flood: residential properties. Mean yearly loss by municipality and registered homes | € | Indemnified euros by municipality and registered homes (exposed). |
| 8 | Flood: residential properties. Mean yearly loss by municipality and residential value of construction | Parts per million | Indemnified euros by each million of residential assessed (cadastral) value of construction exposed. |
| 9 | Flood: automobiles. Mean yearly loss by municipality | € | |
| 10 | Flood: automobiles. Mean yearly loss by municipality and registered vehicle | € | Indemnified euros by municipality and registered (exposed) vehicle. |
| 11 | Flood: industrial, commercial and similar properties: Mean yearly loss by municipality | € | |
| 12 | Flood: industrial, commercial and similar properties: Mean yearly loss by municipality and registered business | € | |
| 13 | Flood: industrial, commercial and similar properties: Mean yearly loss by municipality and assessed construction value for this kind of risks | Parts per million | Indemnified euros to industries, commerces and similar risks by municipality and million of assessed (cadastral) value exposed for this kind of risks. |
| 14 | Flood: infrastructures. Mean yearly loss by municipality | € | |
{{< /tabla >}}

## Results

To give an extensive description of all possible results that can be retrieved would far exceed the scope of this article, so we will confine our remarks to a limited selection of maps and to certain features of those maps.

Figure 2 shows the annual average flood losses paid under the extraordinary risk insurance per municipality during the period examined. The ten municipalities which received the highest annual average flood compensation appear on Table 2. It is appropriate to mention here that these are the total compensation data per municipality, and that the compensation payments are on the properties insured. That is, not all of the flood losses are represented here, but rather solely those which were insured and therefore paid compensation by the CCS.

Overall, it is estimated that the extraordinary risk insurance covers on the order of 50-60% of the total losses, with public infrastructures and other public properties constituting the principal source of this gap in coverage, since the Administration insures itself to a large extent. This is the reason why no comments will be made in this study on the information provided in the viewer on flood damage to infrastructures, since they are strongly dependent on the policy of the Public Administration to which they belong as to whether they are insured or not. Another relevant factor is the different level of insuring from one region to another, as well as the variation between urban and rural areas. Nevertheless, having made these considerations, coherent spatial characteristics can be observed.

{{< figura src="/images/numero-14/inundacion_municipio02%20grande.png" caption="Figure 2. Annual average compensation under the extraordinary risk insurance due to floods, by municipality (2006-2020)." source="" >}}

{{< tabla caption="Table 2. The ten municipalities of Spain with the highest annual average compensation (2006-2020)." >}}
| Nº | Municipality | Basin Authority | Province | Loss (€/year) |
| :---: | :--- | :--- | :--- | :---: |
| 1 | Orihuela | Segura | Alicante | 7,098,641.51 |
| 2 | Los Alcázares | Segura | Murcia | 5,350,222.91 |
| 3 | Murcia | Segura | Murcia | 4,182,169.95 |
| 4 | Vera | Andalusian Mediterranean | Almería | 4,128,396.24 |
| 5 | Málaga | Andalusian Mediterranean | Málaga | 4,095,421.18 |
| 6 | Marbella | Andalusian Mediterranean | Málaga | 3,201,282.98 |
| 7 | Tarragona | Catalan Internal Basins | Tarragona | 2,861,505.74 |
| 8 | San Javier | Segura | Murcia | 2,744,628.13 |
| 9 | Lorca | Segura | Murcia | 2,645,056.48 |
| 10 | Donostia/San Sebastián | Basque Internal Basins | Gipuzkoa | 2,522,306.66 |
{{< /tabla >}}

Once again the cross between hazard level and exposure is what determines the highest loss. Thus, the coincidence between geographical features and coastal zones play a very relevant role in this higher amount of losses, particularly on the Mediterranean coast in Andalusia, Murcia Region, the Community of Valencia and the south of Catalonia, as well as the coast of the Bay of Biscay, together with the exposure. The large cities close to major river courses, such as Zaragoza or Cordova, for example, also reflect this cross between hazard level and exposure. The very weight of the exposure in the large metropolitan areas of Madrid and Barcelona is also responsible for their accumulation of greater losses. In addition to in Figure 2 and, of course, in the viewer itself, the analysis of the municipalities with the highest level of flood losses according to river basins, which appear on Table 3, casts greater light on this issue.

It is evident that the river basins presenting a higher loss level are those of the Segura –five of the ten municipalities which, on the national level, suffer the most losses belong to this basin–, the Mediterranean basins of Andalusia –three of whose municipalities are also among the top ten in Spain– and others, such as the Júcar, or the internal basins of Catalonia and the Basque Country. The major river basins, such as those of the Ebro or the Guadalquivir also include municipalities with extensive flood damage, as a result of their significant exposure or of tributaries of the main course which cause serious flooding and are due to a greater extent to processes which are more similar to those causing floods on the coast than to those from the overflow of a major river course: the cases of Tafalla, Écija, Lucena or Jaén.

{{< figura src="/images/numero-14/inundacion_municipio_tabla03.png" caption="Table 3. The five municipalities with the highest annual average compensation due to floods, by river basin, in the period 2006-2020." source="" >}}

The absence of significant geographical reliefs next to major cities and the low population density mean that other major river basins, such as those of the Douro, Tagus (with the exception of Madrid and its metropolitan area, a result of the significant exposure), Guadiana or Miño-Sil, present relatively minor flood damage. In the coast of Galicia and the Bay of Biscay (with the exception of the Basque coast), rainfall of a lesser torrential nature –large accumulations can occur but with a lesser degree of intensity than on the Mediterranean coast– together with a lower level of urban development, or a more disperse development, mean that, except in the large population centres of Galicia and Asturias, flooding does not cause as much damage as in other coastal areas.

The Balearic and Canary Islands logically respond to flooding dynamics similar to those of other highly developed coastal areas, where the torrential nature of the rainfall combines with the geographical relief, generating courses with little response time and strong current, with high exposure.

Figure 3 represents these same average amounts of compensation by municipality and year, divided by the number of inhabitants, for the purpose of putting into perspective the effect of the exposure. On this map, the effects of the major population centres disappear and others which reflect the real hazard level better become clearer. The municipalities which appear with higher losses per inhabitant tend to be due, in general, to sudden flood dynamics occurring in short watercourses, with steep downgrades and short accumulation times. In addition to the coastal areas of the Mediterranean and Eastern Bay of Biscay, already mentioned, these effects appear in the Pyrenees, Cantabrian Mountains (especially on their southern side), the Middle Area of Navarre and both sides of the Catalan Mediterranean System and the Penibaetic System (in its most western sector). To a lesser degree, the same occurs in Sierra Morena and the Montes de Toledo.

{{< figura src="/images/numero-14/inundacion_municipio03.png" caption="Figure 3. Annual average compensation under the extraordinary risk insurance due to floods, by municipality and inhabitants (2006-2020)." source="" >}}

{{< tabla caption="Table 4. The ten municipalities of Spain with the highest annual average compensation by inhabitant (2006-2020)." >}}
| Nº | Municipality | Basin Authority | Province | Loss (€/inhab/year) |
| :---: | :--- | :--- | :--- | :---: |
| 1 | Tirapu | Ebro | Navarre | 1,105.58 |
| 2 | Beniparrell | Júcar | Valencia | 682.89 |
| 3 | Frías | Ebro | Burgos | 527.00 |
| 4 | Vilamòs | Ebro | Lleida | 438.10 |
| 5 | Fontanilles | Catalan Internal Basins | Girona | 384.45 |
| 6 | Massanes | Catalan Internal Basins | Girona | 345.33 |
| 7 | Vinaixa | Ebro | Lleida | 337.08 |
| 8 | Castiello de Jaca | Ebro | Huesca | 328.50 |
| 9 | Los Alcázares | Segura | Murcia | 322.50 |
| 10 | Pueyo | Ebro | Navarre | 279.78 |
{{< /tabla >}}

The ten municipalities with the highest losses per inhabitant, which appear on Table 4, all coincide in these circumstances, with the annotation that the low population of some of them, such as Tirapu (40 inhabitants) makes the losses per capita soar. Although the series of data is of a relatively lengthy duration (15 years), the small population of some of these municipalities also means that events of great significant could have an impact on these classifications. Table 5 shows the five municipalities of each river basin that present the highest losses compensated per inhabitant in the period under study, and the previous assessment on those evidencing higher losses is confirmed. Thus, when comparing the five municipalities of each river basin with the highest amount of losses compensated per capita, the largest amounts appear, in general, in the Ebro River Basin (Figure 4), in its areas located in the Pyrenees or in the Iberian-Cantabrian headwaters of the river.

{{< figura src="/images/numero-14/inundacion_municipio_tabla05.png" caption="Table 5. The five municipalities with the largest annual average per inhabitant of compensations due to flooding, by river basin, in the period 2006-2020." source="" >}}

{{< figura src="/images/numero-14/inundacion_municipio04.png" caption="Figure 4. Example of visualisation of the Ebro River Basin in the viewer, with annual average losses by municipality and inhabitant, river courses and flood areas with a return period of 500 years (CNZI)." source="" >}}

We will examine in greater detail below the losses caused according to three major types of risk: residential properties (including condominiums), automobiles and businesses, industries and other similar risks such as offices, sports facilities, educational facilities, etc.

Figures 5, 6 and 7 show the annual average losses by municipality for each of these three types of risk, respectively.

{{< figura src="/images/numero-14/inundacion_municipio05.png" caption="Figure 5. Annual average compensation for residential properties under the extraordinary risk insurance due to floods, by municipality (2006-2020)." source="" >}}

{{< figura src="/images/numero-14/inundacion_municipio06.png" caption="Figure 6. Annual average compensation for automobiles under the extraordinary risk insurance due to floods, by municipality (2006-2020)." source="" >}}

{{< figura src="/images/numero-14/inundacion_municipio07.png" caption="Figure 7. Annual average compensation for industries, businesses and other similar risks under the extraordinary risk insurance due to floods, by municipality (2006-2020)." source="" >}}

The graphic information is complemented by the classifications shown on Tables 6 to 11, where, for each type of risk, the ten municipalities with the highest annual average losses, on a total basis, and the ten municipalities with the highest annual average losses for exposed residential properties, vehicles or businesses, respectively, are listed.

{{< tabla caption="Table 6. The 10 municipalities with the highest flood losses for residential properties, annual average." >}}
{{< /tabla >}}

{{< tabla caption="Table 7. The 10 municipalities with the highest flood losses for residential properties, annual average per property exposed." >}}
{{< /tabla >}}

{{< tabla caption="Table 8. The 10 municipalities with the highest flood losses for automobiles, annual average." >}}
{{< /tabla >}}

{{< tabla caption="Table 9. The 10 municipalities with the highest flood losses for automobiles, annual average per automobile exposed." >}}
{{< /tabla >}}

{{< tabla caption="Table 10. The 10 municipalities with the highest flood losses for businesses, industries and similar, annual average." >}}
{{< /tabla >}}

{{< tabla caption="Table 11. The 10 municipalities with the highest flood losses for businesses, industries and similar, annual average per company exposed." >}}
{{< /tabla >}}

From a comparison of both sources, graphics and tables, conclusions can be reached as to the effects of the exposure of dwellings in areas with a high hazard level, such as the Vega Baja area of the Segura River Basin or the area around the Mar Menor lagoon and, in general, the coastal areas of the south and southeast of the Peninsula, which are normally heavily developed as a consequence of the pressure of tourism and property development. When analysing the losses by municipality and dwellings exposed, the factors of proximity to more or less defined watercourses are those which become most evident. Many of these municipalities are located in the Middle Ebro Valley, Navarre or in the Bajo Segura.

In the case of automobiles, in addition to the usual municipalities, others appear with significant exposure, such as Madrid, Malaga or Valencia, as well as Vilagarcía de Arousa in the demarcation of Galician Atlantic Basins. In the case of this kind of property, due to its mobility, it would be easier to avoid losses, by removing vehicles from flood areas in situations of warnings of intense rainfall or flooding, as well as by reducing the vulnerability of the parking facilities in the face of flood risks; perhaps this type of risk would be the one which could be more easily and quickly addressed through actions to reduce risk.

In the case of industries and businesses, which generally involve considerably higher losses than the other two types, it could be said that the municipalities with the greatest impact are affected more with respect to businesses, offices and other similar facilities than by eminently industrial risks. Although on the list of total losses there are municipalities with a strong industrial presence (Tarragona, San Sebastián, Valle de Trápaga, Barcelona, etc.), and that without a doubt very significant losses occur in this type of facility, it is the cumulative effect of many businesses, offices and other facilities (sports, educational, etc.) that ends up making the losses rise in the areas most exposed to flood hazards. When examining the list of the municipalities with the highest losses compensated per company exposed, this fact becomes evident, since some very small municipalities appear on the list, with very few commercial establishments, and make this average rise. It is relatively easier to undertake risk reduction actions in a few industries which, when flooded, suffer very high losses, than in a myriad of small businesses and facilities, more limited in their financial capacity and, perhaps, less aware of the risks. Here another possible line of priority action can be perceived with a view to the reduction of flood risk in Spain.

As we mentioned at the start, it is very difficult to synthesise in a few words and graphics all of the information this viewer contains and all of the potential of the wealth of data on compensation payments for flood damage held by the Consorcio de Compensación de Seguros and which are made available here for all interested parties. The principal value of these data and of this viewer is, without a doubt, to facilitate an awareness of the risk of floods and to serve as an indicator for the implementation of risk-reduction measures by the competent government administrations and by the insureds themselves.