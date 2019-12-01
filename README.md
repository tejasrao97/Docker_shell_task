# Docker_shell_task

1. Dockerfile : This dockerfile is used to install vim and git using nginx as a base image.

2. Docker-compose file : This docker-compose file is used to set up a mongoDB container which is linked to a mongo-express container with the help of bridge network in the host machine. 
   a) Before bringing up the compose file, create a new directory named MongoDB inside the /root directory to make sure that the host machine is mapped locally with the volume present inside the MongoDB container. 
   b) The username and password for the Mongo-Express UI are:-
      Username : AT&T
      Password : TangoYankee

3. Shell script: This shell script accepts the name of the file and it's path as the input from the user and verifies if the file exists in the specified path, if not creates a new file in the same path with the aforementioned file name.
