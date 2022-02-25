# React Immutable State

## Learning Objectives
- Build a React component that holds an immutable array as state and updates it

## Set Up
* Fork and clone this repository
* `npm install` to install dependencies
* `npm start` to start the React development server

## Instructions
In this exercise you are provided with a simple component that maintains a list of randomly generated workouts. You must implement the provided function placeholders to make the application functional. To do this, you will need to understand how to manipulate an immutable array held as React state.

### Part 1 Adding Workouts
- Implement the `addNewWorkout` function to add the `newWorkout` object to the `workouts` state in an immutable way.

### Part 2 Removing Workouts
- Implement the `deleteWorkout` function to remove the `workout` from the `workouts` state in an immutable way.

### Part 3 Updating Workouts
- Implement the `completeWorkout` function to set the `done` boolean to true on the passed `workout`and update `workouts` state in an immutable way.

## Extension
- Add a checkbox with the label "Show Done Only" to allow the user to toggle between all workouts and only workouts that are done.

## Extension 2
- Add a new button to each workout that when clicked replaces the workout with another random workout
