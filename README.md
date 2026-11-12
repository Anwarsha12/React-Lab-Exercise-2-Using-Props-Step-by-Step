# React Lab Exercise 2: Using Props — Step by Step
## Name: Anwarsha E.M
## Roll no: 2305001002
## Department: CSE

## AIM
### To create a React application that demonstrates how to pass data from a parent component to a child component using Props.

## PROGRAM
### i) App.jsx
```py
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
```
## OUTPUT
<img width="758" height="344" alt="Screenshot 2026-11-13 004748" src="https://github.com/user-attachments/assets/77e6534c-59d2-450a-8b9c-592dbc6de4c6" />
<img width="760" height="154" alt="Screenshot 2026-11-13 004809" src="https://github.com/user-attachments/assets/d953f0cf-8e72-4bc7-8ed5-0925207c875b" />


## RESULT
### The React application was successfully created using Props to pass employee information from the parent component to the child component. Three employee details were displayed successfully using Props and Props Destructuring.
