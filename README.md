# Monitoring-LA-25TU-Dimplex-Python3
Monitoring LA 25TU with Python3 accessing with Modbus and storing in Influx-DB
Intention is to read at regular intervals the LA-25TU using modbus and storing the results in an influxDB data base, then displaying results with Grafana.
First step is the Python3 module on a Linux-Ubuntu machine to read the LA-25TU.
I intend to use uModbus , through TCP. Function implemented are 1,3,5,6,15,16
