---
title: "Geographical and temporal description of extraordinary risk loss data arising from natural causes"
category: "Contributions"
pdf_download: "/pdf/num22/editorial.pdf"
sidebar_image: "/images/numero-19/portada_representación-espacio-temporal.jpg"
sidebar_text: "The relationship between the values of costs of compensation pay-outs, the assets insured and the natural events which bring about claims that arise in a territory shows varying characteristics depending on the scale or detail of aggregation whereby they are observed."
weight: 6
image: "/images/numero-19/portada_representación-espacio-temporal.jpg"
summary: "This paper conducts an analysis of the geographical and temporal component of the data on compensation pay-outs and exposure of property items insured in combination."
authors:
    - name: "Francisco Espejo Gil"
    - name: "Urko Elosegi Gurmendi"
    - institution: "Subdirectorate for Research and International Relations"
    - institution: "Consorcio de Compensación de Seguros"
---

## Introduction and background
Insurance is among the most detailed and accurate sources of information available for researching catastrophe risks. In most countries there is a common problem of accessibility of data (which is typically dispersed among the dozens or even hundreds of insurers who usually operate in a market), given that there are sometimes issues of confidentiality or involving sales policy when it comes to making it obtainable for researchers. An additional problem is availability itself and the demand (and take up) for this product. The norm in the vast majority of jurisdictions is to take out policies specific to certain catastrophe risks on a separate, voluntary basis. It seems appropriate to assume that those people who wish to take out these forms of coverage are those who have most exposure to the hazard in question, meaning that a problem of adverse selection tends to arise, which translates into a high premium cost, in turn leading to lower market penetration of the insurance cover, with the outcome that the data is not only dispersed, but also biased and relatively scarce.

Only a few countries have insurance market regulatory mechanisms which facilitate the pooling of certain hazard risks to bypass the adverse selection problem, cut back on the cost of premiums and maximise penetration for the insurance. One such country is Spain, where it is mandatory to extend coverage for almost all property insurance to a set of «extraordinary risks», which encompass flooding, wind-storm phenomena or certain geological risks such as earthquakes, tsunamis and volcanic eruptions. For such extraordinary risk insurance, a surcharge is applied for those policies taken out with any private insurer operating in the Spanish market which is used so that a public sector insurer, namely the Consorcio de Compensación de Seguros (CCS), can pay out compensation for loss or damage caused by such hazards to all property insured. This means that the situation in Spain is relatively far more conducive to studying such natural risks on the basis of the data on loss or damage insured because:

1. The vast majority of insured property is also automatically covered against extraordinary risks, eliminating the protection gap that exists in other countries around us.
2. The compensation pay-outs for hazards of this kind are the sole responsibility of just a single institution, Consorcio de Compensación de Seguros, which has an extensive set of detailed data on indemnities for the said extraordinary risks.

Among the goals of CCS is promoting risk prevention and reduction by working in partnership with other institutions and engaging in activities which help to keep the impacts of catastrophe events to a minimum. There is no doubt that the data on claims experiences kept by CCS are an extremely useful source when it comes to achieving these supplementary goals.

## Methodology
This paper conducts an analysis of the geographical and temporal component of the data on compensation pay-outs and exposure of property items insured in combination. These two pieces of information come from different reporting systems within CCS and exhibit different structures and characteristics at source.

### Determining the geographical elements in the analysis
The relationship between the values of costs of compensation pay-outs, the assets insured and the natural events which bring about claims that arise in a territory shows varying characteristics depending on the scale or detail of aggregation whereby they are observed.

The operational information that exists at the CCS includes, among other items, the geographical data comprising the post code and municipality for claims handled. A post code established in Spain allows analysis of a small area, which (particularly in highly populated territory) provides a significant improvement of the detail which the data affords at municipal level, thereby permitting more granularity of the information and a more insightful understanding of the characteristics and needs of different areas within these municipalities. In the processing of geographical data, the post code can function as an aggregator which enables positioning of information in compliance with the regulations on personal data protection. Furthermore, it is an item of data that is commonly gathered and integrated within the activities of a whole host of sectors (such as the insurance industry) and is widely used in compiling market research (Sereno, 2009).

Based on assignment of the post code and municipality which each of the compensation handling procedures has and the estimated figure for sums of capital per post code which the Surcharge Information System (SIR) provides (a system that has been applied since 2019 whereby insurers report the post code where all their insured risk is located that is subject to the extraordinary risk surcharge to the CCS), all the supra-municipal areas can be linked together which make up different magnitudes of aggregation that are equivalent to the administrative levels in Spain and the European Union. This produces valuable data with which to facilitate planning and decision-making with the aim of designing highly efficient strategies that become drivers of management initiatives to find out about and reduce risks.

### Transformation and modelling of the data
Linking data on compensation and exposure per post code, municipality, province, region, hydrographic district, or the NUTS-1, 2 and 3 European statistical areas, requires applying data cleansing processes and transformations to each of the two sources individually with the goal of ultimately joining together geographical areas, aggregating and calculating analytical variables.

Modelling the temporal aspect consisted of characterising each element of processing based on the hydro-meteorological season of the year according to the date of occurrence and identifying if it took place in spring (March, April, May), summer (June, July, August), autumn (September, October, November) or winter (December, January, February). «Seasonality» of this kind enables observation of loss events associated with hydro-meteorological phenomena in a manner that is readily recognisable for the reader.

For geographical or spatial analysis of the data and graphical depiction of it, the data on all of the administrative areas must be identified using the same one-to-one codes which the publishing {{< tooltip text="authorities" num="1" url="" >}}
Instituto Geográfico Nacional (IGN) for administrative boundaries, MITECO for hydrographic districts and Correos for postal code layers.
{{< /tooltip >}} provide of the geographical layers used, so it is essential to carry out additional procedures of verification, standardisation and enhancement of information to enable combination of this sort for the entire area over which CCS {{< tooltip text="operates" num="2" url="" >}}
Territorial scope of Spain (peninsula, Balearic Islands, Canary Islands, Ceuta and Melilla).
{{< /tooltip >}}.

### Selecting the period and improving the quality of aggregate data
CCS has historical data on compensation paid out from as far back as the institution’s very beginnings in operation. Nevertheless, the information on individualised case handling began to be managed in digital format in 1996, thus creating a historical record which allows optimal processing and analysis of the past 27 years of operational activity.

Analysis of the individualised information reveals a certain number of records where values were possibly logged erroneously from the outset. This is the case for certain territorial variables which are subject to geo-processing in this study, such as the post code. Since this item of data is ordinarily provided by people who take out a policy or file a claim, on occasion there are times when the person gives the post code which they believe to be correct but this turns out to be inaccurate. Databases contain case files that cannot be directly allocated to existing post codes, though they may potentially belong to the same province, regional autonomy or any administrative district at a higher level. This is true of codes which have the first two digits (which identify the province) but end in triple zero, such as '10000', '28000’ and '35000'. These are non-valid post codes according to Spain’s current post code system. By categorising such cases as handwriting errors, and purely for the purposes of conserving completeness of information on the monetary sums in areas ranked as provinces or higher and to endow the data as a whole with full statistical robustness for supra-municipal aggregate figures, we propose implementing a post code standardisation process which entails identifying them using the «closest» correct post code for the location in question and applying the criterion of totalling the costs of claims for non-valid records, though using a post code that is identifiable within the same province as the nearest which ends in 1, which is usually to be found in the centre of the capital of the province.

For data on the cost of loss events, this allows some 120 million euros, out of the figure of almost 8.5 billion euros, which is the sum total of all compensation relating to natural causes in Spain from 1996 to 2022, to be reallocated from province level upwards by assigning another geographical location to a total of 22,952 procedures out of 1,533,892 (1.49%).

If we apply the same criterion to insured property data, we can manage to reinstate around 1.2 billion euros out of the figure of almost 6.5 trillion euros (which is estimated to be the sum total of all sums insured in Spain as of 31 December 2022) to the sum totals from province level upwards and can pinpoint another location for a total of 7,361 policies out of 60,651,203 (0.01%).

### Causes and aggregated areas: Resulting geodata
The set of data transformed and homogenised by area enables it to be filtered by the type of cause it is desired to observe. For the purposes of the study which we present in this edition of the magazine we have examined the effect of flood (riverine and pluvial), coastal flood, and geological causes, such as earthquakes, tsunami, and volcanic eruptions for the full historical period from 1996 to 2022 and also the impact of windstorms – or, according to the regulations’ wording, atypical cyclonic storms (ACSs) – over the past 11 years. The reasoning behind these different time periods stems from the fact that, whereas for flooding (both fluvial and pluvial) and coastal flooding the same criterion for coverage has been applied since 1996, for ACSs (strong windstorms) the threshold for coverage has been changeable along the years but homogeneous for 2012-2022, which is the period we study in detail here.

As a product of the joining together and aggregation of all the pre-processed tables we achieve tables of alphanumeric information that are compatible for combining with their respective geometric layers and can visualise thematic maps based on the following attribute fields:

{{< tabla caption="Table 1. Dictionary of data from tables in the historical record of estimates of costs of losses and sum insured according to causes and Spanish administrative areas. Note: The cause described as an ACS (atypical cyclonic storm) takes in the 2012-2022 period. Source: CCS." >}}
| Column | Description |
| :--- | :--- |
| ID | Identifier for the unit of area. |
| numero_siniestros | Total number of losses (1996-2022 dataset). |
| coste_total | Compensation for property damage by post code regardless of the risk class (1996-2022 dataset). |
| coste_viviendas | Compensation for property damage by post code within the risk class of dwellings and home-owners’ communities (1996-2022 dataset). |
| coste_vehiculos | Compensation for loss or damage to vehicles with a Spanish number plate by post code for the claim event (1996-2022 dataset). |
| coste_resto | Compensation for property damage by post code for the risk classes of offices, business and industrial risks, infrastructure and the rest (1996-2022 dataset). |
| numero_de_polizas | Number of current policies in force at 31-12-2022. |
| total_capitales | Value in euros of total sums insured for property damage by post code regardless of risk class as of 31-12-2022. |
| capital_viviendas | Value in euros of sums insured for property damage by post code within the risk class of dwellings and home-owners’ communities as of 31-12-2022. |
| capital_vehiculos | Estimated value in euros of vehicles with a Spanish number plate by post code for the policy holder’s address as of 31-12-2022. |
| capital_resto | Value in euros of sums insured for property damage by post code for the risk classes offices, business and industrial risks, infrastructure and the rest as of 31-12-2022. |
| dt_primavera | Compensation for property damage during spring-time (March, April and May) by post code regardless of the risk class (1996-2022 dataset). |
| dt_verano | Compensation for property damage in summer-time (June, July and August) by post code regardless of the risk class (1996-2022 dataset). |
| dt_otonno | Compensation for property damage throughout autumn (September, October and November) by post code regardless of the risk class (1996-2022 dataset). |
| dt_invierno | Compensation for property damage in winter-time (December, January and February) by post code regardless of the risk class (1996-2022 dataset). |
| est_max_dt | Season with the highest compensation for property damage by post code regardless of the risk class (1996-2022 dataset). |
| prop_max_dt | Value in proportion to the total of the season with the highest compensation for property damage by post code regardless of the risk class (1996-2022 dataset). |
| tasa_siniestralidad | Euros/year paid out in compensation per euro insured as of 31-12-2022. |
| tasa_sini_millon_aseg | Euros/year paid out in compensation per million euros insured as of 31-12-2022. |
{{< /tabla >}}

## Findings
Even though the source information has a resolution at post code level, in presenting the findings from this exercise we shall opt in favour of aggregation by municipality, which transpires as more intuitive from the reader’s standpoint. On occasion we will aggregate the information by province or regional autonomy.

The exposure of insured property by municipality given in Figure 1 offers an unusually faithful reflection of Spain’s population structure, with very high values insured on the coast and in the Guadalquivir and Ebro valleys, as well as in Madrid and its area of influence. The minimum brackets (large amount of municipalities which do not reach 100 million euros in total sum insured – amassing dwellings, industries, businesses, infrastructure and motor vehicles –) emerge in Castile and León, the mountainous regions in Aragon and Castilla-La Mancha, the Pyrenean foothills and other mountainous areas within the peninsular interior.

{{< figura src="/images/numero-19/Figura%2001_M_capitales_cBarras.jpg" caption="Figure 1. Capital insured for property (residential, commercial, industrial, infrastructure and motor vehicles) by municipal district as of 31 December 2022." source="" >}}

If we aggregate this information by regional autonomies in Figure 2, only two – Catalonia and the Madrid Region – top a trillion euros in the total sum insured, while Andalusia and Valencian Region fall within the bracket of 500 billion to one trillion euros of total capital insured. The autonomous cities of Ceuta and Melilla are (as one might suppose) the areas which have the least capital insured, with Cantabria and La Rioja falling within the group having 10 to 100 billion in insured capital, while all the other regional autonomies are within the 100-500 billion euro range. As we said earlier, the overall total sum insured is of the order of some 6.5 trillion euros.

{{< figura src="/images/numero-19/Figura%2002_A_capitales.jpg" caption="Figure 2. Capital insured for property (residential, commercial, industrial, infrastructure and motor vehicles) by regional autonomy as of 31 December 2022." source="URA" >}}

As for claims incurred on account of the natural causes under consideration (flooding, coastal flood, windstorm and geological causes), the annual average for compensation paid out over the period of 1996-2022 is depicted in Figure 3. There is a palpable two-fold reliance on, firstly, exposure (there are more compensation pay-outs in the larger municipalities such as Barcelona, Madrid and Valencia) and, secondly, the hazard level (which is the case in Lorca, for example), although, broadly speaking, in those municipalities which stand out in terms of total compensation (such as Malaga, San Sebastián, Murcia and Córdoba) it is the blend of both factors which is responsible for the high annual average compensation paid out.

{{< figura src="/images/numero-19/Figura%2003_M_cnat_indemni.jpg" caption="Figure 3. Annual average compensation paid out per municipality due to the natural causes considered in the study (flood, coastal flood, atypical cyclonic storms, earthquakes, tsunamis, and volcanic eruptions)." source="" >}}

To avoid the distortion which zones with high exposure (sums insured) produce, from now on we will perform our analysis at municipal level on the basis of the division of the annual average for yearly compensation pay-outs by the annual exposure for 2022, which will give us a loss ratio in euros paid out per year and municipality for every million euros insured in it. We are aware that we are comparing average insured loss over 27 years with exposure for one particular specific year (2022). It is patent that, given that the exposure level over this period has tripled, the loss must have exhibited a similar pattern (which can be seen from the aggregated total of losses). In other words, we are under-representing the earlier claim events and this may impact the final conclusions, although it is also true that the growth occurred very rapidly in 1996-2010, when the total sum insured swelled (in terms of constant euro levels for 2022) from 2.24 trillion to 5.41 trillion. From 2011 to 2022, when the total sum insured reached 6.46 trillion euros, growth slackened, which is why exposure in major loss events such as the 2011 Lorca earthquake or the cut-off lows in 2012 or 2019, can be thought of as being relatively stable. In regard to totals, 51% of overall losses (remembering here that this is in constant euros) were caused in these last 12 years out of the total for the 27 years under review in the study.

### Extraordinary floods (fluvial and pluvial flooding)
Figure 4 shows the annual average amount paid out in compensation in euros per million euros insured by municipal district on account of fluvial and pluvial flooding, which reflects a loss ratio that is relatively independent from cumulative exposure. The zones with higher loss ratios per flood are generally located along the coastline, in the central sections of the Guadalquivir, Ebro and Guadiana, and in the populated mid-mountain areas.

{{< figura src="/images/numero-19/Figura%2004_M_inun_tasa.jpg" caption="Figure 4. Loss ratio (average annual loss in euros / sum insured in millions of euros) by reason of extraordinary flooding per municipal district." source="" >}}

More precisely, the eastern, Mediterranean coast from Cape Gata to the Ebro Delta, together with certain areas of the Sierra de Tramuntana and the 'Llevant' of Majorca, as well as the Costa Brava, exhibit high or very high loss ratios. In certain zones, such as the Guadalentín valley, the Lower Segura or the Mar Menor basin, these rates are extraordinarily high.

Along the northern coast, the highest loss ratios are concentrated on Galicia’s 'Rías Bajas’ (southern half of the coastline) and the central and eastern Bay of Biscay coastline. As regards the valleys of the major rivers, there are very high loss ratios at certain points of the Ebro Axis and its main tributaries, such as the Arga or the Aragón, as well as along the Córdoba-Seville section of the Guadalquivir and in the Badajoz section of the Guadiana.

An interesting characteristic has become evident in the mid-mountain areas where there is a significant population, both in the Cantabrian range (especially on the southern side), the foothills of the Pyrenees in Navarre, the Catalan coastal ranges, as well as in Sierra Morena and the Baetic and Penibaetic systems (particularly in Malaga province). There are municipalities with high loss ratios, and some very high, while others are occasionally anomalously high, as a result of floods occurring along short river courses which with only a very brief response time in highly built floodplains. This is the same process present in the areas neighbouring the Strait of Gibraltar and generally speaking in all the coastal zones reported above.

In regard to the Canary Islands, the northern tip of Tenerife presents very high loss ratios and the loss ratio is substantial in the south-west of Gran Canaria and that of Fuerteventura.

{{< figura src="/images/numero-19/Figura%2005_M_inun_estacion.jpg" caption="Figure 5. Seasonality of greatest frequency of flood losses by municipality." source="" >}}

The seasonality of the danger of flooding is illustrated in Figure 5. The map does not show the season of the year when it rains most but rather the season when CCS logs the most flood claims, which do not necessarily coincide. The biggest losses from flooding in autumn are concentrated along the entire Mediterranean coastline and the Balearic Islands, although they are also present in other zones such as in Andalusia between Córdoba and Malaga and the west of Extremadura. There is no doubt that the effects of cut-off lows clearly play a leading role in this geographical make-up.

The winter highs occur in areas exposed to Atlantic flows and result from the passing through of low-pressure systems in that particular season: Galicia, the Cantabrian mountain range, particularly on its southern side, the Central System, the Montes de Toledo, the Sierra Morena and large swathes of the Guadalquivir basin and the zone around the Strait, including the basins of the major rivers in Malaga. These flows, which generally run from the west or the south-west, see build-ups from huge rainfalls in these directions, which translate into floods and losses.

The spring is normally the season when there are less flooding (and here we wish to stress the difference between greater cumulative rainfall and the heavier downpours, which is what gives rise to flooding). Spring floods only predominate in scattered inland areas.

Summer highs appear in zones within the interior such as the Madrid Region, the Iberian system and also (which is something that is less intuitive) in the Central Pyrenees and along the Bay of Biscay coastline. Once again, there is a significant difference between the cumulative amount of rainfall, which, for example, is greater in winter on the Bay of Biscay coast, and very heavy downpours in only a short space of time, that are convectional in origin, and cause damage.

### Coastal flooding
Interpretation of the regulations on extraordinary risks yields a definition of coastal flood as flooding of land caused by the sea or estuaries, or else by the action of sea swells that affects items located on otherwise dry land. The total amount of loss or damage on account of coastal flooding is not very considerable compared to that caused by extraordinary flooding (it is in the region of 4% of the former) yet we can draw some interesting conclusions from geographical representation of such floods, which is given in Figure 6. The loss ratios (here we should recall that we are not discussing outright loss or damage, but rather loss or damage arising relative to exposure) are highest in the Bay of Biscay and on the Costa Brava. They generally tend to be greatest along the east Bay of Biscay area, where municipalities such as Bermeo (Biscay) have substantial loss ratios, and next to the Mediterranean to the north of Cape Nao, where certain municipalities such as Colera and Portbou in Girona present notable loss ratios. The same occurs in Sant Adriá de Besós (Barcelona), Peñíscola (Castellón) and Escorca and Santa Margalida in Majorca.

That said, the highest loss ratios attributable to coastal flood emerge in the Canary Islands, where Valverde (on El Hierro) and Garachico (on Tenerife) record the highs. In this case they usually relate to episodes involving swells with large-scale surges which engage with favourable exposures in the archipelago.

{{< figura src="/images/numero-19/Figura%2006_M_embate_tasa.jpg" caption="Figure 6. Loss ratio due to coastal flood by municipality." source="" >}}

The seasonality of loss or damage from coastal flood is illustrated in Figure 7. Normally this phenomenon is most frequent in winter on the Galician and Bay of Biscay coasts, as well as in Catalonia and the Canary Islands. The spring highs are notable on the Andalusian shoreline and in autumn along a sizeable portion of the Eastern coast (although the province of Alicante and some areas in that of northern Valencia exhibit winter highs, as does northern Ibiza, western Majorca and Ciutadella and Maó on Minorca).

{{< figura src="/images/numero-19/Figura%2007_M_embate_estacion.jpg" caption="Figure 7. Seasonality of greatest frequency of loss from coastal flood by municipality." source="" >}}

### Atypical cyclonic storms (strong windstorms)
CCS pays out compensation for loss or damage from very strong wind events when these involve gusts assailing a municipality of over 120 km/h in three seconds or present in the form of a tornado. These coverage thresholds were determined in 2011, for which reason the data series we examine in this section relates to the period running for the full years from 2012 to 2022, when these criteria were upheld. From 1996 to 2011 two different thresholds and coverage criteria were applied (see the article by Vilares and Asensio in edition 16 of this digital magazine), with the coverages used by CCS steadily becoming more and more extensive, which means that these are not comparable periods and we are leaving them out of this part of our study.

{{< figura src="/images/numero-19/Figura%2008_M_tca_tasa.jpg" caption="Figure 8. Loss ratio for atypical cyclonic storms by municipality." source="" >}}

Figure 8 makes it clearly noticeable that loss ratios on account of this hazard are higher in very particular areas: Galicia and the west Bay of Biscay portion, as well as the Cantabrian mountain range, with high loss ratio zones extending along the Iberian and Central system, albeit in a more isolated way, as well as the more easterly section of the Baetic and Penibaetic system, with the Balearic Islands included here. Other mountainous areas, such as the Catalan coastal ranges and, in a more isolated manner, the Pyrenees, also show relatively high loss ratios. On the Canary Islands the higher loss ratios occur among the more westerly islands, particularly in zones more open to the northwest. In flat areas, for example in the Ebro valley or points on the Southern Plateau or even in the Guadalquivir valley, points with high loss ratios can also be found, although one or two of them can be due to specific episodes which affect high-value facilities or premises, such as wind farms or other power and industrial installations, which can produce very high relative losses compared to the low exposure in their municipalities.

This is the hazard with the most marked seasonality. Figure 9 shows that in general wind loss takes place in winter as a result of high-impact, low-pressure storms passing through or cyclone formation processes, save for the case of very specific zones, for example in the centre and south of the Madrid Region and the Ebro Axis, where wind loss or damage is linked to summertime convectional processes. In other, more scattered zones in the southern third wind loss most frequently happens in autumn and is associated with the presence of cut-off lows.

{{< figura src="/images/numero-19/Figura%2009_M_tca_estacion.jpg" caption="Figure 9. Seasonality of greatest frequency of loss or damage from atypical cyclonic storms by municipality." source="" >}}

### Geological hazards
The geological hazards covered under extraordinary risk insurance are earthquakes (the most common), tsunamis (in the period under review only one has been compensated, where the loss was minimal, in 2003) and volcanic eruptions, which likewise only led to compensation on a single occasion with the eruption on the Cumbre Vieja massif on La Palma of 2021. It makes no sense to speak of seasonality with these hazards, although we can actually offer a geographical representation of the loss ratio, with the evident distortions caused by the two episodes of greatest significance and losses: the Lorca earthquake in 2011 and the cited eruption on La Palma, as shown in Figure 10.

{{< figura src="/images/numero-19/Figura%2010_M_geolo_tasa.jpg" caption="Figure 10. Loss ratio for geological hazards by municipality." source="" >}}

Obviously, the highest ratios on account of earthquakes are concentrated in the south-west of Murcia region, which was hit by the Lorca earthquake on 11 May 2011, though also by others such as in Mula in 1999 or La Paca in 2002. Other zones where we can note significant seismic claims incurred include the Granada Plain, which was affected by the earthquake swarm of 2021, the autonomous city of Melilla, where there was a major event in 2016, or other zones less severely impacted but involving relative frequency, such as the northern third of Navarre, El Ripollés in Girona or the Becerreá-Ancares region in Lugo.

The volcanic eruption at Cumbre Vieja on La Palma left its mark in terms of extremely high loss ratios in the municipalities of El Paso, Los Llanos de Aridane and Tazacorte, which were directly affected by the eruption, though also on account of the rest of the municipalities in the southerly two-thirds of the island, which were impacted by ash and tremors that related to the eruption process.

### Maximum frequency of hazards by municipality
The concept of compensation falls within the philosophy of extraordinary risk insurance, and this appears in the name of our institution, across various different hazards which manifest themselves to a greater or lesser extent in several different geographical areas. Figure 11 shows which hazard has caused the most loss over the period under review in each municipality. As with all the loss compensated by CCS, where flooding represents two out of every three euros paid out, in terms of geographical representation it is flooding which predominates over large swathes of Spanish soil. It is possibly more time-effective to pinpoint the zones where other hazards (among those examined in this study) are those which give rise to proportionately more loss or damage.

{{< figura src="/images/numero-19/Figura%2011_M_causaprin.jpg" caption="Figure 11. Classification of most losses per municipality according to the hazards considered within this study." source="" >}}

Wind predominates in virtually the whole of Galicia and the western portion of Asturias and León. It also prevails in the arc of municipalities which spans the Central and Iberian system and the Cantabrian mountain range, as well as in a sizeable part of the Pyrenean municipalities and the coastal Catalan ranges. Wind loss also predominates in Majorca, the eastern-most Baetic systems and the island of Tenerife, as well as in certain zones of the west and central Southern Plateau. Coastal flood is the most costly hazard on La Gomera and El Hierro, as well as in isolated municipalities on the Catalan, Basque and Bay of Biscay shoreline.

Geological hazards predominate in south-west Murcia, the Granada Plain, Melilla and the island of La Palma, yet also in certain municipalities in La Mancha and the aforementioned Pyrenean and Pyrenean foothill zones, as well as in certain points in the west of the provinces of Zamora and Cáceres.

{{< figura src="/images/numero-19/Figura%2012_P_causaprin.jpg" caption="Figure 12. Most loss by province and proportionate distribution of them included in the period under review." source="" >}}

This information can be expressed in synthesis at provincial level in Figure 12, where it can be seen that, in the vast majority of provinces, it is flooding which is the extraordinary risk which brings about the most loss, except for in La Coruña, Lugo, Orense, Burgos, Álava, Segovia and Soria, which suffer most from wind events, and Murcia, Santa Cruz de Tenerife and the autonomous city of Melilla, where the most losses were produced in the period under review by geological hazards.

{{< destacado-rojo >}}

### Conclusions
Based on purely economic data, sums insured and compensation paid out in relation to extraordinary risks for hazards that are natural in origin and considered herein, we have managed to extricate certain characteristics that relate to atmospheric processes and their seasonality or to geological processes, which reveals the immense importance of the flow of data which CCS stores in the context of its insurance functions as a basis for performing another of them, namely providing valuable greater insight into risks covered with a view to minimising them.

This knowledge is most important, if you will, in the context of the climate crisis in which we must act with greater diligence to reduce the vulnerability of property that is exposed to a hazard that is increasing.

{{< /destacado-rojo >}}

## Acknowledgements
Thanks to the Technical and Reinsurance Directorate of the CCS, which compiled, refined and prepared the baseline data for this study.

{{< referencias >}}
Consorcio de Compensación de Seguros, CCS (2023), Estimación de los capitales asegurados en daños a los bienes por código postal y clase de riesgo. Dataset. https://www.consorseguros.es/ambitos-de-actividad/seguros-de-riesgos-extraordinarios/mas-informacion/estadistica [Accessed 01/12/2023].

Consorcio de Compensación de Seguros, CCS (2023), Información sobre las indemnizaciones. Tramitaciones de RREE abiertas a 31-12-2022. [Accessed 01/12/2023].

Correos, Capa cartográfica de indicadores. Version April 2023. MAPA_CP_31_03_2023_CON_INDICADORES.shp [Accessed 01/12/2023].

Instituto Geográfico Nacional. Provincias. Información geográfica de referencia. Límites municipales, provinciales y autonómicos. Límites y unidades administrativas. Date 01/12/2023. CNIG Download Centre. https://centrodedescargas.cnig.es/CentroDescargas/buscadorCatalogo.do?codFamilia=02131.

Ministry for the Ecological Transition and the Demographic Challenge. Demarcaciones hidrográficas. Demarcaciones hidrográficas (ámbitos terrestre y marino). Period January 2022. Shapefile format. INSPIRE Download Service https://www.mapama.gob.es/app/descargas/descargafichero.aspx?f=Demarcaciones_a_terrestre_marino.zip [Accessed 01/12/2023].

Ministry for the Ecological Transition and the Demographic Challenge. Límites cartográficos de las confederaciones hidrográficas. INSPIRE Download Service. https://www.mapama.gob.es/app/descargas/descargafichero.aspx?f=limites_cartograficos_de_las_confederaciones_hidrograficas.zip [Accessed 01/12/2023].

Sereno, A. (2009). La información geográfica en España: especial referencia a la cartografía catastral, CT Catastro 67, 50. http://www.catastro.minhap.gob.es/documentos/publicaciones/ct/ct67/3.pdf
{{< /referencias >}}