### Remember

Answer these on your own, then compare answers as a group

1.  What is React?

    React is...a javascript library.
    React is a javascript library. It’s used create components that present date that will change over time. It handles part of the visual layer for your website. It fetches data, & holds data.
    A javascript library for building and interacting with HTML layouts


2.  What is create-react-app?

    A tool Made by Facebook devs that sets up a package of files for a brand new react app, which saves a ton of time.
    It’s a tool that compiles all the packages you will most likely need while creating a react project.
     A tool, made by facebook, that simplifies the process of creating a react website

3.  What is Component Based Architecture?
It allows you to break up and structure different parts of your website. Such as a news feed, photo album, chat window.. etc. It maximizes the functionality and performance of each of these components… allowing one to be uploaded and refreshed without affecting the other components.
Splitting functionality into small, reusable parts

4.  What is JSX?
    A step that gives html syntax to javascript, makes it look nicer.
    A JavaScript extension that allows using HTML-like syntax to create elements in react

5.  What is the virtual DOM?
    A virtual representation of the actual DOM, and it sits between your app and the DOM. It makes rendering faster.
    

6.  What is unidirectional (one-way) data flow?
    Instead of data flowing both ways, the way it does in angular and other older formats, react uses one direction for data flow; parent to child.
    When data is only allowed to flow from parents to their children

### Understand

Discuss these questions in pairs if you have a 4-person group

7.  Summarize what happens when you run `create-react-app my-app`
    It creates a folder with the given name and fills it with a basic template for react apps
    A huge chunk of files are generated that set up our basic App.

8.  Explain what this code does:

```jsx
import React from "react";

const Mentor = props => (
 <div className="mentor-container">
   <h1 className={props.title === "Lead Mentor" ? "lead" : ""}>Tim Biles</h1>
   <ul>
     <li>Fort Worth, TX</li>
     <li>My email address is timbilestimbiles@gmail.com</li>
   </ul>
 </div>
);

export default Mentor;```
    It imports the base react object, creates a functional component to produce elements, and exports said component
9.  Explain how data is passed from a parent component to a child component.
    Attribute-like 'props' will pass down their assigned data to the constructor of the Component
### Apply

Try these on your own, but work together if you start to get stuck.

10.  Use `create-react-app` to create a new React application called `student-directory`

11.  Use the code from `Mentor` above to create a new functional, stateless component called `User` with a list of friends. Hard code the list of friends, do not use state or props.

### Analyze, Evaluate, Create

Discuss these questions as a group

12. What are the benefits and drawbacks of using a tool like create-react-app?
    It can speed up the initial phase of a project, at the cost of including functionality that you might not need or fully understand

13. Compare and contrast JSX with other templating options, such as those used in Angular or Vue

14. Compare and contrast one-way data flow with two-way data binding.
    One-way data flow is more limited, while two-way data binding is supposedly too free