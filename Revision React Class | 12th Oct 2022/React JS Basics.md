# _React JS_ 🔯
## _📌 node_modules_
- All the packages comes from **_Node Package Manager(NPM)_**

## _📌 manifest.json_
- Wheneven we want to create **_Progressive Web App(PWA)_**, the we use this file

## _📌 robots.txt_
- Whenever we search on Google, Google is able to load that exists, all that **_information_** is written here
- Basically, it is to **_Track our Website_**

## _📌 src_
- All that you want to do inside your React App, that piece of code you write inside **_src_**

## _📌 app.js_
- This is the **_first thing_** that **_your browser_** will load inside **_index.js_**

## _📌 app.test.js_
- Whenever you write **_test cases for your application_**, it is written in **_app.test.js_**

## _📌 .gitignore_
- All the things which I want git to not track, those are written in **_.gitignore_**

## _📌 package.json_
- Everything you installed using npm inside your project get written inside **_package.json_**

## _📌 package-lock.json_
- **_List of all the packages_** and the **_version of package getting installed_**
---

## _If we delete everything inside src folder then_
 - React will search for index.js, as soon as we make an index.js file, the react-app will be up and running
 
## _index.js_

<b>

```javascript
import React from "react";
import ReactDOM from "react-dom";

const Home = <h1>Hello World!</h1>;

ReactDOM.render(Home, document.getElementById(".root");
```
</b>

## _Output_
This will give Output as Hello World Written in H1 heading.

## _Note:_
- Now, after **_Version 17_** if we don't write `import React from "react";`, the system will understand automatically 

- Always and always the **_Name of the function will start from Capital Alphabet_**

<b>

```javascript
// import React from "react";
import ReactDOM from "react-dom";

function App(){ 
  return <h1>Hello World!</h1>;
}

ReactDOM.render(<App />, document.getElementById(".root");
```

- In case of function, function name will come instead of Home and that to in `< />` this manner
</b>

## _Create a Component_
## _components/App.js_

<b>

```javascript
function App(){ 
  return <h1>Hello World!</h1>;
}

export default App;
```

## _index.js_

```javascript
// import React from "react";
import ReactDOM from "react-dom";
import App from "./components/App";

ReactDOM.render(<App />, document.getElementById(".root");
```
</b>

