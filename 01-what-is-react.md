
====================================
TOPIC 1: WHAT IS REACT
====================================

THEORY
------
React is a JavaScript library used to build user interfaces.

Its main job is:
- Show data on the screen
- Automatically update the UI when data changes

React focuses only on the UI layer.
It does not handle backend, database, or styling by itself.

Core idea:
UI depends on data.
When data changes, React updates the screen.

------------------------------------

EXAMPLE
-------
A simple React component:

function App() {
  return <h1>Hello React</h1>;
}

This component:
- Is a JavaScript function
- Returns UI
- React shows this UI on the screen

------------------------------------

SUMMARY
-------
React shows UI based on data.
Data changes → UI updates.

====================================
END
====================================

====================================

THEORY PRACTICE QUESTIONS
-------------------------

BASIC UNDERSTANDING
-------------------

1. What is React?

- React is a javascript library used to build and change User Interface.

2. Is React a framework or a library?

- React is a library

3. What type of applications is React mainly used for?

- React is mainly used for web applications.

4. Which layer of an application does React focus on?

- Frontend layer.


CORE PURPOSE
------------

5. What is the main job of React?

- Main job of react is to build User interface of frontend and update it whenever the data changes.

6. What happens to the UI when data changes in React?

- User interface gets re - rendered when data changes in React.

7. What is the core idea behind React?

- Core idea behind React is to re-render the UI whenever any data changes.

8. Explain the relationship between UI and data in React.

- Whenever data changes, UI changes accordingly.


SCOPE & LIMITATIONS
-------------------

9. Does React handle backend logic? Explain.

- No react doesn't handle backend logic. 
- React's work is to simply change the UI whenever it gets the new data.

10. Does React manage databases? Why or why not?

- No, react doesn't manage databases, it only manages frontend,
- Databases are handled by backend.

11. Does React automatically handle styling? Explain.

- No, React does not automatically handle styling. 
- We use CSS or other styling methods with React.


UNDERSTANDING THE EXAMPLE
-------------------------

12. In the example provided, what type of thing is "App"?

- App is a function.

13. What does the App function return?

- App function returns JSX <h1>Hello React</h1> which represents UI .

14. How does React display the UI returned by a component?

- React displays the UI by rendering the JSX returned components to the screen.

15. Why is a React component considered a JavaScript function?

- Because it gets the new data as an argument, 
- and accordingly return the new UI, which react then updates.


CONCEPT CLARITY
---------------

16. If data changes but the UI does not update, is React working correctly? Why?

- No, react is not working properly, because
- react always has to update the UI whenever data/state changes.

17. Why is React called a “UI library”?

- Because it handles the UI part of application.

18. What does it mean that React focuses only on the UI layer?

- It only handles the UI layer not the backend logic or anyhting else.

19. Can React work without JavaScript? Explain.

- No, react can't work without javascript because browsers only understand javascript.

20. Complete the statement:
    “Data changes → UI updates”

====================================
END
====================================
