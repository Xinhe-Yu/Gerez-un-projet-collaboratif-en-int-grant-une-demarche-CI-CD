# BobApp
[![Tests](https://github.com/Xinhe-Yu/Gerez-un-projet-collaboratif-en-int-grant-une-demarche-CI-CD/actions/workflows/tests.yml/badge.svg)](https://github.com/Xinhe-Yu/Gerez-un-projet-collaboratif-en-int-grant-une-demarche-CI-CD/actions/workflows/tests.yml)

[![Sonar](https://github.com/Xinhe-Yu/Gerez-un-projet-collaboratif-en-int-grant-une-demarche-CI-CD/actions/workflows/quality.yml/badge.svg)](https://github.com/Xinhe-Yu/Gerez-un-projet-collaboratif-en-int-grant-une-demarche-CI-CD/actions/workflows/quality.yml)

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

## Coverage Reports

- [Frontend Coverage Report](https://xinhe-yu.github.io/Gerez-un-projet-collaboratif-en-int-grant-une-demarche-CI-CD/frontend/index.html)
- [Backend Coverage Report](https://xinhe-yu.github.io/Gerez-un-projet-collaboratif-en-int-grant-une-demarche-CI-CD/backend/index.html)
