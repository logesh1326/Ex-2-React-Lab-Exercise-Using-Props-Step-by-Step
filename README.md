React Lab Exercise 2: Using Props — Step by Step
Name: Aravindan T
Roll no: 2305001003
Department: CSE
AIM
To create a React application that demonstrates how to pass data from a parent
component to a child component using Props.
PROGRAM
i) App.jsx
README
12/11/2026, 21:53 aravindan2005/React-Lab-Exercise-2-Using-Props-Step-by-Step
https://github.com/aravindan2005/React-Lab-Exercise-2-Using-Props-Step-by-Step#react-lab-exercise-2-using-props--step-by-step 1/3

import Employee from "./Employee";
function App() {
return (
<div>
<h1>Employee Information</h1>
<Employee
name="Aravindan T"
id="101"
department="CSE"
designation="Software Developer"
/>
<Employee
name="Hariharan S"
id="102"
department="IT"
designation="Web Developer"
/>
<Employee
name="Moulishwar G"
id="103"
department="AIDS"
designation="Data Analyst"
/>
</div>
);
}
export default App;
OUTPUT
RESULT
The React application was successfully created using Props to pass employee
information from the parent component to the child component. Three employee
details were displayed successfully using Props and Props Destructuring
