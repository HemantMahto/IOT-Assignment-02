# IOT-Assignment-02

Application Security

The aim is to develop a weather station that can collect sensor data and send it to Thingsboard. 

To achieve this, a Python script is used to simulate sensor data which is then transmitted to Thingsboard in JSON format via an MQTT connection with the broker at host:"demo.thingsboard.io", port:1883 and topic:"v1/devices/". Before running the script, the MQTT library needs to be installed using "npm install mqtt --save" command. 

Additionally, the bash script can be used to perform a POST request to Thingsboard. The necessary libraries are imported at the start of the script.
