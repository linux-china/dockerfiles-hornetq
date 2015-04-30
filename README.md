docker-hornetq
=========================================
Docker file for trusted builds of HornetQ on Docker Hub.

Run the latest container with:

* docker pull linuxchina/hornetq
* docker run -p 5445:5445 -p 5455:5455 linuxchina/hornetq

The Broker listens on port 5445 and 5455.

### Docker compose
please add following code into your docker-compose.yml

    hornetq:
        image: linuxchina/hornet
        ports:
          - "5445:5445"
          - "5455:5455"
    
### Image Tags

* linuxchina/hornetq:latest
* linuxchina/hornetq:2.4.7
