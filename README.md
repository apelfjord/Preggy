# Preggy

**A proof of concept built in React Native during a two week sprint.**

## The Concept
An app for expecting parents where everything is in the same place.
Combining the ability to track their pregnancy journey, connect with others and follow their favourite influencers week by week blog posts. 
Once the baby is born the app will continue to serve as a hub of information for new parents.

## Tech Stack
* React Native
* Native Navigation
* Native Base
* MongoDb

## Starting Up

### [Install MongoDb](https://treehouse.github.io/installation-guides/mac/mongo-mac.html "Install MongoDb")
### [Install React Native CLI](https://facebook.github.io/react-native/docs/getting-started "Install React-Native") & Xcode

### While mongo is running:
~~~~
cd Server
npm i
npm start
~~~~

### In a new terminal tab: 
~~~~
cd Preggy
npm i
react-native run-ios
~~~~

#### The red button, "Ta bort Användardata", in the drawer menu is for development mode only. In order to remove all stored user data from asyncStorage
