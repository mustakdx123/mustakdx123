<!--
  Profile README for github.com/mustakdx123
  Visual assets live in ./assets (hand-written SVG, no external fonts).
  Local preview: node .preview/build.mjs, then open .preview/index.html
-->

<p align="center">
  <img src="./assets/header.svg" width="100%" alt="Mustakali MD — AI &amp; IoT Developer, Embedded Systems, ECE Student" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mustakali-md-327894352"><img src="https://img.shields.io/badge/LinkedIn-Mustakali%20MD-0A66C2?style=flat-square" alt="LinkedIn: Mustakali MD" /></a>
  <a href="https://github.com/mustakdx123?tab=repositories"><img src="https://img.shields.io/badge/GitHub-Repositories-30363d?style=flat-square&logo=github&logoColor=white" alt="GitHub repositories" /></a>
  <a href="https://smart-grain-analyzer.onrender.com/"><img src="https://img.shields.io/badge/Live%20demo-Smart%20Grain-0e7490?style=flat-square&logo=render&logoColor=white" alt="Live demo: Smart Grain Quality Detection" /></a>
</p>

<p align="center">
  Electronics and Communication Engineering student building where hardware meets software:<br />
  microcontrollers and sensors on one end, machine-learning models and live dashboards on the other.
</p>

<br />

## About me

- **Studying** — Electronics and Communication Engineering at P.A. College of Engineering
- **Focus** — AI, machine learning, IoT and embedded systems, especially ESP32-based devices
- **How I build** — end to end: sensor → microcontroller → cloud → dashboard
- **Exploring next** — smart health monitoring and AI-based fall detection

<br />

## Featured projects

<a href="https://github.com/mustakdx123/Smart-Grain-Quality-Detection-Using-Sensors-and-Image-Analysis-">
  <img src="./assets/project-smart-grain.svg" width="100%" alt="Smart Grain Quality Detection — prototype with live demo. Data flow: camera frame, TensorFlow.js, Socket.IO server, live dashboard." />
</a>

**Smart Grain Quality Detection** &nbsp;·&nbsp; `Prototype`

A camera page runs a TensorFlow.js image model directly in the browser every 10 seconds and classifies rice as **Good**, **Bad** or **Wet**. Each result and captured frame is streamed through a Node.js + Socket.IO server to a live dashboard that shows prediction history, a quality-distribution chart, and a moisture graph fed by an HTTP endpoint for sensor readings.

`TensorFlow.js` `JavaScript` `Node.js` `Express` `Socket.IO` `Chart.js` `Render`

[Repository](https://github.com/mustakdx123/Smart-Grain-Quality-Detection-Using-Sensors-and-Image-Analysis-) &nbsp;·&nbsp; [Live demo (camera)](https://smart-grain-analyzer.onrender.com/) &nbsp;·&nbsp; [Live dashboard](https://smart-grain-analyzer.onrender.com/dashboard.html)
<br /><sub>Hosted on Render's free tier, so the first load can take up to a minute while the server wakes up.</sub>

<br /><br />

<img src="./assets/project-smart-water.svg" width="100%" alt="Smart Water Desalination System — in development. Data flow: sensors and float switches, ESP32 control, Firebase, web dashboard." />

**Smart Water Desalination System** &nbsp;·&nbsp; `In development`

A small-scale, solar-powered RO water purification prototype. An ESP32 runs the feed pump automatically from float switches, with no-flow, maximum-runtime and float-plausibility safety interlocks and a watchdog. It reads TDS, pH, turbidity and flow sensors, shows live values on a 16×2 LCD, and uploads them to Firebase. A web dashboard displays live values and history graphs, and uses rule-based checks to flag faults and suggest troubleshooting steps.

`ESP32` `Arduino C++` `Firebase Realtime Database` `JavaScript` `Chart.js`

<sub>Repository not yet public.</sub>

<br />

## Tech stack

<sub>Only tools used in my own project code.</sub>

| Area | Tools |
| :-- | :-- |
| **Languages** | ![JavaScript](https://img.shields.io/badge/JavaScript-0d1117?style=flat-square&logo=javascript&logoColor=F7DF1E) ![C++ (Arduino)](https://img.shields.io/badge/C%2B%2B%20%28Arduino%29-0d1117?style=flat-square&logo=cplusplus&logoColor=00599C) ![HTML5](https://img.shields.io/badge/HTML5-0d1117?style=flat-square&logo=html5&logoColor=E34F26) ![CSS](https://img.shields.io/badge/CSS-0d1117?style=flat-square&logo=css&logoColor=1572B6) |
| **Embedded & IoT** | ![ESP32](https://img.shields.io/badge/ESP32-0d1117?style=flat-square&logo=espressif&logoColor=E7352C) ![Arduino](https://img.shields.io/badge/Arduino-0d1117?style=flat-square&logo=arduino&logoColor=00979D) |
| **AI / ML** | ![TensorFlow.js](https://img.shields.io/badge/TensorFlow.js-0d1117?style=flat-square&logo=tensorflow&logoColor=FF6F00) |
| **Web & real-time** | ![Node.js](https://img.shields.io/badge/Node.js-0d1117?style=flat-square&logo=nodedotjs&logoColor=5FA04E) ![Express](https://img.shields.io/badge/Express-0d1117?style=flat-square&logo=express&logoColor=white) ![Socket.IO](https://img.shields.io/badge/Socket.IO-0d1117?style=flat-square&logo=socketdotio&logoColor=white) ![Chart.js](https://img.shields.io/badge/Chart.js-0d1117?style=flat-square&logo=chartdotjs&logoColor=FF6384) |
| **Cloud & tools** | ![Firebase](https://img.shields.io/badge/Firebase-0d1117?style=flat-square&logo=firebase&logoColor=FFCA28) ![Render](https://img.shields.io/badge/Render-0d1117?style=flat-square&logo=render&logoColor=white) ![Git](https://img.shields.io/badge/Git-0d1117?style=flat-square&logo=git&logoColor=F05032) ![GitHub](https://img.shields.io/badge/GitHub-0d1117?style=flat-square&logo=github&logoColor=white) |

<br />

## Learning goals

<sub>What I'm working towards next. These are goals, not finished skills.</sub>

| Area | Goal |
| :-- | :-- |
| **AI / ML** | Go beyond running models: collect my own data, then train, evaluate and compare image and sensor models |
| **Edge AI** | Run small ML models directly on ESP32-class microcontrollers so devices can decide without the cloud |
| **Embedded systems** | Strengthen embedded C/C++ fundamentals: RTOS tasks, low-power design and reliable sensor calibration |
| **IoT** | Build secure, reliable device-to-cloud links, including MQTT and over-the-air firmware updates |
| **Software development** | Write cleaner, tested code with TypeScript, automated tests and good Git habits |
| **Real-world projects** | Finish and publish the Smart Water Desalination prototype, then prototype smart health monitoring and AI-based fall detection |

<br />

## GitHub activity

<details>
<summary><b>Show activity cards</b></summary>
<br />
<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=mustakdx123&custom_title=GitHub%20activity&hide=stars&hide_rank=true&show_icons=true&bg_color=0b1020&title_color=22d3ee&icon_color=a78bfa&text_color=cbd5e1&border_color=1e293b&border_radius=12" alt="GitHub activity card for mustakdx123: commits, pull requests and issues (third-party service)" />
  <img height="165" src="https://streak-stats.demolab.com/?user=mustakdx123&background=0B1020&border=1E293B&stroke=1E293B&ring=22D3EE&fire=A78BFA&currStreakNum=E2E8F0&sideNums=E2E8F0&currStreakLabel=22D3EE&sideLabels=94A3B8&dates=64748B&border_radius=12" alt="GitHub contribution streak card for mustakdx123 (third-party service)" />
</p>
<sub>These cards come from free third-party services (github-readme-stats and GitHub Readme Streak Stats) and can occasionally fail to load. The contribution graph on this profile page is drawn by GitHub itself.</sub>
</details>

<br />

## Connect

<a href="https://www.linkedin.com/in/mustakali-md-327894352"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge" alt="Connect on LinkedIn" /></a>
<a href="https://github.com/mustakdx123"><img src="https://img.shields.io/badge/GitHub-mustakdx123-30363d?style=for-the-badge&logo=github&logoColor=white" alt="GitHub profile: mustakdx123" /></a>

<br /><br />

<p align="center">
  <img src="./assets/footer.svg" width="100%" alt="Mustakali MD — sensors, silicon, insight" />
</p>
