# Progressive Budget Tracker

<p align="center">
<img src="https://img.shields.io/badge/license-MIT-yellow" />
</p>

<p align="center">
    <img src="https://img.shields.io/github/repo-size/kaidong-chr/HW19_Progressive_Budget_Tracker" />
    <img src="https://img.shields.io/github/languages/top/kaidong-chr/HW19_Progressive_Budget_Tracker"  />
    <img src="https://img.shields.io/github/issues/kaidong-chr/HW19_Progressive_Budget_Tracker" />
    <img src="https://img.shields.io/github/last-commit/kaidong-chr/HW19_Progressive_Budget_Tracker" >
</p>

### Overview
🔍<br />
Progressive budget tracking application that works online and offline. It takes advantage of cache storage to quick loading and as well as local storage (IndexedDB) to keep your data until you are online.

### Table of Contents
📑<br />
- [Overview](#Overview)
- [Demo](#Demo)
- [Prerequisites](#Prerequisites)
- [Usage](#Usage)
- [Installation](#Installation)
- [Questions](#Questions)
- [License](#License)

### Demo
🎥<br /> 
[Progressive Budget Tracker Live Link](https://progressive-budget-tracker-kai.herokuapp.com/)<br />
<img src="public\img\Budget_Tracker.gif" width="1000"><br />
<p align="center">
    <img src="https://img.shields.io/badge/JavaScript-blue" />
    <img src="https://img.shields.io/badge/-node.js-green" />
    <img src="https://img.shields.io/badge/-express-red" />
    <img src="https://img.shields.io/badge/mongoose-light" />
    <img src="https://img.shields.io/badge/morgan-yellow" />
    <img src="https://img.shields.io/badge/compression-gray" />
    <img src="https://img.shields.io/badge/lite server-orange" />
    <img src="https://img.shields.io/badge/dotenv-blue" />
</p>

### Prerequisites 
🔨<br />
  1. mongoDB / Compass
  2. VS Code
  3. npm packages: express, dotenv, morgan, mongoose, compression, lite-server

### Usage
💻<br />
In VS Code terminal, install the npm dependencies, then run <i>node server.js</i> in the terminal to start the app and create the budget database.<br />
In a browser, navigate to http://localhost:8080/ to view the site.<br />
You can add new budget items online, or bring up the dev console take the app offline in the Network tab, then add new budget items.<br />
Once you bring the app back online all your offline entries will persist, you can also check CompassDB to see these entries registered.<br />

### Installation
💾<br />
```
npm install express dotenv morgan mongoose compression lite-server
```

### Questions
  Contact me for questions at dongkai981@gmail.com<br />
  Find me on GitHub: https://github.com/kaidong-chr

### License
📘<br />
```
MIT License
Copyright (c) [2021] [Progressive Budget Tracker]
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```