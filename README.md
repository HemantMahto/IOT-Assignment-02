# IOT-Assignment-02

Assignment 2: IoT : Application Security

Here the goal is to create a sort of weather station that deploys various readings of sensors based on its selection. It is part of the course application project for MS in Cybersecurity at Syracuse University.

Using a python scrypt we simulate data sensors and we send them in JSON format to Thingsboard. The script is available on github Before running the script, we need to download the library with this command: npm install mqtt --save

start the connection between the client and our broker using host:"demo.thingsboard.io", port:1883 and topic:"v1/devices/".

bash script: curl -X POST --header 'Content-Type: application/json' --header 'Accept: application/json' -d

Check for import libs and import necessary libs
