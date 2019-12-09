# How to System will Work

## Big Picture

![alt BigPicture](images/iot.png)

## Edge Service

This service is responsable for recieve the information incoming across the devices, the service use the
**mqtt** protocol to recive messages, the format of the message MUST be JSON, with the following minimum payload:

```json
{
    "id": "2", 
    "tenantId": "1", 
    "token": "321", 
    "timestamp": 123213123, 
    ... custom fields
    "temperature": 27.3, 
    "memory": 36.3
}
```

#### Important
 - id, tenantId, and tokenId: must be used the supplied by **Asset Service**
 - timestamp: in seconds
 - custom fields: you can send any data to server, the edge service will intepretate it

## Asset Service
## Times Series Aggregation Service
## Times Series Persistent Service
## Rule Service


# How to Run System

You will need pre installed:
 - JDK 8
 - maven
 - docker
 - docker-compose
 
