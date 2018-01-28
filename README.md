# React-Redux-ES6-Basics

## Installation, Setup & Intro

### NodeJS & Npm
NodeJS - https://nodejs.org/ (Download & Install it, Long Term Support (LTS) recommended)

Check if NodeJS was correctly installed, opening a terminal and typing:
```javascript
node -v
```
### Choosing an IDE
- Sublime - https://www.sublimetext.com/3
- Atom - https://atom.io/
- Visual Studio Code - https://code.visualstudio.com/

### React Docs
- https://reactjs.org/
- https://github.com/facebook/react

### Babel y ES6 in CodePen 

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

## Start Coding!

### First React App
https://reactjs.org/docs/add-react-to-a-new-app.html
- VS Studio Code > View > Integrated Terminal 
```javascript
npm install -g create-react-app
create-react-app my-app

cd my-app
npm start
```

### Wireframing
- 30 Best Free Wireframing Tools 2018 - https://www.doublemesh.com/free-wireframing-tools/

#### Sample in Pencil:

WeatherLocation Component
![WeatherLocation Component](https://lh3.googleusercontent.com/pyhRr-p--K5G-jLuqVuAfKRwS3TtcaZeVtWBS4SJjXp0FYk6pgwSVi-zaEYaqyNpJS2F1XteA7AO7j7wLryj5UQbdU17nwlGfXXzP8eTaCRCpIPzw31nG5Nrq7iyGYvpjRNLF0QeivFTB3sguZGeITXfmmSzy2f7Us3041qlrRhd2_8mcyGbeqjKiLTMlqM2pwyCBEOpPt-7yqx3dwCphg3jw-2D8jP1MOh4sAYn8C9Ks2mjlrAMyOYRa5xUtARQ1IL9FieDLWr1UD0Ed2tjR5wOz-OLgM6hd7-dTM-dnRj5lK0xphpzy639oh1suSeCWflJ0vd9wALECLhMU3YMuXKMZwIXDOd_Amc6rb0MpzkD1ayuLF4NLKFGv3Ih8L30i6GUYJf2VI6pbKZM4MkLq1uXgHAIRzZLOlSV49msuuZeuom9HDhop6G45txr1JQ0QqhNUE9xbk5v99beCeDuOiTkcekjAJydJIJLbspVyNHW8o4CPiRVJlADRzMQHlKbf3rWQvmbSTXP-ovpo33ERNq_EWm5iD3HQ0CwHQjjdJMoFuV8AaSijyIj6n9hmKeM=w2462-h1746)

App Layout
![App Layout](https://lh3.googleusercontent.com/4AAYWaYNi7K5LKrx4Acn3bBdBBXhmabEie4gqCI_65POMn_y2HoMCpCOqlOH-JmbmKXq2GvYWVUr-Dp21qoKEuvriIekBGOLCkyJccqFy_oEDBXiqCd9I2bQ5xE6hnoAUkTRsPlTBOFrSKgpNChy0yJrTT9buBEoqwbk5wt8ZWhbKFQahecmViffsNYyl4edLPHQNMQANimuXuRW2jetJvHVcEFQkVVQJsogYKd4759VP8aDRAbclqo0YTZMEWl8A2ib0ceePRjlpqQI1eyq765Z3YYYQmmVUtnMtjUiktJSMpxy5c-4HKYb4BhNAgTSk_qsex9dkZDWseYTkFt6_RQb47i8HKlMABFVYZBTWBDH95cMo8Hfe_C7co0M89yqzaewcx4LHzVPb3mF9ChbOdL_Ov7YfDfzUzfTzMXQsbc1yHIz97JWexDRwRYiepI4S5j1npNPQJCkR_y2QXTX8jPMF7Nmaygp9Vm8MXaJdUdqCvSZLYlcLMdmkgDBk8uU-99jp84-D3rW4oFPTQJ1YCwFYV8XjoyptSSSKtH0G-0ZDWFI0VAmvxwNCi2joqjh=w2462-h1746)

ForecastItem Component
![ForecastItem Component](https://lh3.googleusercontent.com/KyQiwxsneZvZ1gU9eCRbZALYLEBads45i_wyAeUBdYSPNhzyu9zJ7LS8UMlp_qd_Q22RH-GlBR9jdqLIaw6J9xSzs1yxwde6K-9zUhz93KmwofJn4yJg1bFcU_rbnz6-VlV6e7FnZYRr95a-KVl9m9BIP5gMq0Wj_0mKh1LD7N4K4pdYhVgoR8vr6IZRaxy2kPA_PW6V0c1hLkVILNQNgya3Bn3HgqKXQmYoEACvmRf-5cQCdtr4WSR8eCv38Decs9e0CC1jT5uC5ter4lxhIXu5STUYfvsjapWfmO61r37qt5Iz4RMEEl1xdCyv5ERG_NtgEqR3mRgKpJzGSjE0IeRdo0Zb383IMCHGhcx2w-B7PwioG_di_-q-UTn-PxMIopkoC-zCEv1s0u7eLYVL0npRerCvHOhIEckrgR6OrpVgHux1Y4CAtCWgaQldSMd2h-3B3YmLGudjACOQIBCo0soC4HUuuJvw2cdBgAuwM7hwFsTmy6dXQdv0XY-a0pIGtwSNS_YsXh-k5QREAwYBB8921KiRBJKOlZlBY4oNLT2T2rQ0-atvPZFnuOkcg9BY=w2462-h1746)

### 1.1.- WeatherApp - Functional Component

WeatherLocation.js
```javascript
import React from 'react';

const WeatherLocation = () => 
(
    <div>"Weather Location"</div>
); 

export default WeatherLocation;
```

App.js
```javascript
import React, { Component } from 'react';
import WeatherLocation from './components/WeatherLocation';
import './App.css';

class App extends Component 
{
  render() 
  {
    return 
    (
      <div className="App">
        <WeatherLocation></WeatherLocation>
      </div>
    );
  }
}

export default App;

```


export default WeatherLocation;

#### Useful links
- https://codepen.io/
- http://babeljs.io/
- https://reactjs.org/docs/introducing-jsx.html

## References
- https://www.udemy.com/react-js-redux-es6-completo-de-0-a-experto-espanol/
- https://www.udemy.com/the-complete-react-and-redux-course-build-modern-apps/
- https://www.udemy.com/learn-and-understand-react-and-redux-i/
