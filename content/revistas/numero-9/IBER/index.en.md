---
title: "The IBER model and its application to flood studying"
category: "Análisis"
pdf_download: "/pdf/num22/editorial.pdf"
sidebar_image: "/images/numero-9/foto_portada09_IBER.png"
sidebar_text: "Iber has options for feeding in various different kinds of initial conditions and inflow and outflow boundary conditions. It has tools to automatically assign channel roughness and also features configuration options for internal boundary conditions to define spillways, sluices, bridges, drains or covered sections of channel. Post-processing consists of viewing the results in a way that makes them easy to interpret, for which purpose displays can be made using colours, level curves, labels, vectors, graphics, animations, etc."
weight: 4
image: "/images/numero-9/foto_portada09_IBER.png"
summary: "In episodes of flooding, the most important variables for assessing flood risks are the velocity and level reached by the water, as well as how long it remains there. There are several ways of assessing the risk associated with a river flooding event as a function of these parameters."
authors:
    - name: "David López Gómez"
      institution: "PhD in Civil Engineering. Centre for Hydrographic Studies, CEDEX"
    - name: "Juan J. Rebollo Cillán"
      institution: "PhD in Civil Engineering. Centre for Hydrographic Studies, CEDEX"
---
During river floods, the volume of water passing through the water course increases to the point where it overflows its main channel and encroaches onto flood plains. While the flow of water remains confined to the main channel, one-dimensional models manage to describe the movement of the water sufficiently well, meaning that they allow us to know the depth and velocity of the water over the river’s main course; yet after the waters have encroached onto the flood plains, the flow becomes two-dimensional, which implies that the direction of the water no longer follows the course of the main channel and can instead move in any direction depending on the topography and any obstacles which overflows find in their path, which means that flood events should be analysed using two-dimensional models.

{{< figura src="/images/numero-9/IBER_Guadalhorce1.png" caption="" source="" >}}

The Iber model, which takes its name from the Latin root for the river Ebro, in turn lending its name to the Iberian peninsula, has been developed by Spanish institutions spread across various different points of Spain’s geography: specifically, the Polytechnic University of Catalonia, the University of A Coruña, the International Centre for Numerical Methods in Engineering (CIMNE) and the Centre for Studies and Experimentation of Public Works (CEDEX), with funding from the Directorate General for Water.

One of the advantages of the Iber model is that it is a freely downloadable software, which has facilitated its use by both consulting firms and public administrations, thus smoothing interaction among the various different actors involved. This software has also been popular throughout academia, with a large number of users in Europe and Latin America. This has been helped by the fact that it can be configured to run in Spanish or English.

The executable installation files can be downloaded from the website at www.iberaula.es (opens in a new window), where instructional material can also be found, featuring manuals, examples and tutorial videos, which can prove very useful for learning purposes. There is also quite an active forum where you can post queries and make contributions. Information on both attended and online courses can be also found.

The Iber numerical engine is the FORTRAN F90 code, which solves 2D depth-integrated Navier Stokes equations for shallow waters, known as Saint Venant or 2D shallow water equations, with turbulent closure equations and in a variable system. To solve these equations the numerical finite volume method is used. Iber uses an explicit upwind-type numerical scheme. Of the various different numerical schemes that exist, this is the one which is best-suited to two-dimensional flows on a free surface, as it can solve wave front and system change problems without calculation devices.

Iber has tools that allow models to be generated and results to be analysed within the same computer application. We could say that Iber is encapsulated within the GiD graphics environment (www.gidhome.com (opens in a new window)), which offers pre-processing and post-processing utilities. GiD has been developed to define and prepare the data that makes up a numerical simulation, as well as to visualise the results of this. Data creation implies defining the geometry of the problem and assigning the information to the geometry that is required to generate the internal files which Iber’s numerical engine needs for execution. GiD has a CAD engine that enables new geometries to be created or imported from other CAD systems for subsequent fitting. The program also makes it possible to generate a grid and transfer the data associated with their geometry.

All calculations are carried out on a three-dimensional grid that reproduces the geometry of the watercourse. The elements of the grid serve to define the finite volumes upon which calculation is performed. Iber can calculate in relation to structured and unstructured mesh elements, be they triangular or quadrilateral in shape.

{{< figura src="/images/numero-9/IBER_Mogon.png" caption="" source="" >}}

Iber has options for feeding in various different kinds of initial conditions and inflow and outflow boundary conditions. It has tools to automatically assign channel roughness and also features configuration options for internal boundary conditions to define spillways, sluices, bridges, drains or covered sections of channel.

Post-processing consists of viewing the results in a way that makes them easy to interpret, for which purpose displays can be made using colours, level curves, labels, vectors, graphics, animations, etc.

In the episodes of the flooding the most important variables for assessing flood risks are the velocity and level reached by the water and how long it remains there. There are several ways of assessing the risk associated with a river flooding event as a function of these parameters. Iber can zone flood risk pursuant to Spanish national regulations, Catalonian regional regulations or any others that we might wish to implement using the personalised classification option. Additionally, Iber has utilities that enable raster mapping using these results, which can be exported to geographic information systems (GIS). This makes it possible to cross risk maps with land uses to be in a position to assess the flood damage caused, which means we have a tool available to perform an economic assessment of damage done.

Although hydrodynamics plays a key role in a flooding process, there are other phenomena that affect the flow in channels, such as sediment transport or tree-trunks being carried along. Iber has different modules to cater for studies of this kind. The sediment transport module deals with two types of phenomena: on the one hand, bed load, featuring soil and gravel dragged along, which greatly influences the geometry of the bed of the main channel, then on the other hand, the transport of suspended solids, which focusses on shifting of fine matter (clay and silt) which also moves over flood plains. Iber has different formulations which allow analysis of any alteration over time of river and reservoir beds.

Recently a new rainfall model has been added which enables study of rainfall run-off in basins so that, for a given rainfall scenario, we can calculate what volume of water reaches courses and then study floodability.

The participation of universities in the Iber project makes it highly dynamic, since it means that new developments can come on board that derive from research projects or doctoral theses and which both represent improvements on and increase calculation capabilities and fields where the model can be applied.

Although Iber’s numerical code has been optimised, using certain modules, such as those on sediment transport or rainfall, requires very considerable execution times. Work is currently being carried out on developing a version of the code for supercomputing based on graphics cards. This will allow calculation times to be considerably reduced and larger-scale studies to be taken on.

Among modules in the development pipeline, an urban hydrology module is due out soon that will enable simulations where drainage networks can be added, which will in turn make it possible to simulate loading processes in piping of this kind and the flow of surface run-off.