# Ngram-Node-React-Django-Project

Table of Contents
Description
Technologies Used
Usage
API Endpoints

Description
This project is a full-stack application that includes a backend built with ExpressJS and a PWA (Progressive Web App) frontend built with React. The backend interacts with a Django server through an API to perform ngrams comparison using NLTK.

The main tasks completed in this project are as follows:

Created a backend using ExpressJS to handle HTTP requests and responses.
Developed a PWA using React that accepts text input from users and sends it to the backend. The user interface of the PWA dynamically changes on interaction.
Implemented the following functionalities in the backend:
Logs the number of times a connection is made by the frontend and inserts it into a Mongoose Model.
Receives the text inserted by the frontend and inserts it into another Model.
Calls the Django API using the two most recent strings and returns the ngrams to the frontend.
Created a Django server that provides an API to perform ngrams comparison using NLTK.

Technologies Used
ExpressJS
React
Django
NLTK
Node

Usage
The app described is a full-stack application consisting of a backend built with ExpressJS, a PWA frontend developed with React, and integration with a Django server. It enables users to input text, which is processed by the backend and sent to the Django server for advanced text analysis using NLTK. The app also includes features like connection logging.

API Endpoints
List all the API endpoints and their descriptions.

Endpoint 1: "http://localhost:80/api/message" 
Receives the text inserted by the frontend and inserts it into a Model.

Endpoint 2: "http://localhost:80/api/ngrams"
Call the Node Server API to get the ngrams for last two messages.

Endpoint 1: "http://localhost:8000/get_ngrams/"
Calls the Django API using the two most recent strings and returns the ngrams to the frontend.
