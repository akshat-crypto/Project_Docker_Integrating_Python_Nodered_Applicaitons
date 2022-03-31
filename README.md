# PRJECT-2 Docker Integrating Python Application with Nodered, Influxdb, Postgrest, Grafana to setup a complete workflow

### PROJECT DESCRIPTION

>> For this project I have used AWS Cloud9 services which creates a preconfigured enviornment for this setup

>> Here I have used a Python applicaiton which will generate some random temperature data

>> With the help of Nodered Container here we are injecting the generated data to the Influxdb and Postgrest Databases

>> Also here We have setup two Grafana Dashboards which will take input from the databases InfluxDb and Postgrest and display it in form of a graph

>> Networking is done in such a way that no client can directly access any databse. They can only access the Nodered Container and  Grafana Dashboard

>> Also for nodered , influxdb, and python containers Here we have setup certain health checkups to monitor whether these applicaitons are running properly or not


