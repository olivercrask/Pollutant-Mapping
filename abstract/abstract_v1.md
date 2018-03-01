## An introduction to citizen data science with Home-Assistant

#### Brief Summary (max 400 char)
Citizen science projects typically use 'free' cloud solutions for collecting their data, but these come with restrictions and often result in the use of proprietary analysis tools. Home-Assistant is an open-source python-based platform that is ideal for gathering, analysing and acting on data. The citizen-scientist can then integrate the project into their daily life, giving it new dimensions.


#### Main
Home-Assistant is an open-source, Python 3, home automation hub, typically running on a Raspberry Pi in the home. Home-Assistant can connect with with a huge range of sensors, switches and services, and the state of the system is continually logged to an SQL database on the hub. This combination of open-source software using standard tools, and broad integration with services and hardware makes Home-Assistant an ideal platform for conducting citizen data science projects.

This workshop will begin with an introduction to Home-Assistant and a demo of its installation and use. We then give a short presentation on a project that the speakers have been undertaking on personalised air quality monitoring. This project uses a battery operated [low cost sensor](https://www.hackster.io/OxygenLithium/particulater-air-quality-monitoring-for-everyone-3caef2) to monitor air quality as well as other environmental variables. Sensor readings along with GPS data are transmitted back to Home-Assistant, and logged to the database. Home-Assistant allows a user to monitor, visualise and ultimately predict their daily exposure to pollution. Home-Assistant automations can then be used to trigger actions based on the data, for example flashing a red light in the users home when it predicts they may become exposed to a higher than average level of pollution. The workshop will end with an interactive session where the audience can discuss the challenges in their citizen science projects and together we can explore solutions using Home-Assistant.

**Talk structure**
1. 0-20 mins: Introduction to Home-Assistant, demo installation, setup an automation.
2. 20-30 mins: Demo accessing the Home-Assistant database and do some data analysis in Pandas.
3. 30-40 mins. Present background on citizen data science projects, their challenges and impact.
4. 40-70 mins: Present our air quality project, hardware solution, integration with Home-Assistant, analysis of data.
5. 70-80 mins: Future plans and prospects.
6. 80-90 mins: Interactive session with audience to explore their project challenges.
