# Inter-IIT-IOT
This project was done in the 8th Inter IIT Technical meet which was held at IIT Roorkee. It is a solution to the problem statement formulated by DIC (Design Innovation center, IIT Roorkee). The problem statement was basically to build a bot to help the farmers with terrace farming.

One of the problem faced by the farmers are that they lack essential inputs such as soil moisture content, temperature, humidity etc. Terefore we have implemented IoT with the Agritech bot to curb this issue. It can used to note the real time field inputs of specific part of the land as desired by the farmer.

This repository contains only the IOT part implemented in the terrace farming bot. 

## Sensors used
Soil moisture sensor, temperature and humidity sensors were used.

This project won GOLD at the Inter IIT Tech meet 8.0 among a total of 18 teams that took part for the same problem statement.

## Steps and sequence of running the files:-

1) Firstly ensure proper connection of sensors with the esp8266.
2) Upload the file named integrated.ino in the esp266.
3) Upon running the code in esp8266, it will generate a url which needs to copied and pasted in the file EXAMPLE_PYTHON_READER.py    (generally the url remains same if the wifi of esp is not changed.)
4) Run the file named EXAMPLE_PYTHON_READER.py in the ubuntu terminal. (now the sensor data are present in a text file)
5) Finally run the main.py in the ubuntu terminal. It will genetae a url.
6) Copy paste the url in the chrome to get to the web page.

NOTE: The files should be present in the same folder. The arrangement of files should be shown in this repository.
NOTE: This is a preliminary project. It can be automated and made efficient to make the process easier.
