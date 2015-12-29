# Docker JRebel License Server
JRebel License Server running in docker container

More info about JRebel License Server 
* http://manuals.zeroturnaround.com/license-server/ 
* http://zeroturnaround.com/software/license-server/quick-start/#!/installation

## Usage
Run with ```docker run -p 9000:9000 borgeorgiev/docker-jrebel-license-server```

To run with Jrebel license server data on docker host i.e. host dir in ```/data/jrebel``` use 
```docker run -p 9000:9000 -v /data/jrebel:/jrebel/license-server/data borgeorgiev/docker-jrebel-license-server```


Follow the activation procedures http://zeroturnaround.com/software/license-server/quick-start/#!/activation

Based on official java:7 image
