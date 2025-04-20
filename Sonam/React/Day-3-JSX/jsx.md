# Learning JSX in React

Today, I learned about **JSX (JavaScript XML)** in React.  
JSX is a syntax extension for JavaScript that allows us to write HTML-like code inside JavaScript. It looks like HTML, but it can also include JavaScript expressions.

## 📌 What I Understood

- JSX makes it easier to write and understand UI code in React.
- It is not exactly HTML, but looks very similar.
- We can **embed JavaScript** using `{ }` curly braces.
- JSX needs to be compiled (usually by Babel) to regular JavaScript that browsers can understand.
- Components must return a **single parent element**.

## ✅ Example of JSX

```jsx
function Hello() {
  const name = "Sonam";
  return (
    <div>
      <h1>Hello, {name}!</h1>
      <p>This is my first JSX component.</p>
    </div>
  );
}

export default Hello;


🧠 Key Points
Use className instead of class in JSX.

JSX allows you to use all the power of JavaScript inside UI code.

It improves readability and allows writing UI in a declarative way.

💡 Conclusion
JSX is not required in React, but it makes writing React components much easier and cleaner.
Today, I understood the basics of JSX and how to use it in a simple React component.