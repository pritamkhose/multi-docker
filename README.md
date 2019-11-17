To Run local setup -

git clone https://github.com/pritamkhose/multi-docker      
cd multi-docker/
 
sudo docker-compose up --build

http://localhost:3050/

sudo docker ps -a
sudo docker images -a
sudo docker info

sudo docker-compose stop

sudo docker system purage
sudo docker rmi f20a6d8b6721

# Run Production via AWS ElasticBeanstalk 
https://us-east-2.console.aws.amazon.com/elasticbeanstalk/home?region=us-east-2#
