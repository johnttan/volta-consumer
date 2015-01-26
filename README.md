#Volta Energy-Consumer
[![Circle CI](https://circleci.com/gh/teamvolta/volta-consumer/tree/dev.svg?style=svg&circle-token=5c73e7db8a6313ad61b0d30176a46a65ac93913e)](https://circleci.com/gh/teamvolta/volta-consumer/tree/dev)

A smart grid management system with dynamic energy pricing that enables customers to trade green energy in local markets.

[Volta Energy-Consumer](https://github.com/teamvolta/volta-consumer) represents the household consumer model of the [Volta Energy system](https://github.com/teamvolta).

Also see: 

* [Volta Energy-Producer](https://github.com/teamvolta/volta-producer)
* [Volta Energy-System](https://github.com/teamvolta/volta-system)

##Table of Contents

1. [Team](#team)
2. [Deployment](#deployment)
3. [Development](#development)
    1. [Requirements](#requirements)
    2. [Installing Dependencies](#installing-dependencies)
    3. [Distributive System Tool](#distributive-system-tool)
4. [Roadmap](#roadmap)

##Team

* Product Manager: [Anastasia Zotova](https://github.com/azotova)
* Technical Lead: [John Tan](https://github.com/johnttan)
* Scrum Master: [Michael Lom](https://github.com/mlom)
* Development Team: [Nikhil Ballaney](https://github.com/NBallaney)

##Deployment
To see a deployed version of the Volta Energy system, please visit the following:
* [Volta Energy-System Dashboard](http://voltaenergy.io)
* [Volta Energy-Consumer Dashboard](http://consumer1.azurewebsites.net/dashboard)
* [Volta Energy-Producer Dashboard](http://producer1.azurewebsites.net/#/)


##Development

###Requirements
* Node.js

###Installing Dependencies

From within the root directory:

```
npm install -g bower
npm install
bower install
```

###Distributive System Tool
The Volta Energy system requires running multiple servers for each [consumer](https://github.com/teamvolta/volta-consumer), [system](https://github.com/teamvolta/volta-system) and [producer](https://github.com/teamvolta/volta-producer) model. To assist running multiple servers simultaneously, please refer to [Distributive System Tool](https://github.com/teamvolta/distmanager).

### Roadmap

View the project roadmap [here](https://github.com/teamvolta/volta-consumer/issues).
