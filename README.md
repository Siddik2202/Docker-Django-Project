This is a simple notes app built with React and Django.
Befor you follow this steps, you should install docker, docker-compose and also login docker.
Installation Proces:
  i) You can Clone this project using git clone https://github.com/Siddik2202/Docker-Django-Project.git
  ii) After that you need to create this Dockerfile with Install app dependencies. I already created so you can run by using  docker build -t my-image-name .
  iii) Here your image will create now. now create docker-compose file where build your image nginx, mysql and my-image-name app.
  iv) Befor execute you should create a volume "mysql-data" using docker volume create volume-name.
  v)  Also create network usinf docker network create network_name -d bridge
  vi) Now you can run your docker-compose file using docker-compose up --build
  vii) Now you can see docker project, nginx and mysql will work file with in a network.
