# WebDev Projectday


# Timetable

No worries - this is a flexible timeframe

**Time** | **Block**
---------|---------
09:30 - 10:30 | Lesson
10:45 - 12:00 | Lesson
12:00 - 13:00 | Lunch Break
13:00 - 14:45 | Lesson
15:00 - 16:30 | Lesson


# Web Development Project Day

* Welcome to our web development project day!
* Today we'll be building a basic portfolio page from scratch.
* Let's get started!


# What we gonna learn today

- The workflow of web-devs
- The proceess of web-projects
- How to figure things out (problemsolver)


# Create a GitHub Account

- Go to [github.com](http://github.com) and sign up for an account
- Fill out the registration form with your details
- Verify your email address to activate your account
- Create a new repository named: `username.github.io` for our project


# Create a New HTML File

- Download vscode
- Download the index.html from before
- Put it into a seperated project folder. I recommend `~/dev/username.github.io`
- Open that folder with VsCode
- Add the basic HTML structure:
```html
<!DOCTYPE html>
<html>
<head>
        <title>My Portfolio</title>
</head>
<body>
        <!-- content will go here -->
</body>
</html>
```


# Before we start coding...
- Make a rough wireframe
- Think about what you wanna tell
- Think about the perspective of a HR person


# Build a Basic Portfolio Page

- Add a heading and introduction to our portfolio page:
```html
<h1>Welcome to my portfolio!</h1>
<p>This is a brief overview of my work...</p>
```
- Add a section for showcasing projects:
```html
<section>
        <h2>My Projects</h2>
        <ul>
                <!-- project list items will go here -->
        </ul>
</section>
```
- Style our page with basic CSS:
```css
body {
        background-color: #f2f2f2;
        font-family: Arial, sans-serif;
}

h1 {
        color: #00698f;
}
```


# Get a workflow with vscode live-server

- Download vscode extention live-server
- Start working on your html, save, see how it refreshes
- Get used to this workflow of editing files, see the result in the browser



# Installing Git Locally
- Go to [git-scm.com/downloads](http://git-scm.com/downloads) and download the latest version of Git for your operating system
- Follow the installation instructions for your operating system (Windows, macOS, or Linux)
- Verify that Git is installed by running `git --version` in the terminal/command prompt


# Setting Up Your Local Git Repository
- Navigate to your project folder in the terminal/command prompt
- Run `git init` to initialize a new local Git repository
- Create a new file called `.gitignore` to specify files that should be ignored by Git
- Add `node_modules/` and other unnecessary files/folders to the `.gitignore` file


# Linking Your Local Repository to GitHub
- Run `git remote add origin https://github.com/yourusername/yourrepositoryname.git` to link local repository to GitHub
- Verify that the origin is set by running `git remote -v`
- Make changes to your project and commit them using `git add .` and `git commit -m "Initial commit"`


# Pushing Changes to GitHub
- Navigate to your project folder in the terminal/command prompt
- Run `git remote add origin https://github.com/yourusername/yourrepositoryname.git` to link local repository to GitHub
- Run `git push -u origin master` to push changes to GitHub


# Cloning a Repository from GitHub
- Run `git clone https://github.com/yourusername/yourrepositoryname.git` to clone the repository to your local machine
- Navigate into the cloned repository folder
- Verify that all files are present by running `ls` or `dir`



# Styling with CSS
- Create a new file called `styles.css` in your project folder
- Link the stylesheet to your HTML document using `<link rel="stylesheet" href="styles.css">`
- Use selectors (e.g. `h1`, `.header`, `#logo`) to target specific elements and apply styles
- Use classes (e.g. `.header`) to style multiple elements with the same properties
- Use IDs (e.g. `#logo`) to style a single unique element with special properties
- Add CSS rules (e.g. `background-color: #f2f2f2;`, `font-size: 24px;`) to style individual components


# Understanding Selectors
- Use element selectors (e.g. `h1`, `p`, `img`) to target specific HTML elements
- Use class selectors (e.g. `.header`, `.footer`) to target multiple elements with the same class
- Use ID selectors (e.g. `#logo`, `#nav`) to target a single unique element with an ID
- Use combinator selectors (e.g. `.header > h1`, `.nav ul li`) to target specific relationships between elements


# Working with Classes and IDs
- Classes can be used multiple times in an HTML document, while IDs are unique
- Use classes for styling multiple elements that share the same properties (e.g. `button`, `link`)
- Use IDs for styling a single element with special properties (e.g. `header-logo`, `footer-text`)


# CSS Properties and Values
- Use CSS properties (e.g. `background-color`, `font-size`) to style individual components
- Use values (e.g. `#f2f2f2`, `24px`) to specify the desired effect of a property
- Understand how different units work (e.g. `px`, `%`, `em`)


# Styling Text and Fonts
- Use CSS properties (e.g. `font-size`, `color`, `text-align`) to style text elements
- Choose from various font families (e.g. serif, sans-serif) and weights (e.g. normal, bold)
- Experiment with different text decorations (e.g. underline, strikethrough)


# Working with Colors and Backgrounds
- Use hex codes (e.g. `#f2f2f2`) or RGB values to specify colors
- Understand how to use transparency (e.g. `rgba`, `opacity`)
- Experiment with different background properties (e.g. `background-image`, `background-repeat`)


# Adding Interactivity with Pseudo-classes and States
- Use pseudo-classes (e.g. `:hover`, `:active`) to add interactivity to elements
- Understand how to use states (e.g. `:checked`, `:focus`) to style form elements
- Experiment with different effects using transitions and animations


# Preview about frameworks
- Bootstrap
- Tailwind



# Introduction to JavaScript
- JavaScript is a client-side scripting language used for adding interactivity to web pages
- It can be used for creating dynamic effects, responding to user interactions, and updating content on the fly
- Understand how to include JavaScript files in your HTML document using the `<script>` tag


# Exercise
- Include a script on your page
- `<script src="myscript.js"></script>`
- Position that script before the ending body tag `</body>`


# Basic Data Types and Variables
- Learn about basic data types (e.g. `number`, `string`, `boolean`)
- Difference between browser and server javascript
- Experiment with basic arithmetic operations (e.g. addition, subtraction) and string concatenation


# Interacting with the DOM
- Learn about the Document Object Model (DOM), which represents the structure of your web page as a tree-like data structure
- Understand how to select elements using methods like `document.getElementById()` and `document.querySelectorAll()`
- Experiment with different ways of manipulating element properties and attributes (e.g. `innerHTML`, `style`, `className`)


# Exercise
- Create a button with an `id` attribute inside the HTML
- Select that element wiht javascript `document.getElementById('MYBUTTONID')`
- Add an event listener to the button element `ele.addEventListener()`
- Finish the listener to simply run a `alert("This is my popup")`


# Conditional Statements and Loops
- Use conditional statements (e.g. `if/else`, `switch`) to make decisions in your code
- Learn about different types of loops (e.g. `for`, `while`, `do...while`)
- Understand how to use loop counters and conditions to control the flow of your program


# Functions and Modules
- Learn about functions, which are reusable blocks of code that can take arguments and return values
- Understand how to create modules, which are self-contained pieces of code that can be easily imported and reused
- Think about user interaction => code execution => DOM interaction flow


# Working with Arrays and Objects
- Learn about arrays, which are ordered collections of values
- Understand how to work with objects, which are unordered collections of key-value pairs
- Experiment with different array methods (e.g. `push`, `pop`, `forEach`) and object properties (e.g. `key in obj`)


# Final Exercise: 
## On-the-fly text to binary converter

- Create a input element from that we read
- use this function in your code
    ```
    function binaryFunc(str) {

        var newBin = str.split(" ");
        var binCode = [];

        for (i = 0; i < newBin.length; i++) {
            binCode.push(String.fromCharCode(parseInt(newBin[i], 2)));
        }
        return binCode.join("");
    }
    ```
- Test the function `binaryFunc('01000001 01110010 01100101 01101110 00100111 01110100'); `
- add eventlistener to the input element, and run the function on `keyup` event
- Write the result into the DOM
