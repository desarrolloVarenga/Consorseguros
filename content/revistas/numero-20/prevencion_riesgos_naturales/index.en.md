---
title: "Artificial Intelligence in Preventing Natural Perils"
category: "Contributions"
pdf_download: "/pdf/num22/editorial.pdf"
sidebar_image: "/images/numero-20/foto_portada_IA_prevencion_riesgos_naturales.jpg"
sidebar_text: "Tesicnor's NOE application makes it possible to digitise and speed up implementation of municipal disaster planning. In case of an emergency, the system provides real-time directions concerning the prevention tasks that need to be carried out and their status (not started, in progress, completed). Since it is a dynamic tool, the contact telephone numbers of the people in charge can be quickly and easily updated and new functionalities, such as sending automated SMS alerts and early flood warnings out to the public using AI, can be added."
weight: 6
image: "/images/numero-20/foto_portada_IA_prevencion_riesgos_naturales.jpg"
summary: "Natural disasters have occurred throughout history and have forced societies to adapt, prepare, and evolve, carrying mankind to its current level of safety and development. While development has brought us greater protection from hazards, it seems that society often forgets that events like these even exist and are a real possibility. They only come to mind when they actually occur."
authors:
    - name: "Marcos García Muñoz"
      institution: "Artificial intelligence developer"
    - name: "Iñaki Pérez del Notario López"
      institution: "Doctoral Candidate, Industrial Science and Technology"
    - institution: "TESICNOR"
---


### Introduction
Natural disasters have occurred throughout history and have forced societies to adapt, prepare, and evolve, carrying mankind to its current level of safety and development. While development has brought us greater protection from hazards, it seems that society often forgets that events like these even exist and are a real possibility. They only come to mind when they actually occur.

At the same time, technological progress has also driven human development, from the invention of the wheel to the recent advent of artificial intelligence. These technological advances have led humankind to become a highly interconnected technological society with unlimited potential to innovate and solve complex problems.

At first glance it may appear that these paths run parallel, but the two branches converge at a number of points. At Tesicnor’s Disaster Risk Reduction (DRR) Department our vision is to put the most innovative commercially available technologies to use for protection and risk mitigation, and advancing personal safety is our cornerstone. This contribution discusses the research and development work currently under way, basically on artificial intelligence (AI), and how we think these advances will help reduce the impact of natural disasters on the population and the natural environment.

### Natural disasters
#### Formal definition of a natural disaster
Natural disasters are destructive phenomena that cause severe impacts within a short span of time. Some examples of natural disasters are floods, the spread of wildfires due to combustion reactions, cyclones and tornadoes, earthquakes, and so on.

#### Natural disasters in Spain
In environmental terms, floods and wildfires are the most frequent and most damaging natural disasters in Spain. Other events like earthquakes and cyclones are much less common compared to other countries.

With regard to wildfires, Spain is one of the countries with the largest expanse of forested land in the European Union and carefully addressing this risk is therefore critical.

From an insurance industry perspective, flooding is the most frequent and problematical natural disaster. Earthquakes and cyclones, though as a rule less common, are capable of causing great damage unexpectedly.

#### Consequences
Natural disasters are a source of damage both to inhabited areas and to ecosystems. Their economic impact is high, and recovery is slow and takes a lot of work.

Investing resources in reducing or preventing the repercussions of these events translates into major economic savings in the long term. This is a premise that is readily understandable in theory, yet in practice it is hard to drive this point home to people and to the authorities unless these events occur often enough to impact them directly, as is the case, for instance, of earthquakes in countries like Japan.

### AI basics
Today the field of artificial intelligence has myriad applications and is much in vogue. One way AI can be used is to mitigate the consequences of natural disasters through early warnings. There is much talk about AI technology right now, often without much basis and with considerable fearmongering or overdramatisation. Let us therefore provide a formal definition of artificial intelligence and consider its benefits in the world of natural disaster risk reduction.

#### Definition of AI
Our underlying assumption is that the internal functioning of machines is extremely simple and that they are only capable of performing simple mathematical operations like adding and subtracting. Artificial intelligence is a field in computing and mathematics whose aim is to make a machine able to perform tasks that require a certain degree of human intelligence. Some examples are recognising objects in photographs, detecting faulty products in production chains, identifying email spam, predicting how a company’s shares will perform on the stock market, etc.

Data are AI’s source of learning. It might intuitively seem that training a machine to write first requires providing it with an explanation of the grammatical rules of language and word meanings in great detail. What is actually done, however, is to expose the machine to large numbers of texts so that it learns the context of words and language grammar rules itself through trial and error. In AI, this process is termed «machine learning».

The process of making a machine capable of learning is carried out through systems of mathematical equations termed «AI models». What the concept of training means is that the machine tries to fit the model’s mathematical equations to minimise an error function. For instance, the error in an AI model designed to predict car prices based on vehicle characteristics would be the difference between the actual price and the prediction made by the model.

The main advantage of AI over other alternatives is that once a machine has learned to perform a task, it can be put to work 24 hours a day and used to simplify tasks that would otherwise be tiresome and require human involvement.

#### Neural networks
AI models based on neural networks are the most successful models at the present time. Their logic is based on how neurons work in the brain.

Biologically speaking, neurons in the brain are structures made up of interconnected cells that use electrical impulses to communicate with each other. A neuron receives impulses from multiple other neurons through its dendrites, interprets them, and transmits another impulse through the axon to other neurons. Neurons have rather complex internal learning mechanisms and all together make up a system that has enabled us to reach quite a high level of advanced intelligence. Trivial abilities like communicating, distinguishing objects that we see, interpreting sounds, taking decisions, etc. all have a very high degree of both sensory and learning complexity.

The notion of an artificial neuron is a much simplified model of a biological neuron. It can be considered a node interconnected to other nodes using input and output connections. The node receives numerical values output by other nodes through each of its input connections. These values are used internally to calculate the result of a simple mathematical equation learned individually by each of the nodes. The result of the equation is then transmitted to other nodes through its output connections.

This simple concept is the basis for creating more complex neural structures by interconnecting large numbers of nodes. The learning ability of artificial neural networks is what enables AI models to learn. These models can be used in a wide range of applications, such as text and image recognition and generation, biometrics, help in medical decision-making, protein folding, etc.

#### Comparison of AI and physical models
Forecasting in meteorology and hydrology entails making predictions by running numerical simulations using physical equations to try to estimate future changes in certain variables by simulating interactions between the variables over time. One example of this is the Harmonie-Arome weather forecasting model that meteorological services like Spain’s National Meteorological Agency ({{< tooltip text="AEMET" num="1" url="" >}}
Agencia Estatal de Meteorología.
{{< /tooltip >}}) use to make weather forecasts. These models provide large quantities of information for decision-making in a slew of different areas. The drawback attached to these models is that they require large amounts of computing power to be able to make forecasts within a reasonable time frame.

Applying AI to this field enables learning by systems of simpler equations that can be run in just a short time while maintaining reasonable levels of accuracy. This in turn allows forecasts to be updated continuously based on the most recent data, yielding highly detailed short-term forecasts (0-6 hours). 

Ease of specialisation is another advantage: if we want to use AI specifically to detect adverse weather phenomena, a specialised model can be trained to learn patterns that give rise to events of that kind, even though this means that the model may be worse at general purpose modelling.

### Digitisation - The NOE Tool
#### Digitisation of municipal disaster planning
Natural risks, floods in particular, require careful planning to minimise damage and coordinate effective responses. Current legislation requires cities and towns to draw up and implement action plans to combat flooding. Nevertheless, the complexity and length of these plans can make it hard to actually put them into practice quickly in the face of an emergency.

Tesicnor’s NOE application makes it possible to digitise and speed up implementation of municipal disaster planning. In case of an emergency, the system provides real-time directions concerning the prevention tasks that need to be carried out and their status (not started, in progress, completed). Since it is a dynamic tool, the contact telephone numbers of the people in charge can be quickly and easily updated and new functionalities, such as sending automated SMS alerts and early flood warnings out to the public using AI, can be added.

{{< figura src="/images/numero-20/IA_prevencion_riesgos_naturales_1.png" caption="Figure 1. NOE tool flood management and alert functionality chart." source="Prepared by the authors." >}}

#### Real-time data collection and AI-based early warning
The most novel of NOE’s various functionalities is the inclusion of an early warning system for floods that works by collecting meteorological and hydrological data from river stations in real time and implementing an AI model to predict changes in the river in the next 6-12 hours. If the model detects a flood threat, NOE automatically notifies the people in charge in the urban areas concerned and in the worst case Spain’s emergency services number, 112. Ultimately, it will be those people who decide whether or not to declare an emergency.

There are plans to enhance and expand this function by adding early warnings for disasters of other kinds and improving existing levels of reliability.

### Early flood warning by applied AI
Floods are a type of natural disaster that involves an excessive accumulation of water in typically dry areas. We are referring chiefly to places where human activity is commonplace, e.g., cities, towns, farmland, roads, campgrounds, and so forth. The two main causes of floods are rivers overflowing their banks (fluvial flooding) and localised heavy rainfall (pluvial flooding). Tsunamis, storm surges, and dam failures are other less frequent causes.

#### Effects of climate change
Climate change acts to increase the frequency and intensity of extreme weather events, such as the intensity of precipitation, rising sea levels, and abrupt changes in temperature that contribute to the accumulation and melting of snow in mountainous areas, leading to sudden surges in river water levels.

#### Fluvial flooding (predicting river flow volumes)
River floods are a type of flooding that occurs when river water levels rise until they spill over into anthropized areas along a river’s course. They can be caused by protracted heavy rainfall that ends up saturating the ground’s capacity to absorb the water or by sudden melting of large masses of snow in the mountains. They tend to be frequent in the winter months and can be predicted with relative ease compared to pluvial floods.

Early warnings focus on predicting when a flood is going to occur in an urban area so that the inhabitants can be alerted. Hydrological models like those employed by basin management authorities have traditionally been used, but AI is producing more accurate short-term predictions (0-12 hours, depending on the river) that can be updated in real time.

{{< figura src="/images/numero-20/IA_prevencion_riesgos_naturales_2.png" caption="Figure 2. Plot of AI model Arga River flow rate predictions." source="Prepared by the authors." >}}

The NOE tool provides AI-based warnings for urban areas at risk of flooding.

#### Pluvial flooding (radar prediction)
Pluvial floods are another type of flooding caused by very heavy rainfall in a very short time, when the volume of water that falls is so high that it cannot be absorbed, not even by dry ground. This type of rainfall event is frequent in the summertime, and predictability tends to be a complicated affair. The goal of early warnings is to detect the occurrence of heavy rains potentially capable of causing flooding in an urban area. 

Thanks to its high computational efficiency, implementing an AI approach can improve short-term predictions (0-6 hours) of heavy storms, enabling forecasts to be made within very short time frames using the most up-to-date data.

Research on several different techniques is under way in order to predict the behaviour of intense rainfall, e.g., seeking to replicate how physical models work by replacing physical equations with other more efficient equations optimised by AI. However, one of the methods that is working the best is using neural networks to predict motion in radar images.

{{< figura src="/images/numero-20/IA_prevencion_riesgos_naturales_3.png" caption="Figure 3. Example of radar image-based nowcasting using an AI model." source="Prepared by the authors." >}}

Radar images provide very high spatial and temporal resolution (1 km² per pixel every 10 minutes), so they contain quite a high level of detail. However, they also have a drawback, namely, the signal scatters with distance from the radar, which can give rise to false echoes from flocks of birds and other sorts of interference.

To address this problem, AI models can be trained to try to identify false echoes and to act as a filter for the images themselves. To overcome the problem of scattering in areas at a distance from the radar, AEMET uses image interpolation methods to combine readings taken by different radars and in that way to some extent correct for the problem posed by scattering.

The AI model is fed a sequence of past images and uses them to generate another sequence of images and forecast images to follow. Thanks to the research in progress on AI image generation, advances are constantly being made in this field.

### Drones
Drones are another emerging technology that can be used in flood damage prevention and assessment. These unmanned aerial vehicles are an alternative means of reconnoitring affected areas without the high costs and risks associated with helicopter flights. Using automated drones allows safer, more economical surveillance and eliminates the need for specialised personnel on the ground. This technology affords a broader, more detailed view of the event that would be hard to obtain from the ground alone.

{{< figura src="/images/numero-20/IA_prevencion_riesgos_naturales_4.png" caption="Figure 4. Maintenance flight over the Cidacos River (Tafalla, Spain)." source="EMERAL Project." >}}

Using drones during emergencies would be optimal, but there are numerous legal restrictions preventing this from taking place. Hopefully, the legislation will grow more permissive for situations in which drones are being used not for recreation but to help mitigate the impact of natural disasters.

### Wildfires
Wildfires are a type of natural disaster in which fire burns out of control over large swathes of woodland, causing damage to the flora and the fauna, and recovery can take decades. 

They can originate from natural causes, like lightning strikes, or from human-made causes, like negligence or being set intentionally. Most are caused by human activities, so making predictions is particularly problematical compared with other causes, such as lightning strikes. Although lightning strikes are a less common cause, it is important not to overlook them, because they are capable of starting fires in hard-to-reach, uninhabited areas, where the fires can be hard to put out.

When trying to prevent these events, it needs to be borne in mind that the place where a fire is going to break out is not foreseeable in advance, making early warnings more complicated than for floods. The approach taken is to help prioritise fire surveillance in locations that are particularly vulnerable on account of weather and land conditions and to create firebreaks or other land features to help prevent potential fires from spreading.

#### Effects of climate change and rural depopulation
The effects of climate change increase the frequency and intensity of droughts, making the land drier and more likely to catch fire.

The depopulation of rural areas is another of the main causes of heightened risk of fire. With fewer people working the land, important maintenance tasks like clearing away overgrowth that can feed wildfires and creating firebreaks to keep fires from spreading are neglected.

Three different approaches are used when applying artificial intelligence to reduce the risk of wildfires:

1. Predicting areas at risk.
2. Using computer vision to detect fires that have just broken out.
3. Predicting how a fire that has already started will spread.

The first approach involves using extremely high resolution to estimate the level of fire risk in a geographic area in real time on the basis of weather and terrain conditions. This makes it possible to prioritise fire watching and to take preventive measures in especially vulnerable locations. In these cases AI uses historical data on past events as a basis for learning. These data can also include data on proximity to inhabited areas and the degree of forest use, since human activities tend to be the cause of most wildfires.

{{< figura src="/images/numero-20/IA_prevencion_riesgos_naturales_5.png" caption="Figure 5. Example of a map of Navarre showing the risk of wildfires in summer." source="Fire-Alert Project." >}}

The second approach involves dynamically monitoring the condition of the countryside to detect fires that break out as soon as possible. One widely used method entails installing camera systems at elevation to monitor the countryside and using automated computer vision systems to detect smoke clouds that could come from fires that have recently started. Thus, surveillance is kept up 24 hours a day, improving the response by emergency services and reducing the chance that a fire will burn out of control. This method is now being used in California, in the United States of America, to good effect, although responding to fires can encounter serious difficulties because of densely overgrown vegetation.

{{< figura src="/images/numero-20/IA_prevencion_riesgos_naturales_6.png" caption="Figure 6. Smoke recognition by computer vision." source="Results of smoke detection by a proprietary Tesicnor model from images in a dataset compiled by the Center For Wildfire Research, University of Split, Croatia." >}}

The third approach involves developing tools to help put out fires. The most widely used method is to employ simulators to estimate where the fire is likely to spread to assist in taking strategic fire-fighting decisions. Some researchers are studying the use of AI-controlled drones in operational fire-fighting to reconnoitre affected areas and even using drones equipped with water hoses to help extinguish fires from above. The main benefits of these drones are that they can get up close to the fire without putting anyone’s life at risk while being much less expensive than operating a helicopter.

{{< destacado-rojo >}}

### Conclusions
The field of disaster risk reduction is becoming more and more important to society because of the increased likelihood of adverse weather events as a result of climate change and the depopulation of rural areas.

AI technology development, research, and applications are experiencing exponential growth in industry, enabling many processes to be automated and at the same time tackling problems that could not be dealt with otherwise. Its implementation in disaster risk reduction is improving the precision and scope of systems for giving the public early warnings, enhancing surveillance in areas at risk, and helping in digitising emergency procedures.

The development of AI in this field holds out great promise. In the future the techniques discussed in this article will be refined, and new approaches with solutions for as yet unsolved problems will emerge.

{{< /destacado-rojo >}}