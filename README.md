# HTTP Server Response Sample

This Sample demonstartes a simple HTTP/REST service using HTTP Server connectivity plug-in where the response is handled in EPL application. That means we can have a full request response protocol where the logic is handled by the EPL application allowing some complex processing and state.

# Running this sample 

N.B. It is assumed you have an installation of Apama and that the environment has been set correctly

* clone or extract this repository to a local directory
  * edit HTTPServer.properties and choose a port that you want the HTTP Server to be exposed on 
  * E.G HTTPServer_port=30002
* cd into the directory and run engine_deploy 
  * E.G. engine_deploy --outputDeployDir app application
* run the correlator
  * E.G. correlator -v DEBUG --config app
* now point a browser at the running correlator (using your port) 
  * firefox http://localhost:30002/index.html
  
This should show a screen similar to the one below

![Alt text](images/main.PNG?raw=true "Browser view")
