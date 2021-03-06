# Foodload
This is a project where the main objective was to learn as much as possible by building a mobile application as well as a RESTful backend and a WebSocket server. In this project we built an application where one could keep track on food items in a household and also generate buying lists for a created template. For example, one can add new food items to a storage (e.g. Fridge) and the family members could keep the amount updated in real time. One can also create a template (e.g. for the ingredients for a recipe or the buying list of the week) which generates a buying list with the missing ingredients/food items for that template.

The structure of the project is as follows:

| Codebase              | Description        
| --------------------- |:-------------------:|
| foodload_backend      | RESTful backend     |
| foodload_flutter      | Mobile application  |
| notification service  | WebSocket server    |

## The RESTful Backend
We built the backend with Spring Boot and used PostgreSQL for the database and Redis for PubSub. For authentication we used Firebase and JWT:s.

## The Mobile Application
For building the mobile application we used Flutter. Building a mobile application was new for us and so was Flutter and Dart. So this part of the project was the most challenging and also the most fun.

## The WebSocket Server
The WebSocket server was built in Node.js with Express and SocketIO. This component was the smallest one in this project but very important since it provided with real time updates in the application.

## Summary of Technologies
* Firebase
* Flutter
* Node.js and Express
* PostgreSQL
* Redis
* SocketIO
* Spring Boot
