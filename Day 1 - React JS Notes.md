# _React JS_ ⚛️
- <b>React</b> begins with <b> ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)</b>

## _Runtime Environment for JS_ ⚡
- <b>_Deno_</b> 
- <b>_Bun_</b>

## <b>_Versions in Node JS:_</b><br>
- <b>LTS(Long Term Support)</b>: Has a release Cycle and Doesn't update everytime<br>
- <b>Current</b>: Updates very quickly as soon as any update is pushed with new features(Constant Update)


🌟 **Note:**  **Node** did some breaking changes after **_Version 12_**

Before **Version 12** Node used to have some special function like **firebase functions** for free<br>
But After **Version 12** these function use to <b>take charge</b> for using them

### 🌟 _Go and study about_ : _Child Processes_

- Node also gives npm

## <b>_Full Forms_</b>
- **npx:** Node Package Execute<br>
- **npm:** Node Package Manager<br>
---
- Sometimes your npm version might be different and node version might be different

## _Creating a React App_

Earlier we use to install the global library, it was almost similar to installing a software in your system
> npm -g install create-react-app

<br>
Now you can imagine, you always have to install this whenever you want to create a react app<br>
This will consume a lot of space, that's a huge distadvantage<br>
Or if there is an update in the create react app then we have to reinstall it or kind of update it<br>
Earlier people use to do this way

### _Q. **So for each project we have to install React again and again?**_ <br>
<b>No</b>, we have to install it <b>one time globally</b>, the it <b>works anytime</b> atleast on the system<br>

<b>But there could be a better way</b><br>
There was <b>another package introduced</b> which was <b>npx(node package exxecuter)</b><br>
With <b>npx</b> you <b>don't need to install</b> anything on the <b>system</b>,<br>
it just that **you write and command** and it will **execute that command directly from the internet**
<br>
The same way it installs other technology like <b>react-native too</b>

## _Command to create a React App_
> <b>npx create-react-app appName</b>

## _Command to start the Server_
> <b>npm start</b>

Whenever we write _<b>npm start</b>_, first it goes to _<b>package.json</b>_ and see that npm start means _<b>react-scripts start</b>_. In other way we can say <b>_npm start_</b> is short form of _<b>react-scripts start</b>_.<br>
All this comes from the <b>_react-scripts_</b>.

## _index.html_
- the entirety of application is dependent on _<b>Javascript</b>_
- there is only one page that is _index.html_ which is a proof that react is **_Single Page Application(SPA)_**
- the Application always loads from index page only

## _src/index.js_
- **_React_** doesn't use an **_Ordinary DOM_**, instead it uses a **_Virtual DOM_**
- it is using `root` by using `document.getElementById('root')`

## _Study about_
- Hydration Option
- createRoot
- ReactDOM
- render
- React.StrictMode

## _When we delete everything from src folder_


