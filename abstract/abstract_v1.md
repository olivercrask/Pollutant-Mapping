## An introduction to data science with Home-Assistant

#### Brief Summary (max 400 char)
Citizen data science projects typically use 'free' cloud solutions for gathering their data, but these come with restrictions and often result in the use of proprietary analysis tools. Home-assistant is an open-source project that is ideal for data gathering and compatible with Pandas. Crucially the scientist can integrate the project into their daily life, adding new dimensions to the data.


#### Main
Home-assistant is an open source, python 3, home automation hub, typically running on a raspberry pi in the home. Home-assistant can connect with with over 1000 different types of sensors, switches and services (collectively referred to as entities), allowing event driven automations to perform actions such as switching on the lights when the user gets home and it is dark. The state of the system (entities and events) is continually logged to an SQL database on the hub. This combination of open-source software using standard tools and broad integration with services and hardware makes Home-assistant an ideal platform for conducting citizen data science projects.

The workshop will begin with an introduction to Home-assistant and demo its use. We then move onto a short presentation on a citizen data science project that Robin and Oliver have been undertaking on personalised air quality monitoring. This project uses a low cost air quality sensor to capture GPS tagged readings which are transmitted to a Home-assistant instance. Analysis will be performed on the collected data and an automation will be used to demonstrate how Home-assistant allows the citizen scientist to integrate their data science project into their daily life. The workshop will end with an interactive session where the audience can discuss the challenges in their citizen data science projects and together we can explore solutions using Home-assistant.

**Talk structure**
1. 0-20 mins: introduction to Home-Assistant, some background, demo running and setup of an automation.
2. 20-30 mins: show accessing Home-Assistant database, demo some data analysis in Pandas.
3. 30-40 mins. Present background on citizen data science projects, present case study of [pollution monitoring using taxis](https://www.hackster.io/james-puderer/distributed-air-quality-monitoring-using-taxis-69647e).
4. 40-70 mins: Present our air pollution monitoring project, hardware solution, integration with HA, analysis of data.
5. 70-80 mins: future plans and opportunities.
6. 80-90 mins: interactive session with audience to explore their challenges.
