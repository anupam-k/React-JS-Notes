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

## _Using React in Simple HTML_
- Use the same Order of import written below
  - **_React_**
  - **_ReactDOM_**
  - **_Babel_**

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

## _How to write more than one element in React : Use a Div_ 
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
    <script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>  // reactDOM
    <script src=" https://unpkg.com/@babel/standalone/babel.min.js"></script>
    <script type="text/babel">  // babel
      const home = document.querySelector(".root");
      
      const homePage = (
        <div>
            <h1>Hello Home Page Anurag</h1>
            <h2>Hello H1</h2>
        </div>
      );
      ReactDOM.render(homePage,home); 
    </script>  
  </body>
  </html>
```

## _Output_
![image](https://user-images.githubusercontent.com/91872149/195966006-b1420d62-f1e9-4d42-82ff-fb7e29597ef4.png)


</b>

## _How to Make Componenets in React and Display them_
# _"When we have to enject anything inside jsx we always have to use curly braces"_

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
    
    <script crossorigin src="https://unpkg.com/react@18/umd/react.development.js"></script>  
    <script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>  
    <script src=" https://unpkg.com/@babel/standalone/babel.min.js"></script>
    <script type="text/babel">  
      const home = document.querySelector(".root");
      
      const Navbar = (
        <div>
            <p>Home</p>
            <p>About</p>
        </div>
      );
      const Main = (
        <div>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>
      );
      const Footer = (
        <div>
            <p>CopyRight 2022 Anurag Tiwari</p>
        </div>
      );

      const App = (
        <div>
          {Navbar} {Main} {Footer}
        </div>
      );
      
      ReactDOM.render(App,home); 
    </script>  
  </body>
  </html>
```

## _Output_
![image](https://user-images.githubusercontent.com/91872149/195965953-d0ecbcd9-9ad9-4fbb-85ac-2a35e4508040.png)

</b>

## _How to enject CSS iniside HTML(React)_

- Write Style tag inside div
- **First Curly Braces:** When we have to enject anything inside jsx we always have to use curly braces
- **Second Curly Braces:** This is my CSS in the form of Key:Value Pair 
<br>
 - Whenever we write css, we always write the <b><i>firstword followed by Capital second word</i></b> <br>
 
e.g. fontSize, fontWeight, etc.
<br><br>


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
    
    <script crossorigin src="https://unpkg.com/react@18/umd/react.development.js"></script>  
    <script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>  
    <script src=" https://unpkg.com/@babel/standalone/babel.min.js"></script>
    <script type="text/babel">
      const home = document.querySelector(".root");
      
      const Navbar = (
        <div style={{color: "red", fontSize: "25px"}}>
            <p>Home</p>
            <p>About</p>
        </div>
      );
      const Main = (
        <div>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>
      );
      const Footer = (
        <div>
            <p>CopyRight 2022 Anurag Tiwari</p>
        </div>
      );

      const App = (
        <div>
          {Navbar} {Main} {Footer}
        </div>
      );
      
      ReactDOM.render(App,home); 
    </script>  
  </body>
  </html>
```

</b>

## _Output_
![image](https://user-images.githubusercontent.com/91872149/195966490-1ab0bde8-4542-4015-8b7f-91d800ba6bda.png)


## _Another Method to Write CSS_

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
    
    <script crossorigin src="https://unpkg.com/react@18/umd/react.development.js"></script>  
    <script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>  
    <script src=" https://unpkg.com/@babel/standalone/babel.min.js"></script>
    <script type="text/babel">
      const home = document.querySelector(".root");
      const csss = { color: "blue", fontSize: "25px" };
      const Navbar = (
        <div style={csss}>
            <p>Home</p>
            <p>About</p>
        </div>
      );
      const Main = (
        <div>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>
      );
      const Footer = (
        <div>
            <p>CopyRight 2022 Anurag Tiwari</p>
        </div>
      );

      const App = (
        <div>
          {Navbar} {Main} {Footer}
        </div>
      );
      
      ReactDOM.render(App,home); 
    </script>  
  </body>
  </html>
```
</b>

## _Output_
![image](https://user-images.githubusercontent.com/91872149/195966531-a8f18dec-b052-4897-af01-dde3b60f8f8c.png)

