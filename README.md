# The web server of Indi javascript games
This repository contains the links and the documentation for the whole PROYECTO GAMER infrastructure

Projecto gamer is an Open source web page which offers anyone to host his or her game. And make it available for internet.
Currently we are trying to create our own server in a raspberry pi. And since we do not have any colaborators yet, the server is not operating. However, at the moment we get a raspberry pi, we will keep working on it. If you want to collaborate, please contact me to mvca1245@gmail.com.

## Project Arquitechture
We defined 3 different modules that are ment to work toghether:
The backend: Contains all the needed software for making the backend of gameServer work.
The frontend: Contains the sofware needed to make the webpage of proyecto gamer work.
All the different games are stored in another repository. This assures that the games would work independenly from the backend or the frontend. And also makes a little more simple for people who want to colaborate. This way, they do not have to bother about any other module of the   PROYECTO GAMER infrastructure.

## Repositories

|Repo|Description|
|----|-----------|
|[games-gameServer](https://github.com/chriss1245/games-gameServer)|This repo contains all the games in game server|
|[backed-gameServer](https://github.com/chriss1245/backend-gameServer)|The backend part of the game server|
|[frontend-gameServer](https://github.com/chriss1245/frontend-gameServer)| The frontend part of game server|

## In the future 
### Machine Learning!
We want to connect a database to store scores and other kind of data. We aim developing basic reinforcement learning agents which could play these games.
### Our own email extension
Once we have some raspberry PIs we want to use one of them as email server. We want to give to anybody who colaborates with us this custom email.
In addition, we want to add in the frontend a way of managing the emails.
