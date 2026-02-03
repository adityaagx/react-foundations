
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
