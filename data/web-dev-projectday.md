# WebDev Projectday 
## (optional)


# Timetable

- Class 9:00 - 10:30 (17.00 - 18.30 JST)
- Break 10:30 - 10:40 (18.30 - 18.40 JST)
- Class 10:40 - 11:50 (18.40 - 20.10 JST)
- Break 11:50 - 12:00 (20.10 - 20.20 JST)
- Class 12:00 - 13:05 (20.20 - 21.05 JST)
- `Lunch break`
- Class 14:05 - 15:35 (self paced learning)
- Break 15:35 - 15:45
- Class 15:45 - 17:15 (self paced learning)
- Break 17:15 - 17:25
- Class 17:25 - 18:10 (self paced learning) (00.25 - 01.10 JST)


# Web Development Project Day

* Welcome to our web development project day! <!-- .element: class="fragment" data-fragment-index="2" -->
* Today we'll be building a basic portfolio page from scratch. <!-- .element: class="fragment" data-fragment-index="3" -->
* Let's get started! <!-- .element: class="fragment" data-fragment-index="4" -->


# What we gonna learn today

- The workflow of web-devs <!-- .element: class="fragment" data-fragment-index="2" -->
- The proceess of web-projects <!-- .element: class="fragment" data-fragment-index="3" -->
- How to figure things out (problemsolver) <!-- .element: class="fragment" data-fragment-index="4" -->


# Create a GitHub Account

- <span>Go to http://github.com and sign up for an account</span> <!-- .element: class="fragment" data-fragment-index="2" -->
- Fill out the registration form with your details <!-- .element: class="fragment" data-fragment-index="3" -->
- Verify your email address to activate your account <!-- .element: class="fragment" data-fragment-index="4" -->
- <span>Create a new repository named: `username.github.io` for our project</span> <!-- .element: class="fragment" data-fragment-index="5" -->


# Before we start coding...
- Make a rough wireframe <!-- .element: class="fragment" data-fragment-index="2" -->
- Think about what you wanna tell <!-- .element: class="fragment" data-fragment-index="3" -->
- Think about the perspective of a HR person <!-- .element: class="fragment" data-fragment-index="4" -->


# Create a New HTML File

- Download vscode <!-- .element: class="fragment" data-fragment-index="2" -->
- Download the index.html from before <!-- .element: class="fragment" data-fragment-index="3" -->
- <span>Put it into a seperated project folder. I recommend `~/dev/username.github.io`</span> <!-- .element: class="fragment" data-fragment-index="4" -->
- Open that folder with VsCode <!-- .element: class="fragment" data-fragment-index="5" -->
- Add the basic HTML structure: <!-- .element: class="fragment" data-fragment-index="6" -->
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


# Tired of ctrl+s ctrl+r?

- Download vscode extention live-server <!-- .element: class="fragment" data-fragment-index="2" -->
- Start working on your html, save, see how it refreshes <!-- .element: class="fragment" data-fragment-index="3" -->
- Get used to this workflow of editing files, see the result in the browser <!-- .element: class="fragment" data-fragment-index="4" -->


# Installing Git Locally
- Signup with github from within VsCode <!-- .element: class="fragment" data-fragment-index="2" -->
- <span>Go to [git-scm.com/downloads](http://git-scm.com/downloads) and download the latest version of Git for your operating system </span><!-- .element: class="fragment" data-fragment-index="3" -->
- Follow the installation instructions for your operating system (Windows, macOS, or Linux) <!-- .element: class="fragment" data-fragment-index="4" -->
- <span>Verify that Git is installed by running `git --version` in the terminal/command prompt</span> <!-- .element: class="fragment" data-fragment-index="5" -->


# Setting Up Your Local Git Repository
- Navigate to your project folder in the terminal/command prompt <!-- .element: class="fragment" data-fragment-index="2" -->
- <span>Run `git init` to initialize a new local Git repository </span><!-- .element: class="fragment" data-fragment-index="3" -->
- <span>Create a new file called `.gitignore` to specify files that should be ignored by Git</span> <!-- .element: class="fragment" data-fragment-index="4" -->
- <span>Add `node_modules/` and other unnecessary files/folders to the `.gitignore` file</span> <!-- .element: class="fragment" data-fragment-index="5" -->


# Linking Your Local Repository to GitHub
- <span>Run `git remote add origin https://github.com/yourusername/yourrepositoryname.git` to link local repository to GitHub</span> <!-- .element: class="fragment" data-fragment-index="2" -->
- <span>Verify that the origin is set by running `git remote -v`</span> <!-- .element: class="fragment" data-fragment-index="3" -->
- <span>Make changes to your project and commit them using `git add .` and `git commit -m "Initial commit"`</span> <!-- .element: class="fragment" data-fragment-index="4" -->


# Pushing Changes to GitHub
- Navigate to your project folder in the terminal/command prompt <!-- .element: class="fragment" data-fragment-index="2" -->
- <span>Run `git remote add origin https://github.com/yourusername/yourrepositoryname.git` to link local repository to GitHub</span>  <!-- .element: class="fragment" data-fragment-index="3" -->
- <span>Run `git push -u origin master` to push changes to GitHub</span>  <!-- .element: class="fragment" data-fragment-index="4" -->


# Cloning a Repository from GitHub
- <span>Run `git clone https://github.com/yourusername/yourrepositoryname.git` to clone the repository to your local machine</span> <!-- .element: class="fragment" data-fragment-index="2" -->
- <span>Navigate into the cloned repository folder</span>  <!-- .element: class="fragment" data-fragment-index="3" -->
- <span>Verify that all files are present by running `ls` or `dir`</span>  <!-- .element: class="fragment" data-fragment-index="4" -->


# Styling with CSS
- <span>Create a new file called `styles.css` in your project folder</span> <!-- .element: class="fragment" data-fragment-index="2" -->
- <span>Link the stylesheet to your HTML document using `<link rel="stylesheet" href="styles.css">`</span>  <!-- .element: class="fragment" data-fragment-index="3" -->
- <span>Use selectors (e.g. `h1`, `.header`, `#logo`) to target specific elements and apply styles</span>  <!-- .element: class="fragment" data-fragment-index="4" -->
- <span>Use classes (e.g. `.header`) to style multiple elements with the same properties</span>  <!-- .element: class="fragment" data-fragment-index="5" -->
- <span>Use IDs (e.g. `#logo`) to style a single unique element with special properties</span>  <!-- .element: class="fragment" data-fragment-index="6" -->
- <span>Add CSS rules (e.g. `background-color: #f2f2f2;`, `font-size: 24px;`) to style individual components</span>  <!-- .element: class="fragment" data-fragment-index="7" -->


# Understanding Selectors
- <span>Use element selectors (e.g. `h1`, `p`, `img`) to target specific HTML elements</span> <!-- .element: class="fragment" data-fragment-index="2" -->
- <span>Use class selectors (e.g. `.header`, `.footer`) to target multiple elements with the same class</span> <!-- .element: class="fragment" data-fragment-index="3" -->
- <span>Use ID selectors (e.g. `#logo`, `#nav`) to target a single unique element with an ID</span> <!-- .element: class="fragment" data-fragment-index="4" -->
- <span>Use combinator selectors (e.g. `.header > h1`, `.nav ul li`) to target specific relationships between elements</span> <!-- .element: class="fragment" data-fragment-index="5" -->


# Working with Classes and IDs
- <span>Classes can be used multiple times in an HTML document, while IDs are unique</span> <!-- .element: class="fragment" data-fragment-index="2" -->
- <span>Use classes for styling multiple elements that share the same properties (e.g. `button`, `link`)</span> <!-- .element: class="fragment" data-fragment-index="3" -->
- <span>Use IDs for styling a single element with special properties (e.g. `header-logo`, `footer-text`)</span> <!-- .element: class="fragment" data-fragment-index="4" -->


# CSS Properties and Values
- <span>Use CSS properties (e.g. `background-color`, `font-size`) to style individual components</span> <!-- .element: class="fragment" data-fragment-index="2" -->
- <span>Use values (e.g. `#f2f2f2`, `24px`) to specify the desired effect of a property</span> <!-- .element: class="fragment" data-fragment-index="3" -->
- <span>Understand how different units work (e.g. `px`, `%`, `em`)</span> <!-- .element: class="fragment" data-fragment-index="4" -->


# Styling Text and Fonts
- <span>Use CSS properties (e.g. `font-size`, `color`, `text-align`) to style text elements</span> <!-- .element: class="fragment" data-fragment-index="2" -->
- <span>Choose from various font families (e.g. serif, sans-serif) and weights (e.g. normal, bold)</span> <!-- .element: class="fragment" data-fragment-index="3" -->
- <span>Experiment with different text decorations (e.g. underline, strikethrough)</span> <!-- .element: class="fragment" data-fragment-index="4" -->


# Working with Colors and Backgrounds
- <span>Use hex codes (e.g. `#f2f2f2`) or RGB values to specify colors</span> <!-- .element: class="fragment" data-fragment-index="2" -->
- <span>Understand how to use transparency (e.g. `rgba`, `opacity`)</span> <!-- .element: class="fragment" data-fragment-index="3" -->
- <span>Experiment with different background properties (e.g. `background-image`, `background-repeat`)</span> <!-- .element: class="fragment" data-fragment-index="4" -->


# Adding Interactivity with Pseudo-classes and States
- <span>Use pseudo-classes (e.g. `:hover`, `:active`) to add interactivity to elements</span> <!-- .element: class="fragment" data-fragment-index="2" -->
- <span>Understand how to use states (e.g. `:checked`, `:focus`) to style form elements</span> <!-- .element: class="fragment" data-fragment-index="3" -->
- <span>Experiment with different effects using transitions and animations</span> <!-- .element: class="fragment" data-fragment-index="4" -->


# Preview about frameworks
- Bootstrap <!-- .element: class="fragment" data-fragment-index="2" -->
- Tailwind <!-- .element: class="fragment" data-fragment-index="3" -->


# Introduction to JavaScript
- JavaScript is a client-side scripting language used for adding interactivity to web pages <!-- .element: class="fragment" data-fragment-index="2" -->
- It can be used for creating dynamic effects, responding to user interactions, and updating content on the fly <!-- .element: class="fragment" data-fragment-index="3" -->
- <span>Understand how to include JavaScript files in your HTML document using the `<script>` tag</span> <!-- .element: class="fragment" data-fragment-index="4" -->


# Exercise
- <span>Include a script on your page</span> <!-- .element: class="fragment" data-fragment-index="2" -->
- <span>`<script src="myscript.js"></script>`</span> <!-- .element: class="fragment" data-fragment-index="3" -->
- <span>Position that script before the ending body tag `</body>`</span> <!-- .element: class="fragment" data-fragment-index="4" -->


# Basic Data Types and Variables
- <span>Learn about basic data types (e.g. `number`, `string`, `boolean`)</span> <!-- .element: class="fragment" data-fragment-index="2" -->
- <span>Difference between browser and server javascript</span> <!-- .element: class="fragment" data-fragment-index="3" -->
- <span>Experiment with basic arithmetic operations (e.g. addition, subtraction) and string concatenation</span> <!-- .element: class="fragment" data-fragment-index="4" -->


# Interacting with the DOM
- <span>Learn about the Document Object Model (DOM), which represents the structure of your web page as a tree-like data structure</span> <!-- .element: class="fragment" data-fragment-index="2" -->
- <span>Understand how to select elements using methods like `document.getElementById()` and `document.querySelectorAll()`</span> <!-- .element: class="fragment" data-fragment-index="3" -->
- <span>Experiment with different ways of manipulating element properties and attributes (e.g. `innerHTML`, `style`, `className`)</span> <!-- .element: class="fragment" data-fragment-index="4" -->


# Exercise
- <span>Create a button with an `id` attribute inside the HTML</span> <!-- .element: class="fragment" data-fragment-index="2" -->
- <span>Select that element wiht javascript `document.getElementById('MYBUTTONID')`</span> <!-- .element: class="fragment" data-fragment-index="3" -->
- <span>Add an event listener to the button element `ele.addEventListener()`</span> <!-- .element: class="fragment" data-fragment-index="4" -->
- <span>Finish the listener to simply run a `alert("This is my popup")`</span> <!-- .element: class="fragment" data-fragment-index="5" -->


# Conditional Statements and Loops
- <span>Use conditional statements (e.g. `if/else`, `switch`) to make decisions in your code</span> <!-- .element: class="fragment" data-fragment-index="2" -->
- <span>Learn about different types of loops (e.g. `for`, `while`, `do...while`)</span> <!-- .element: class="fragment" data-fragment-index="3" -->
- <span>Understand how to use loop counters and conditions to control the flow of your program</span> <!-- .element: class="fragment" data-fragment-index="4" -->


# Functions and Modules
- <span>Learn about functions, which are reusable blocks of code that can take arguments and return values</span> <!-- .element: class="fragment" data-fragment-index="2" -->
- <span>Understand how to create modules, which are self-contained pieces of code that can be easily imported and reused</span> <!-- .element: class="fragment" data-fragment-index="3" -->
- <span>Think about user interaction => code execution => DOM interaction flow</span> <!-- .element: class="fragment" data-fragment-index="4" -->


# Working with Arrays and Objects
- <span>Learn about arrays, which are ordered collections of values</span> <!-- .element: class="fragment" data-fragment-index="2" -->
- <span>Understand how to work with objects, which are unordered collections of key-value pairs</span> <!-- .element: class="fragment" data-fragment-index="3" -->
- <span>Experiment with different array methods (e.g. `push`, `pop`, `forEach`) and object properties (e.g. `key in obj`)</span> <!-- .element: class="fragment" data-fragment-index="4" -->


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
