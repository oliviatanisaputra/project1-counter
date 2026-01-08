# Simple Counter

A React-based counter application demonstrating fundamental concepts of component-based architecture, state management, and lifecycle methods.

## Overview

This project is an interactive counter application built with React that showcases core React concepts including state management with hooks, component composition, conditional rendering, and side effects handling. The application provides an intuitive interface for incrementing and decrementing a numerical counter with various step values.

## Features

- **Dynamic Counter Display**: Real-time counter value visualization
- **Multiple Increment Options**: Buttons for adjusting the counter by ±1, ±10, and ±100
- **Even Number Detection**: Conditional rendering that displays a message when the counter value is even
- **Component Lifecycle Tracking**: Console logging for monitoring component updates and unmounting
- **Input Field**: Additional text input for demonstrating multiple state management

## Architecture

The application follows a modular component structure:

### Components

- **App.js**: Main application component managing global state and orchestrating child components
- **Viewer.js**: Presentational component for displaying the current counter value
- **Controller.js**: Interactive component containing increment/decrement buttons
- **Even.js**: Conditional component that appears only when the counter is an even number

## Technologies Used

- **React**: JavaScript library for building user interfaces
- **React Hooks**: 
  - `useState` for state management
  - `useEffect` for side effects and lifecycle management
- **CSS**: Custom styling for component presentation

## Key Concepts Demonstrated

1. **State Management**: Using `useState` to manage counter and text input states
2. **Props Drilling**: Passing state and handlers between parent and child components
3. **Event Handling**: Managing user interactions through button clicks and input changes
4. **Conditional Rendering**: Dynamically showing/hiding components based on state (`count % 2 === 0`)
5. **Side Effects**: Implementing `useEffect` for logging and cleanup operations
6. **Component Lifecycle**: Understanding mount, update, and unmount phases

## Usage

- Click the **+1**, **+10**, or **+100** buttons to increment the counter
- Click the **-1**, **-10**, or **-100** buttons to decrement the counter
- The "현재 카운트는 짝수입니다" (Current count is even) message appears when the counter value is even
- Type in the input field to see multi-state management in action
- Open the browser console to observe component lifecycle logs

## Learning Outcomes

This project was developed as part of Software Development Practice 2 (소프트웨어개발실습2) course and demonstrates:

- Proficiency in React fundamentals
- Understanding of component-based architecture
- Practical application of React Hooks
- Clean code organization and separation of concerns
- User interface development with React