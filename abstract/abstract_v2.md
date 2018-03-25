## An introduction to citizen data science with Home-Assistant

#### Brief Summary (max 400 char)
Home-Assistant is an open-source python-3 platform home automation that is ideal for gathering, analysing and acting on data from a wide range of sources. Citizen-scientists can use Home-Assistant as their data backend, allowing them to integrate their project into their daily life.


#### Main
Home-Assistant is an open-source, Python 3, home automation hub, typically running on a Raspberry Pi in the home. Home-Assistant can connect with with a huge range of sensors, switches and services, and the state of the system is continually logged to an SQL database on the hub. This combination of open-source software using standard tools, and broad integration with services and hardware makes Home-Assistant an ideal platform for conducting citizen data science projects.

This talk will begin with an introduction to Home-Assistant and highlight the features which make it ideal as a data backend for citizen science projects. The talk then presents a project on personalised air quality monitoring. This project uses a battery-powered [low cost sensor](https://www.hackster.io/OxygenLithium/particulater-air-quality-monitoring-for-everyone-3caef2) to monitor air quality as well as other environmental variables. Sensor readings along with GPS data are transmitted back to Home-Assistant, and logged to the database. Home-Assistant allows a user to monitor, visualise and ultimately predict their daily exposure to pollution. Home-Assistant automations can then be used to trigger actions based on the data. For example flashing a red light in the users home when it predicts they may become exposed to a higher than average level of pollution. In the talk Q&A it is anticipated that the audience will raise their own challenges in their citizen science projects and together we can explore solutions using Home-Assistant.

**Talk Structure**
1. 0-20 mins: Introduction to Home-Assistant, demo installation, setup an automation.
2. 20-30 mins: Demo accessing the Home-Assistant database and do some data analysis in Pandas.
3. 30-40 mins. Present background on citizen data science projects, their challenges and impact.
4. 40-70 mins: Present our air quality project, hardware solution, integration with Home-Assistant, analysis of data.
5. 70-80 mins: Future plans and prospects.
6. 80-90 mins: Interactive session with audience to explore their project challenges.
