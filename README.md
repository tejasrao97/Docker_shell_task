# Docker_shell_task

1. Dockerfile : This dockerfile is used to install vim and git using nginx as a base image.


2. Docker-compose file : This docker-compose file is used to set up a mongoDB container which is linked to a mongo-express container with the help of bridge network in the host machine. 
   
   a) Before bringing up the compose file:
   
      i)  Create a custom Volume and mount the volume with the required container.
         
      ii) Create a custom bridged network and link both the containers to this network.
         
   b) After bringing up the containers:
         
      i)  Perfom an exec command to get into any one container and ping the other container, and make sure that they can talk to each             other
         
      ii) Create a Database and collection in mongo-express UI and add a document into the created collection and verify if the                   document is added into the mongoDB by logging into the mongoshell present inside the mongo container with the below                     mentioned mongo shell credentials
         
   b) The username and password for the Mongo-Express UI are:-
      
          Username : AT&T
      
          Password : TangoYankee

   c) The username and password to login into the mongo shell present inside the mongo container:
         
          Username : POTUS
          
          Password : StingRay
      
      Note: Please use the below command to login into the mongo shell:
          
          mongo --username POTUS --password StingRay
          
          
3. Shell script: This shell script accepts the name of the file and it's path as the input from the user and verifies if the file exists in the specified path, if not creates a new file in the same path with the aforementioned file name.
