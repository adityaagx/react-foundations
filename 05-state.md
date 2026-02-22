
====================================
TOPIC 5: STATE
====================================

THEORY
------
State is data that belongs to a component and can change.

When state changes:
- React re-renders the component
- UI updates automatically

State is used for:
- Counters
- Input values
- Toggle buttons
- Any changing data

------------------------------------

EXAMPLE
-------
A counter using state:

function Counter() {
  const [count, setCount] = React.useState(0);

  return (
    <div>
      <p>Count: {count}</p>
      <button onClick={() => setCount(count + 1)}>
        Increase
      </button>
    </div>
  );
}

------------------------------------

WHAT IS HAPPENING
-----------------
- count → current state value
- setCount → updates state
- Updating state updates UI

------------------------------------

SUMMARY
-------
State = changing data inside a component.
Change state → React updates the screen.

====================================
END
====================================

====================================
STATE PRACTICE – 20 QUESTIONS
====================================

BASIC LEVEL
-----------

1. Create a Counter component with a button that increases a number by 1.

const Counter = () => {
  return 
}

2. Create a Counter component with two buttons:
   - Increase
   - Decrease

3. Create a Toggle component that switches between:
   "ON" and "OFF" when button is clicked.

4. Create a component that shows a message.
   Add a button to hide the message.

5. Create a component with a number starting at 10.
   Add a button that resets it back to 10.

------------------------------------

INTERMEDIATE LEVEL
------------------

6. Create a component with two separate states:
   - firstName
   - lastName
   Display full name together.

7. Create a component with a text input.
   Store input value in state and display it live.

8. Create a component with a counter.
   Add a button that increases count by 5.

9. Create a component that tracks how many times a button was clicked.
   Display total clicks.

10. Create a component that toggles between two colors:
    Red and Blue (just display text color change).

------------------------------------

INTERMEDIATE+ LEVEL
-------------------

11. Create a component that stores an object in state:
    { name: "", age: 0 }
    Display both values.

12. Add a button that updates only the age inside the object state.

13. Create a component that stores an array in state.
    Display items using map().

14. Add a button that adds a new item to the array.

15. Add a button that removes the last item from the array.

------------------------------------

ADVANCED THINKING LEVEL
-----------------------

16. Create a counter that uses:
    setCount(prev => prev + 1)
    instead of setCount(count + 1).

17. Create a component with two buttons:
    - Increase twice (increase by 2 in one click)
    - Increase once

18. Create a component that disables a button when count reaches 5.

19. Create a component that shows:
    "Even" if count is even
    "Odd" if count is odd

20. Create a component with:
    - Input field
    - Button
    When button is clicked, store input value into an array state
    and display the list below.

====================================
END
====================================
