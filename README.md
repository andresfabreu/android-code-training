# Android Code Training

## Setup
Before starting make sure to setup and run the [training API code](https://github.com/andresfabreu/android-training-api).

## Requirements
- Must use: 
1. An architecture pattern
2. Kotlin

- Must have at least:
1. One unit test
2. One integration test

## Description
The training API delivers a Car CRUD, this CRUD is used in two differents scenarios: 
1. Favorite Screen, display favorited cars
2. Map Screen, display cars near the user

That said the Challenge consist in the development of a component that will be used in these two different scenarios, each scenario have some particularities:
1. Favorite Screen: Display only Car model and brand, does not have a click action
2. Map Screen: Besides the Car model and brand also display the distance between the Car and the user, notice that our backend team was not able to deliver this information, so it'll be calculate in app side.

ps: The component may or may not have a custom header and footer, based on each scenario. The entry point can be a screen with two button for exemple.
