![real estate (Banner (Landscape))](https://user-images.githubusercontent.com/91872149/195840981-85628085-8fab-43f5-98e6-de00b84fe1f5.png)

## _ReactJS or React or React.js_
-  _**A JavaScript Library for Building User Interface(UI)**_
- Created by **_Jordan Walke(Software Engineer at Facebook)_**
- Released in the year **_2013_**
- The **UI** is a point of **_Human Interaction and Communication_**
- It has Huge community on **_GitHub_**
- Maintained by **_Facebook_**

## _Why React?_ 🔯
- Component Based Approach
- Uses a Declarative Approach
  - <b>Basically there are two approaches:</b>
    - **_Imperative:_** means how you write code
    - **_Declarative:_** means what you write
- DOM updates are handled gracefully
- Reusable code
- Learn Once, Write anywhere
- React is designed for speed, speed of implementing the application simplicity and scalability(in simple terms Single Page Application(SPA))

## _JSX_
JSX where,<br>

**JS** stands for **_JavaScript_**<br>
**X** stands for **_HTML_**

<b>

```javascript
const homePage = <h1>Hello Home Page</h1>
```
</b>

Here, **`const homePgae`** : **_Javascript_** <br>
And **`<h1>Hello Home Page</h1>`** : **_HTML_**

## _Babel_
- **_Babel_** makes the wired looking **JSX code** into **_browser understandable code_**
- Convert **_JSX Code_** to **_Pure JavaScript Code_**
- **_ES6_** to Pure **_JavaScript_**
- It is knowns as Trans(rewatch and write the point)

`Watched upto 25:45`

## _using React in Simple HTML_
- Use the same Order of import written below

<b>
  
```javascript
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>React</title>
  </head>
  <body>
    <div class="root">Not Used</div>
    
    <script crossorigin src="https://unpkg.com/react@18/umd/react.development.js"></script>  // react
    <script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>  reactDOM
    <script src=" https://unpkg.com/@babel/standalone/babel.min.js"></script>
    <script type="text/babel">  // babel
      const homePage = <h1>Hello Home Page Anurag</h1>;
      const home = document.querySelector(".root");
      ReactDOM.render(homePage, home);
    </script>  
  </body>
  </html>
```
  
</b>
