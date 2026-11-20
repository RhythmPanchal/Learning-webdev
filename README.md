# Learning-webdev

> A small stopwatch-style timer built with plain HTML, CSS and JavaScript while learning web development.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## What it is

A single-page timer with a circular clock face and two buttons. No frameworks, no build step, no dependencies.

## Features

- **START / PAUSE / CONTINUE**: one button cycles through the three states, ticking once per second.
- **STOP**: resets the counter and returns the start button to START.
- Time is shown as zero-padded `HH:MM:SS`.
- Background images for the page and the round clock face, styled in CSS.

## Project layout

```
index.html    page markup
Timer.css     styling
Timer.js      timer logic
body-bg.jpg   page background
bg2.jpg       clock face background
```

## Getting started

There is nothing to install. Clone the repo and open `index.html` in a browser:

```bash
git clone https://github.com/RhythmPanchal/Learning-webdev.git
cd Learning-webdev
open index.html    # macOS; on other systems just double-click the file
```

## Status

A learning exercise. Known rough edges: the counter starts displaying from `00:00:00` only after the first tick, and the logic relies on implicit global variables.
