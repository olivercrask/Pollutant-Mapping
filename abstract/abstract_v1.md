## An introduction to data science with Home-Assistant

#### Brief Summary (max 400 char)
Citizen data science projects typically use 'free' cloud solutions for collecting their data, but these come with restrictions and often result in the use of proprietary analysis tools. Home-assistant is an open-source python-based platform that is ideal for gathering, analysing and interpreting data. The scientist can then integrate the project into their daily life, giving it new dimensions.


#### Main
Home-assistant is an open-source, Python 3, home automation hub, typically running on a Raspberry Pi in the home. Home-assistant can connect with with over 1000 different types of sensors, switches and services (collectively referred to as entities), allowing event driven automations. For example, to perform actions such as switching on the lights when the user gets home after dark. The state of the system (entities and events) is continually logged to an SQL database on the hub. This combination of open-source software using standard tools and broad integration with services and hardware makes Home-assistant an ideal platform for conducting citizen data science projects.

The workshop will begin with an introduction to Home-assistant and a demo of its use. We then move onto a short presentation on a citizen data science project that Robin and Oliver have been undertaking on individualised air quality monitoring. This project uses a variety of low cost components to monitor air quality as well as other environmental variables. The device then transmits the sensor values along with GPS data back to Home-Assistant. The aim is for this to be a device that someone can carry on their daily commute or keep in their home. The device will interpret the data collected and trigger automations, enabling the user to be more informed about their environment.
The workshop will end with an interactive session where the audience can discuss the challenges in their citizen data science projects and together we can explore solutions using Home-assistant.

**Talk structure**
1. 0-20 mins: Introduction to Home-Assistant, some background, demo running and setup of an automation.
2. 20-30 mins: Show accessing Home-Assistant database, demo some data analysis in Pandas.
3. 30-40 mins. Present background on citizen data science projects, present case study of [pollution monitoring using taxis](https://www.hackster.io/james-puderer/distributed-air-quality-monitoring-using-taxis-69647e).
4. 40-70 mins: Present our air pollution monitoring project, hardware solution, integration with HA, analysis of data.
5. 70-80 mins: Future plans and opportunities.
6. 80-90 mins: Interactive session with audience to explore their challenges.
