# Architecture to a IoT Ingestion / Report System

All the documentation of the project are on medium on this [link](https://medium.com/@rafaelfaita/a-simple-iot-architecture-to-ingestion-and-reporting-babc8985e25e).

# Project List

 - [Edge Service](https://github.com/rfaita/iot-edge)
 - [Asset Service](https://github.com/rfaita/iot-asset)
 - [Time Series Persistent Service](https://github.com/rfaita/iot-tsp)
 - [Time Series Aggregation Service](https://github.com/rfaita/iot-tsa)
 - [Rule Service](https://github.com/rfaita/iot-rule)
 - [Time Series Stream Service](https://github.com/rfaita/iot-reactive)
 - [Gateway Service](https://github.com/rfaita/iot-gtw)
 - [Embedded System](https://github.com/rfaita/iot-embedded)
 

# Requirements to System

You will need to have pre installed:
 - JDK 8
 - maven
 - docker
 - docker-compose
 
# Developer start up

Clone the **iot-infra** and the execute the shell script **clone**:

```sh
$ chmod +x clone && ./clone
```

This command will create a folder in your home with all repos to development:

```sh
$ cd ~/iot-dev
```

Now you can start you favorite IDE and edit the code

# Runing the development environment

```sh
$ cd ~/iot-dev/iot-infra && ./startdevmode
```
 
 
