# React-Redux-ES6-Basics

## Installation, Setup & Intro

<details><summary>Show Sections - Installation, Setup & Intro</summary>
<p>

### NodeJS & Npm

<details><summary>Show NodeJS & Npm</summary>
<p>
  
NodeJS - https://nodejs.org/ (Download & Install it, Long Term Support (LTS) recommended)

Check if NodeJS was correctly installed, opening a terminal and typing:
```javascript
node -v
```
</p>
</details>

### Choosing an IDE

<details><summary>Show Choosing an IDE</summary>
<p>
  
- Sublime - https://www.sublimetext.com/3
- Atom - https://atom.io/
- Visual Studio Code - https://code.visualstudio.com/

</p>
</details>

### React Docs

<details><summary>Show React Docs</summary>
<p>
  
- https://reactjs.org/
- https://github.com/facebook/react

</p>
</details>

### Babel y ES6 in CodePen 

<details><summary>Show Babel y ES6 in CodePen</summary>
<p>

#### First Steps
- Go to https://codepen.io/
- Create > New Pen > Settings > Javascript > Preprocessor - "Babel" > Quick-add - "React" > Quick-add - "React DOM"
- HelloWorld:

HTML
```javascript
<div id="root">
  
</div>
```
JS
```javascript
ReactDOM.render(<h1>Hello World!!</h1>, document.getElementById('root'));
```
#### Useful links
- https://codepen.io/
- http://babeljs.io/
- https://reactjs.org/docs/introducing-jsx.html

</p>
</details>

</p>
</details>

## 1.- Start Coding!

<details><summary>Show Sections - 1.- Start Coding!</summary>
<p>
  
### First React App

<details><summary>Show First React App</summary>
<p>

https://reactjs.org/docs/add-react-to-a-new-app.html
- VS Studio Code > View > Integrated Terminal 
```javascript
npm install -g create-react-app
create-react-app my-app

cd my-app
npm start
```

</p>
</details>

### Wireframing

<details><summary>Show Wireframing</summary>
<p>
  
- 30 Best Free Wireframing Tools 2018 - https://www.doublemesh.com/free-wireframing-tools/

#### Sample in Pencil:

WeatherLocation Component
![WeatherLocation Component](https://lh3.googleusercontent.com/pyhRr-p--K5G-jLuqVuAfKRwS3TtcaZeVtWBS4SJjXp0FYk6pgwSVi-zaEYaqyNpJS2F1XteA7AO7j7wLryj5UQbdU17nwlGfXXzP8eTaCRCpIPzw31nG5Nrq7iyGYvpjRNLF0QeivFTB3sguZGeITXfmmSzy2f7Us3041qlrRhd2_8mcyGbeqjKiLTMlqM2pwyCBEOpPt-7yqx3dwCphg3jw-2D8jP1MOh4sAYn8C9Ks2mjlrAMyOYRa5xUtARQ1IL9FieDLWr1UD0Ed2tjR5wOz-OLgM6hd7-dTM-dnRj5lK0xphpzy639oh1suSeCWflJ0vd9wALECLhMU3YMuXKMZwIXDOd_Amc6rb0MpzkD1ayuLF4NLKFGv3Ih8L30i6GUYJf2VI6pbKZM4MkLq1uXgHAIRzZLOlSV49msuuZeuom9HDhop6G45txr1JQ0QqhNUE9xbk5v99beCeDuOiTkcekjAJydJIJLbspVyNHW8o4CPiRVJlADRzMQHlKbf3rWQvmbSTXP-ovpo33ERNq_EWm5iD3HQ0CwHQjjdJMoFuV8AaSijyIj6n9hmKeM=w2462-h1746)

App Layout
![App Layout](https://lh3.googleusercontent.com/4AAYWaYNi7K5LKrx4Acn3bBdBBXhmabEie4gqCI_65POMn_y2HoMCpCOqlOH-JmbmKXq2GvYWVUr-Dp21qoKEuvriIekBGOLCkyJccqFy_oEDBXiqCd9I2bQ5xE6hnoAUkTRsPlTBOFrSKgpNChy0yJrTT9buBEoqwbk5wt8ZWhbKFQahecmViffsNYyl4edLPHQNMQANimuXuRW2jetJvHVcEFQkVVQJsogYKd4759VP8aDRAbclqo0YTZMEWl8A2ib0ceePRjlpqQI1eyq765Z3YYYQmmVUtnMtjUiktJSMpxy5c-4HKYb4BhNAgTSk_qsex9dkZDWseYTkFt6_RQb47i8HKlMABFVYZBTWBDH95cMo8Hfe_C7co0M89yqzaewcx4LHzVPb3mF9ChbOdL_Ov7YfDfzUzfTzMXQsbc1yHIz97JWexDRwRYiepI4S5j1npNPQJCkR_y2QXTX8jPMF7Nmaygp9Vm8MXaJdUdqCvSZLYlcLMdmkgDBk8uU-99jp84-D3rW4oFPTQJ1YCwFYV8XjoyptSSSKtH0G-0ZDWFI0VAmvxwNCi2joqjh=w2462-h1746)

ForecastItem Component
![ForecastItem Component](https://lh3.googleusercontent.com/KyQiwxsneZvZ1gU9eCRbZALYLEBads45i_wyAeUBdYSPNhzyu9zJ7LS8UMlp_qd_Q22RH-GlBR9jdqLIaw6J9xSzs1yxwde6K-9zUhz93KmwofJn4yJg1bFcU_rbnz6-VlV6e7FnZYRr95a-KVl9m9BIP5gMq0Wj_0mKh1LD7N4K4pdYhVgoR8vr6IZRaxy2kPA_PW6V0c1hLkVILNQNgya3Bn3HgqKXQmYoEACvmRf-5cQCdtr4WSR8eCv38Decs9e0CC1jT5uC5ter4lxhIXu5STUYfvsjapWfmO61r37qt5Iz4RMEEl1xdCyv5ERG_NtgEqR3mRgKpJzGSjE0IeRdo0Zb383IMCHGhcx2w-B7PwioG_di_-q-UTn-PxMIopkoC-zCEv1s0u7eLYVL0npRerCvHOhIEckrgR6OrpVgHux1Y4CAtCWgaQldSMd2h-3B3YmLGudjACOQIBCo0soC4HUuuJvw2cdBgAuwM7hwFsTmy6dXQdv0XY-a0pIGtwSNS_YsXh-k5QREAwYBB8921KiRBJKOlZlBY4oNLT2T2rQ0-atvPZFnuOkcg9BY=w2462-h1746)

</p>
</details>

### Plugins & Extensions

<details><summary>Show Plugins & Extensions</summary>
<p>
  
- VS Code > Extensions - "vscode-icons", "Reactjs code snippets" - Install

</p>
</details>

### ES6 Arrow Functions

<details><summary>Show ES6 Arrow Functions</summary>
<p>
  
- Go to https://codepen.io/
- Create > New Pen > Settings > Javascript > Preprocessor - "Babel" > Quick-add - "React" > Quick-add - "React DOM"

JS
```javascript
function greeting(name){
  return "Hello " + name;
}

console.log(greeting("Joe"))
```

JS - Arrow Function
```javascript
const greeting = (name) => {
  return "Hello " + name + "! (with arrow function)";
}

console.log(greeting("Joe"))
```

JS - Arrow Function - 1 Line can be with () without "return"
```javascript
const greeting = (name) => ("Hello " + name + "! (with arrow function)")

console.log(greeting("Joe"))
```

</p>
</details>

### 1.1.- WeatherApp - Functional Component

<details><summary>Show 1.1.- WeatherApp - Functional Component</summary>
<p>

/components/WeatherLocation.js
```javascript
import React from 'react';

const WeatherLocation = () => (
    <div>"Weather Location"</div>
); 

export default WeatherLocation;
```

App.js
```javascript
import React, { Component } from 'react';
import WeatherLocation from './components/WeatherLocation';
import './App.css';

class App extends Component {
  render() {
    return (
      <div className="App">
        <WeatherLocation></WeatherLocation>
      </div>
    );
  }
}

export default App;
```

</p>
</details>

### 1.2.- WeatherApp - Components & Imports

<details><summary>Show 1.2.- WeatherApp - Components & Imports</summary>
<p>
  
/components/Location.js
```javascript
import React from 'react';

const Location = () => (
    <div><h1>New York</h1></div>
);

export default Location;
```

/components/WeatherData.js
```javascript
import React from 'react';

const WeatherData = () => (<div>WeatherData</div>)

export default WeatherData;
```

/components/WeatherLocation.js
```javascript
import React        from 'react';
import Location     from './Location';
import WeatherData  from './WeatherData';

const WeatherLocation = () => (
    <div>
        <Location/>
        <WeatherData/>
    </div>
); 

export default WeatherLocation;
```

</p>
</details>

### 1.3.- WeatherApp - Components WeatherExtraInfo & WeatherTemperature

<details><summary>Show 1.3.- WeatherApp - Components WeatherExtraInfo & WeatherTemperature</summary>
<p>
  
/components/WeatherExtraInfo.js
```javascript
import React from 'react';

const WeatherExtraInfo = () => (
<div>Extra Info</div>
);

export default WeatherExtraInfo;
```

/components/WeatherTemperature.js
```javascript
import React from 'react';

const WeatherTemperature = () => (
<div><span>12 ºC</span></div>
);

export default WeatherTemperature;
```

/components/WeatherData.js
```javascript
import React                from 'react';
import WeatherTemperature   from './WeatherTemperature'
import WeatherExtraInfo     from './WeatherExtraInfo'

const WeatherData = () => (
<div>
    <WeatherTemperature/>
    <WeatherExtraInfo/>
</div>
)

export default WeatherData;
```

</p>
</details>


</p>
</details>

## References
- https://www.udemy.com/react-js-redux-es6-completo-de-0-a-experto-espanol/
- https://www.udemy.com/the-complete-react-and-redux-course-build-modern-apps/
- https://www.udemy.com/learn-and-understand-react-and-redux-i/
