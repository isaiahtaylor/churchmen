# Gameplan

## Basic feature list

### Mobile app

* ability to select "I want help" or "I want to help"
* select which church you're a part of
* ability to give good times to notify you about help to give
* notifications when help is needed around the timeframe you've specified
* ability to create new help event
  * number of people needed
  * time / location
  * activity description
* ability to monitor the status of your help event
  * how many people are confirmed coming
  * in-app chatting for directions etc
  

## Technology

### Mobile app

We'll be using **Flutter** for the mobile app. This will provide the most power out the gate.

### Backend

The backend will be almost entirely on AWS. Amplify / AppSync will be our schema, Cognito the authentication.