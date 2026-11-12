# Ex. 2  React Lab Exercise: Using Props — Step by Step

## Exercise Number
Exercise 2

## Subject
AI1067 - Modern Web Application Development (React JS Lab)

## Student Details
- **Name:** LOGESH S
- **Roll No:** 2305001014
- **Department:** B.Tech CSE
- **College:** IST, NMV University

## Objective
To create a React application that demonstrates how to pass data from a parent component to a

## Description
Ex. 2  React Lab Exercise: Using Props — Step by Step
Objective
To create a React application that demonstrates how to pass data from a parent component to a 
child component using Props.
Step 1: Create a React Project
Open the terminal and run:
npm create vite@latest props-demo -- --template react
cd props-demo
npm install
npm run dev
Open the URL shown in the terminal.
Step 2: Understand Props
Props = Properties
Props are used to pass data from a parent component to a child component.
Parent Component
       │
       │  props
       ↓
Child Component
Example:
<Student name="Ajith" />
Here:
•
Student → Child component
•
name → Prop
•
"Ajith" → Prop value
Step 3: Create the Child Component
Create:
src/Student.jsx
Add:
function Student(props) {
  return (

    <div>
      <h2>Student Detail

## Technologies Used
- React JS
- Vite
- JavaScript (JSX)
- HTML5 / CSS3

## How to Run
```bash
npm create vite@latest my-app -- --template react
cd my-app
npm install
npm run dev
```

## Exercise Content
See `exercise.txt` for complete exercise content and source code.
