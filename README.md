Back  
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=MENDEL-BA_cicdbackend&metric=coverage)](https://sonarcloud.io/summary/new_code?id=MENDEL-BA_cicdbackend)  
[![Quality gate](https://sonarcloud.io/api/project_badges/quality_gate?project=MENDEL-BA_cicdbackend)](https://sonarcloud.io/summary/new_code?id=MENDEL-BA_cicdbackend)

Front   
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=cicdgithub_cicd-front&branch=main&coderage)](https://sonarcloud.io/summary/new_code?id=cicdgithub_cicd-front&branch=main&coderage)
[![Quality gate](https://sonarcloud.io/api/project_badges/quality_gate?project=cicdgithub_cicd-front)](https://sonarcloud.io/summary/new_code?id=cicdgithub_cicd-front)
# BobApp
Clone project:

> git clone XXXXX

## Front-end 

Go inside folder the front folder:

> cd front

Install dependencies:

> npm install

Launch Front-end:

> npm run start;

### Docker

Build the container:

> docker build -t bobapp-front .  

Start the container:

> docker run -p 8080:8080 --name bobapp-front -d bobapp-front

## Back-end

Go inside folder the back folder:

> cd back

Install dependencies:

> mvn clean install

Launch Back-end:

>  mvn spring-boot:run

Launch the tests:

> mvn clean install

### Docker

Build the container:

> docker build -t bobapp-back .  

Start the container:

> docker run -p 8080:8080 --name bobapp-back -d bobapp-back 