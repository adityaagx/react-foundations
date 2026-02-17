
====================================
TOPIC 2: COMPONENTS
====================================

THEORY
------
A component is a small piece of the user interface.

In React:
- A component is a JavaScript function
- It returns what should appear on the screen

Components help by:
- Breaking UI into small parts
- Reusing UI logic
- Keeping code clean

Each component focuses on one job.

------------------------------------

EXAMPLE
-------
A simple component:

function Greeting() {
  return <h1>Welcome</h1>;
}

This component:
- Is a function
- Returns UI
- Can be reused anywhere

------------------------------------

USING A COMPONENT
-----------------
function App() {
  return (
    <div>
      <Greeting />
      <Greeting />
    </div>
  );
}

------------------------------------

SUMMARY
-------
Component = function that returns UI.
React builds the screen using components.

====================================
END
====================================

# React Practice – Topic 2: Components

## Rules
- Use only function components.
- Do NOT use props.
- Each component must return UI.
- Reuse components inside `App`.

---

## 1.
Create a component called `Hello`.
It should return:
<h1>Hello World</h1>

const Hello = () => {
  return <h1>Hello World</h1>;
};

---

## 2.
Create a component called `Bye`.
It should return:
<h2>Goodbye!</h2>

const Bye = () => {
  return <h2>Goodbye!</h2>;
}
---

## 3.
Create a component called `Paragraph`.
It should return:
<p>This is a React component.</p>

const Paragraph = () => {
  return <p>This is react component.</p>;
};
---

## 4.
Create a component called `Title`.
It should return:
<h1>My Website</h1>

const Title = () => {
  return <h1>My website</h1>;
};
---

## 5.
Create a component called `Footer`.
It should return:
<footer>Copyright 2026</footer>

const Footer = () => {
  return <footer>Copyright 2026</footer>;
};
---

## 6.
Use the `Hello` component twice inside `App`.

function App(){
  return (
     <div>
       <Hello />
       <Hello />
     </div>
  );  
}
---

## 7.
Use `Title` and `Paragraph` inside `App`.

function App(){
  return (
    <div>
    <Title />
    <Paragraph />
    </div>
  );
};

---

## 8.
Use `Title`, `Paragraph`, and `Footer` inside `App`.

function App (){
  return (
    <div>
     <Title />
     <Paragraph />
     <Footer />
    </div>
  );
};

---

## 9.
Create a component called `Message`.
It should return:
<h3>React is fun!</h3>

Then use it three times inside `App`.

---

## 10.
Create a component called `Box`.
It should return:
<div>Simple Box</div>

Use it two times inside `App`.

---

## 11.
Create a component called `Header`.
It should return:
<h1>Welcome to My App</h1>

Use it inside `App`.

---

## 12.
Create a component called `Content`.
It should return:
<p>This is the main content.</p>

Render it below `Header` inside `App`.

---

## 13.
Create a component called `Layout`.
It should return:
<div>
  <h2>Layout Section</h2>
</div>

Render `Layout` inside `App`.

---

## 14.
Create two components:
- `Navbar`
- `MainSection`

Render both inside `App`.

---

## 15.
Create three components:
- `Top`
- `Middle`
- `Bottom`

Render them in this order inside `App`.

---

## 16.
Create a component called `Card`.
It should return:
<div>Card Component</div>

Render it four times inside `App`.

---

## 17.
Create a component called `Notification`.
It should return:
<p>You have a new message</p>

Use it three times inside `App`.

---

## 18.
Create a component called `Section`.
It should return:
<section>Section Content</section>

Render it twice inside `App`.

---

## 19.
Create a component called `ButtonText`.
It should return:
<button>Click Me</button>

Render it two times inside `App`.

---

## 20.
Create five different components:
- `One`
- `Two`
- `Three`
- `Four`
- `Five`

Each should return different text.

Render all five inside `App`.
