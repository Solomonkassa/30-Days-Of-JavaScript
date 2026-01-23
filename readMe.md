# 30 Days Of JavaScript

| # Day |                                                                       Topics                                                                        |
| ----- | :-------------------------------------------------------------------------------------------------------------------------------------------------: |
| 01    |                                                             [Introduction](./readMe.md)                                                             |
| 02    |                                               [Data Types](./02_Day_Data_types/02_day_data_types.md)                                                |
| 03    |                             [Booleans, Operators, Date](./03_Day_Booleans_operators_date/03_booleans_operators_date.md)                             |
| 04    |                                            [Conditionals](./04_Day_Conditionals/04_day_conditionals.md)                                             |
| 05    |                                                     [Arrays](./05_Day_Arrays/05_day_arrays.md)                                                      |
| 06    |                                                       [Loops](./06_Day_Loops/06_day_loops.md)                                                       |
| 07    |                                                 [Functions](./07_Day_Functions/07_day_functions.md)                                                 |
| 08    |                                                    [Objects](./08_Day_Objects/08_day_objects.md)                                                    |
| 09    |                             [Higher Order Functions](./09_Day_Higher_order_functions/09_day_higher_order_functions.md)                              |
| 10    |                                           [Sets and Maps](./10_Day_Sets_and_Maps/10_day_Sets_and_Maps.md)                                           |
| 11    |                      [Destructuring and Spreading](./11_Day_Destructuring_and_spreading/11_day_destructuring_and_spreading.md)                      |
| 12    |                                  [Regular Expressions](./12_Day_Regular_expressions/12_day_regular_expressions.md)                                  |
| 13    |                             [Console Object Methods](./13_Day_Console_object_methods/13_day_console_object_methods.md)                              |
| 14    |                                         [Error Handling](./14_Day_Error_handling/14_day_error_handling.md)                                          |
| 15    |                                                    [Classes](./15_Day_Classes/15_day_classes.md)                                                    |
| 16    |                                                        [JSON](./16_Day_JSON/16_day_json.md)                                                         |
| 17    |                                            [Web Storages](./17_Day_Web_storages/17_day_web_storages.md)                                             |
| 18    |                                                  [Promises](./18_Day_Promises/18_day_promises.md)                                                   |
| 19    |                                                   [Closure](./19_Day_Closures/19_day_closures.md)                                                   |
| 20    |                                  [Writing Clean Code](./20_Day_Writing_clean_codes/20_day_writing_clean_codes.md)                                   |
| 21    |                                                          [DOM](./21_Day_DOM/21_day_dom.md)                                                          |
| 22    |                            [Manipulating DOM Object](./22_Day_Manipulating_DOM_object/22_day_manipulating_DOM_object.md)                            |
| 23    |                                        [Event Listeners](./23_Day_Event_listeners/23_day_event_listeners.md)                                        |
| 24    |                             [Mini Project: Solar System](./24_Day_Project_solar_system/24_day_project_solar_system.md)                              |
| 25    | [Mini Project: World Countries Data Visualization 1](./25_Day_World_countries_data_visualization_1/25_day_world_countries_data_visualization_1.md) |
| 26    | [Mini Project: World Countries Data Visualization 2](./26_Day_World_countries_data_visualization_2/26_day_world_countries_data_visualization_2.md) |
| 27    |                             [Mini Project: Portfolio](./27_Day_Mini_project_portfolio/27_day_mini_project_portfolio.md)                             |
| 28    |                          [Mini Project: Leaderboard](./28_Day_Mini_project_leaderboard/28_day_mini_project_leaderboard.md)                          |
| 29    |             [Mini Project: Animating Characters](./29_Day_Mini_project_animating_characters/29_day_mini_project_animating_characters.md)            |
| 30    |                                     [Final Projects](./30_Day_Mini_project_final/30_day_mini_project_final.md)                                      |

🧡🧡🧡 HAPPY CODING 🧡🧡🧡

<div align="center">
  <h1>30 Days Of JavaScript: Introduction</h1>
  
  <a class="header-badge" target="_blank" href="https://www.linkedin.com/company/jedan-code-academy/">
    <img src="https://img.shields.io/badge/style--5eba00.svg?label=LinkedIn&logo=linkedin&style=social">
  </a>
  <a class="header-badge" target="_blank" href="https://github.com/jedan-code-academy">
    <img alt="GitHub Follow" src="https://img.shields.io/github/followers/jedan-code-academy?style=social">
  </a>
  <a class="header-badge" target="_blank" href="https://www.jedanacademy.com/">
    <img src="https://img.shields.io/badge/Website-jedanacademy.com-blue">
  </a>

<sub>Created by:
<a href="https://www.jedanacademy.com/" target="_blank">Jedan Code Academy</a><br>
<small> January, 2026</small>
</sub>

<div>


</div>

</div>

[Day 2 >>](./02_Day_Data_types/02_day_data_types.md)

![Thirty Days Of JavaScript](./images/day_1_1.png)

- [30 Days Of JavaScript](#30-days-of-javascript)
- [📔 Day 1](#-day-1)
  - [Introduction](#introduction)
  - [Requirements](#requirements)
  - [Setup](#setup)
    - [Install Node.js](#install-nodejs)
    - [Browser](#browser)
      - [Installing Google Chrome](#installing-google-chrome)
      - [Opening Google Chrome Console](#opening-google-chrome-console)
      - [Writing Code on Browser Console](#writing-code-on-browser-console)
        - [Console.log](#consolelog)
        - [Console.log with Multiple Arguments](#consolelog-with-multiple-arguments)
        - [Comments](#comments)
        - [Syntax](#syntax)
      - [Arithmetics](#arithmetics)
    - [Code Editor](#code-editor)
      - [Installing Visual Studio Code](#installing-visual-studio-code)
      - [How to Use Visual Studio Code](#how-to-use-visual-studio-code)
  - [Adding JavaScript to a Web Page](#adding-javascript-to-a-web-page)
    - [Inline Script](#inline-script)
    - [Internal Script](#internal-script)
    - [External Script](#external-script)
    - [Multiple External Scripts](#multiple-external-scripts)
  - [Introduction to Data Types](#introduction-to-data-types)
    - [Numbers](#numbers)
    - [Strings](#strings)
    - [Booleans](#booleans)
    - [Undefined](#undefined)
    - [Null](#null)
  - [Checking Data Types](#checking-data-types)
  - [Comments Again](#comments-again)
  - [Variables](#variables)
- [💻 Day 1: Exercises](#-day-1-exercises)

# 📔 Day 1

## Introduction

**Congratulations** on deciding to participate in the 30 days of JavaScript programming challenge. This comprehensive curriculum, created by **Jedan Code Academy**, will guide you from JavaScript fundamentals to advanced concepts. By the end of this challenge, you'll have a solid understanding of JavaScript and be able to build real-world applications.

**30DaysOfJavaScript** is designed for both beginners and intermediate developers. JavaScript powers the modern web, enabling interactive websites, mobile apps, desktop applications, games, and even server-side programming with Node.js. Mastering JavaScript opens doors to numerous opportunities in web development, mobile development, and beyond.

This curriculum follows a structured, day-by-day approach with hands-on exercises and projects. Each day builds upon the previous, ensuring steady progress. The content is written in clear, accessible language with practical examples.

## Requirements

No prior programming experience is needed! You just need:

1. **Dedication** to commit to daily learning
2. **A computer** (Windows, Mac, or Linux)
3. **Internet connection**
4. **A modern web browser** (Chrome recommended)
5. **A code editor** (VS Code recommended)

## Setup

### Install Node.js

Node.js allows you to run JavaScript outside the browser. Download it from [nodejs.org](https://nodejs.org/).

![Node download](images/download_node.png)

After downloading, run the installer. Verify installation by opening your terminal/command prompt:

```bash
node --version
# Should display something like: v18.17.0 or higher
```

### Browser

#### Installing Google Chrome

Download and install [Google Chrome](https://www.google.com/chrome/). Chrome has excellent developer tools that we'll use throughout this course.

#### Opening Google Chrome Console

The console is where you can test JavaScript code directly. Open it using:

- **Windows/Linux:** `Ctrl + Shift + J`
- **Mac:** `Cmd + Option + J`

Or right-click on any webpage → "Inspect" → "Console" tab.

#### Writing Code on Browser Console

Let's write our first JavaScript code:

```javascript
console.log('Hello from Jedan Code Academy!');
```

##### Console.log with Multiple Arguments

```javascript
console.log('Welcome', 'to', '30 Days', 'of', 'JavaScript');
console.log('Jedan Code Academy', 2026);
```

##### Comments

```javascript
// Single line comment

/*
Multi-line comment
This is the 30DaysOfJavaScript challenge
Created by Jedan Code Academy
*/
```

##### Syntax

JavaScript requires proper syntax. Common mistakes include missing parentheses, quotes, or semicolons:

```javascript
// Incorrect
console.log('Hello world

// Correct
console.log('Hello world');
```

##### Arithmetics

```javascript
console.log(10 + 5);      // 15
console.log(20 - 8);      // 12
console.log(6 * 7);       // 42
console.log(50 / 5);      // 10
console.log(17 % 5);      // 2 (remainder)
console.log(2 ** 4);      // 16 (2 to the power of 4)
```

### Code Editor

#### Installing Visual Studio Code

Download [VS Code](https://code.visualstudio.com/), a free, powerful editor with great JavaScript support.

![VSCode](images/vscode.png)

#### How to Use Visual Studio Code

1. Open VS Code
2. Create a new folder for the challenge
3. Create your first JavaScript file (e.g., `day1.js`)
4. Install the "Live Server" extension for running web pages

## Adding JavaScript to a Web Page

JavaScript can be added to HTML in three ways:

### Inline Script

```html
<!DOCTYPE html>
<html>
<head>
    <title>Jedan Academy - Day 1</title>
</head>
<body>
    <button onclick="alert('JavaScript is awesome!')">Click Me</button>
</body>
</html>
```

### Internal Script

```html
<!DOCTYPE html>
<html>
<head>
    <title>Jedan Academy - Day 1</title>
    <script>
        console.log('Learning JavaScript with Jedan Code Academy');
    </script>
</head>
<body>
    <h1>Welcome to 30DaysOfJavaScript</h1>
</body>
</html>
```

### External Script

Create `script.js`:
```javascript
console.log('External JavaScript file loaded');
```

HTML file:
```html
<!DOCTYPE html>
<html>
<head>
    <title>External JavaScript</title>
</head>
<body>
    <h1>Jedan Code Academy</h1>
    <script src="script.js"></script>
</body>
</html>
```

### Multiple External Scripts

```html
<script src="script1.js"></script>
<script src="script2.js"></script>
```

## Introduction to Data Types

JavaScript has several primitive data types:

### Numbers
```javascript
let age = 25;
let price = 19.99;
let temperature = -5;
```

### Strings
```javascript
let name = 'Jedan Academy';
let message = "Learn JavaScript";
let greeting = `Hello, ${name}!`; // Template literal
```

### Booleans
```javascript
let isLoggedIn = true;
let hasPermission = false;
let isGreater = 10 > 5; // true
```

### Undefined
```javascript
let username; // undefined
let value = undefined;
```

### Null
```javascript
let emptyValue = null;
```

## Checking Data Types

Use the `typeof` operator:
```javascript
console.log(typeof 'Jedan Academy'); // "string"
console.log(typeof 42);              // "number"
console.log(typeof true);            // "boolean"
console.log(typeof undefined);       // "undefined"
console.log(typeof null);            // "object" (historical quirk)
```

## Comments Again

```javascript
// Good comments explain WHY, not WHAT

/*
Project: 30DaysOfJavaScript
Author: Jedan Code Academy
Date: January 2026
Purpose: JavaScript learning curriculum
*/
```

## Variables

Variables store data. Use `let` for variables that change, `const` for constants:

```javascript
// Using let (can be reassigned)
let studentName = 'Alex';
studentName = 'Jordan'; // OK

// Using const (cannot be reassigned)
const PI = 3.14159;
// PI = 3.14; // Error!

// Valid variable names
let firstName;
let user_age;
let $price;
let _internalValue;
let totalAmount2026;

// Invalid variable names
// let 1stPlace;     // Cannot start with number
// let user-name;    // No hyphens
// let let;          // Cannot use reserved words
```

**Variable Declaration Examples:**
```javascript
// Student information
const academy = 'Jedan Code Academy';
let course = '30 Days of JavaScript';
let studentCount = 1000;
let isEnrolled = true;
let nextSession = null;
let startDate; // undefined

console.log(`Academy: ${academy}`);
console.log(`Course: ${course}`);
console.log(`Students: ${studentCount}`);
```

# 💻 Day 1: Exercises

1. Write a single line comment saying: `// Comments make code readable`
2. Write another single comment: `// Welcome to Jedan Code Academy's 30DaysOfJavaScript`
3. Write a multiline comment describing the importance of comments
4. Create `variables.js` and declare variables with different data types
5. Create `datatypes.js` and use `typeof` to check each variable's type
6. Declare four variables without assigning values
7. Declare four variables with assigned values
8. Declare your information in multiple lines:
   ```javascript
   let firstName = 'YourName';
   let lastName = 'YourLastName';
   let country = 'YourCountry';
   let age = 25;
   ```
9. Declare the same information in a single line
10. Create `ageComparison.js`:
    ```javascript
    let myAge = 25;
    let yourAge = 30;
    console.log(`I am ${myAge} years old.`);
    console.log(`You are ${yourAge} years old.`);
    ```

## Exercise Solutions

### variables.js
```javascript
// Exercise 4: Different data types
let academyName = 'Jedan Code Academy'; // string
let studentCount = 500;                 // number
let isActive = true;                    // boolean
let upcomingCourse;                     // undefined
let previousBatch = null;               // null
```

### datatypes.js
```javascript
// Exercise 5: Check data types
console.log(typeof 'Jedan Academy'); // string
console.log(typeof 2026);            // number
console.log(typeof true);            // boolean
console.log(typeof undefined);       // undefined
console.log(typeof null);            // object
```

### Additional Practice
```javascript
// Exercise 6: Unassigned variables
let variable1;
let variable2;
let variable3;
let variable4;

// Exercise 7: Assigned variables
let courseName = 'JavaScript Fundamentals';
let duration = 30;
let isFree = true;
let rating = 4.8;

// Exercise 8: Multi-line declaration
const academy = 'Jedan Code Academy';
const founded = 2023;
const location = 'Online';
const courses = ['JavaScript', 'Python', 'Web Development'];

// Exercise 9: Single line (not recommended for readability)
let name = 'Alex', role = 'Student', level = 'Beginner', progress = 0;
```

🎉 **EXCELLENT WORK ON COMPLETING DAY 1!** 🎉

You've taken the first step in your JavaScript journey with Jedan Code Academy. Tomorrow we'll dive deeper into data types and operators.

[Day 2 >>](./02_Day_Data_types/02_day_data_types.md)

---

<div align="center">
  <h3>Jedan Code Academy - Empowering Developers Worldwide</h3>
  <p>Visit us at <a href="https://www.jedanacademy.com">jedanacademy.com</a></p>
</div>
