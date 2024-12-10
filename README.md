# React Native FlatList Performance Issue

This repository demonstrates a common performance issue in React Native's FlatList component when rendering a large number of items. The example shows how to reproduce the problem and provides a solution for optimization. 

## Problem
Rendering a large dataset with complex items in a FlatList can result in slow rendering, dropped frames, and a poor user experience.

## Solution
The solution involves implementing techniques like data virtualization, windowing, and optimized item rendering to improve performance.

## Setup
1. Clone this repository.
2. Run `npm install` to install the necessary dependencies.
3. Run `npx react-native run-android` or `npx react-native run-ios` to start the app.