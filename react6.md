REACT BASIC TO ADVANCE PART 6 


Sure 👍

### 🧩 *What is JSX?*

*JSX (JavaScript XML)* is a special *syntax* used in *React* to describe what the UI should look like.
It looks like *HTML, but it’s actually **JavaScript* under the hood.

---

### 💬 Example

jsx
const element = <h1>Hello, world!</h1>;


Here,

* <h1>Hello, world!</h1> is *JSX*.
* It looks like HTML, but it’s not — it’s *JavaScript that creates a React element*.

---

### ⚙ *How It Works*

The browser *cannot understand JSX* directly.
So, a tool like *Babel* converts it into normal JavaScript before running:

js
const element = React.createElement('h1', null, 'Hello, world!');


---

### 💡 *Why JSX is Useful*

* It makes React code easier to *read and write*.
* You can mix *HTML-like structure* and *JavaScript logic* together.

Example:

jsx
const name = "Azam";
const element = <h1>Hello, {name}!</h1>;


👉 Output: *Hello, Azam!*

The {} allows you to write *JavaScript expressions* inside JSX.

---

### 📘 *Key Points*

1. JSX looks like HTML but is *not HTML*.
2. JSX must have *one parent element*.
3. You can write **JavaScript inside {}**.
4. It is *converted into JavaScript* before running.

---

So simply put:

> *JSX = A JavaScript syntax that looks like HTML and helps you write React components easily.*
