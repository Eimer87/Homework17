# Unit 17 Nosql Homework: Workout Tracker

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

 A fitness workout logger that takes in new exercises and uses MongoDB with Mongoose to log them to the database which can then be analyzed in the app's dashboard that has multiple graphic views of the different workouts.
Completion of this app included the buidling out of the exercise model for the Mongo DB formatting to ensure the correct logging of the various fields in the application. As there are two different types of workouts avaialble, resistance and cardio, the requried fields for each of them will be the
same while there are a few fields that are only specific to the type of workout being logged.

There wern't too many difficult parts of this project and the more labor intensive parts included setting up the server, routing for API and HTML, and the model for the database.

## Demo

<img src="gif">

## Table of Contents

-   [Installation](#installation)

## Installation

First, branch the Github Directory and clone the repo to your local machine to install this program. You would then need to install node dependencies, which can be done in your terminal/bash shell by running the npm install command. 
You will need to populate your MongoDB database after the dependencies have been enabled by uncommenting the appropriate seed file or executing NPM Run Seed.

## Usage
You may start the application by running the server.js node or the npm start command. You will then need to visit the local host URL for the port that this application has set up for you. When loaded in the window, you can either click the dashboard tab to display the exercise stats on the supplied graphs or add/continue the exercise by clicking the add or refresh buttons on the home page. When adding a new workout, make sure to click Complete after you have completed anything, as if you click Add Exercise, then add a blank instance of a workout with 0 for the numbers and no string for the region of the title/name.