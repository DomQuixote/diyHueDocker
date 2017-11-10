# diyHueDocker
A docker file for diyHue to control various WiFi enabled lights with a Hue Bridge emulator.

Build with 

docker build
then:
docker run -p 80:80 --name HueEmulator <nameofcontainer> 
  
  
Due to the fact Hue applications expect the service to run on port 80, it is not possible to expose the service on another port.

Comments welcome.
