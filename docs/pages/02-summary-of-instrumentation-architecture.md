---
layout: page
title: Summary of instrumentation architecture
permalink: /02-summary-of-instrumentation-architecture/
---

The technical design of the instrumentation system is made up of multiple components:
* an instrumentation client which observes behaviour on the users’ computer
* a front-end microservice that records the information
* a back-end microservice that processes the data into a form that is easier to analyse
* an analysis back-end that allows analysis of the data to answer user experience questions.

The overall pipeline is shown in the figure below:

[![](/Coulomb/assets/instrumentation_pipeline.png)](/Coulomb/assets/instrumentation_pipeline.png)


**TODO: One paragraph description of each of these phases, from original RoD documentation**
