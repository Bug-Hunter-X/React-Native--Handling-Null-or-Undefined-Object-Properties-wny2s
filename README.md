# React Native: Handling Null or Undefined Object Properties

This repository demonstrates a common error in React Native applications: encountering unexpected `null` or `undefined` values when accessing object properties.  It shows the error and provides a solution using optional chaining and nullish coalescing.

## The Problem

Accessing properties of an object that is `null` or `undefined` will cause a runtime error. This is particularly problematic in asynchronous operations where data might not be available immediately. 

## The Solution

The provided solution uses optional chaining (`?.`) and the nullish coalescing operator (`??`) to safely handle these scenarios.

## Usage

1. Clone this repository
2. Run `npm install` or `yarn install`
3. Run the application using your preferred React Native method (e.g., `npx react-native run-android` or `npx react-native run-ios`).