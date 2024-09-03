# Introduction web development

by Thomas Kuhnert

Speaker Notes:

- Start with joke 
  - Ideas: 
    - BuzzwordBoomin
    - Let chatgpt create a joke
    - Better GH-Copilot


# Today's agenda

- Agenda <!-- .element: class="fragment" data-fragment-index="2" -->
- General overview <!-- .element: class="fragment" data-fragment-index="3" -->
- Tools <!-- .element: class="fragment" data-fragment-index="4" -->
- HTML / HTTP <!-- .element: class="fragment" data-fragment-index="5" -->
- Programming History <!-- .element: class="fragment" data-fragment-index="6" -->
- Funny things (happens for sure before the end) <!-- .element: class="fragment" data-fragment-index="7" -->


# Agenda 

No worries - this is a flexible timeframe

- 09:30 - 11:00 (16:30 - 18:00 JST)
- 11:15 - 12:45 (18:15 - 19:45 JST)
- 13:45 - 15:00 (20:45 - 22:15 JST)
- 15:15 - 16:30 (22:30 - 23:30 JST)


# General overview

### Who are you?


# Who is this guy? 

<div class="d-flex">

- Webdev since 2010 <!-- .element: class="fragment" data-fragment-index="2" -->
- Begann as "script-kiddy" (did I ever stop?) <!-- .element: class="fragment" data-fragment-index="3" -->
- Got official with Wordpress as DigitalMediaDesigner <!-- .element: class="fragment" data-fragment-index="4" -->
- Continued with RubyOnRails <!-- .element: class="fragment" data-fragment-index="5" -->
- 2015 started to freelance <!-- .element: class="fragment" data-fragment-index="6" -->
- Then NodeJS <!-- .element: class="fragment" data-fragment-index="7" -->
- Coaching since 2016 <!-- .element: class="fragment" data-fragment-index="8" -->
- Since 2019 location independent <!-- .element: class="fragment" data-fragment-index="9" -->
- Now python and AI
- Talking to fast <!-- .element: class="fragment" data-fragment-index="10" -->
- Get in touch <!-- .element: class="fragment" data-fragment-index="11" -->
  - https://github.com/spielhoelle 
  - https://tmy.io 
  - https://hachyderm.io/@spielhoelle

<img src="./data/1.jpg" alt="image" width="500">
</div>


# Initial Tech Stuff

- Zoom basics: <!-- .element: class="fragment" data-fragment-index="2" -->
  - understand how to navigate and use essential features like raise hand <!-- .element: class="fragment" data-fragment-index="3" -->
  - mute/unmute <!-- .element: class="fragment" data-fragment-index="4" -->
  - and breakout rooms <!-- .element: class="fragment" data-fragment-index="5" -->
- Quick tips for a smooth start:  <!-- .element: class="fragment" data-fragment-index="6" -->
  - minimize background noise <!-- .element: class="fragment" data-fragment-index="7" -->
  - keep your mic and camera ready <!-- .element: class="fragment" data-fragment-index="8" -->
  - and be prepared to ask questions <!-- .element: class="fragment" data-fragment-index="9" -->
- I cannot look at ZoomChat/Slack etc. Please just speak <!-- .element: class="fragment" data-fragment-index="10" -->

Speaker Notes:

- Test audio/video
- Raise hand


# Internet Stability

- What is internet stability? <!-- .element: class="fragment" data-fragment-index="2" -->
- Importance of fast and stable internet <!-- .element: class="fragment" data-fragment-index="3" -->
- <span>https://fast.com speed</span> <!-- .element: class="fragment" data-fragment-index="4" -->
- <p>Ping or http://ping-test.net reliability</p>  <!-- .element: class="fragment" data-fragment-index="5" -->

Speaker Notes:

- Emphasize importance for onlipythonne development
- Mention how it affects coding experience



# Ecosystem


# What do you think developers are doing?

Speaker Notes:

- Coding all day
- Making fancy animations
- Creating artificial intelligence
- Building robots
- Solving puzzles
- Learning new languages
- Debugging issues
- Meeting with other teams


# What they are actually doing

<div class="d-flex">

- Day-to-day programming experiences <!-- .element: class="fragment" data-fragment-index="2" -->
- Fixed vs freelance vs remote work environments <!-- .element: class="fragment" data-fragment-index="3" -->
- Research and problem-solving strategies <!-- .element: class="fragment" data-fragment-index="4" -->
- Understanding abstract concepts over syntax details <!-- .element: class="fragment" data-fragment-index="5" -->
- Debugging and finding small issues in large systems <!-- .element: class="fragment" data-fragment-index="6" -->
- Unpredictable motivation (it often works at the end) <!-- .element: class="fragment" data-fragment-index="7" -->
- Wide range of industries and applications (e-commerce, biology, etc.) <!-- .element: class="fragment" data-fragment-index="8" -->
- Future-proofing and scalability <!-- .element: class="fragment" data-fragment-index="9" -->
- Digital nomadism: working from anywhere <!-- .element: class="fragment" data-fragment-index="10" -->

<img src="./data/meme.jpg" alt="image" > <!-- .element: class="fragment" data-fragment-index="2" -->
</div>

Speaker Notes:

- Highlight the variety of programming experiences
- Emphasize the importance of problem-solving
- Puzzle, needle/haystack, readings


# The day of a developer

<div class="d-flex">

<img src="./data/2.jpg" alt="image" width="100%" height="auto" style="float: right;"><!-- .element: class="fragment" data-fragment-index="9" -->

- Arrive at "office" <!-- .element: class="fragment" data-fragment-index="2" -->
- Daily-stand <!-- .element: class="fragment" data-fragment-index="3" -->
- Pull code from the repository <!-- .element: class="fragment" data-fragment-index="4" -->
- Check project management tool <!-- .element: class="fragment" data-fragment-index="5" -->
- Write code  <!-- .element: class="fragment" data-fragment-index="6" -->
  - stackoverflow - try - error - stackoverflow - repeat <!-- .element: class="fragment" data-fragment-index="7" -->
- Commit and push changes <!-- .element: class="fragment" data-fragment-index="8" -->
- Go to step 1 <!-- .element: class="fragment" data-fragment-index="9" -->

</div>


# The "internet"

- <span>[History of webdesign](https://www.smamarketing.net/blog/the-history-of-website-design)</span> <!-- .element: class="fragment" data-fragment-index="2" -->
- <span>[State of JS](https://2019.stateofjs.com/demographics/#gender)</span> <!-- .element: class="fragment" data-fragment-index="3" -->


# Exercise:

- <span>Inspect the `DevTools`:</span>  <!-- .element: class="fragment" data-fragment-index="2" -->
  - Elements HTML, Styles and Javascript console <!-- .element: class="fragment" data-fragment-index="3" -->
  - <span>Checkout first website from [Cern](http://info.cern.ch/hypertext/WWW/TheProject.html)</span> <!-- .element: class="fragment" data-fragment-index="4" -->

<img src="./data/devtools.png" alt="image" height="30%" style="float: right;">


# Sub-gernes

<div class="d-flex">

- Frontend <!-- .element: class="fragment" data-fragment-index="2" -->
- Backend <!-- .element: class="fragment" data-fragment-index="3" -->
- Fullstack <!-- .element: class="fragment" data-fragment-index="4" -->
- Related: <!-- .element: class="fragment" data-fragment-index="5" -->
  - Datascience
  - Online marketing
  - Graphic design

<img src="./data/3.jpg" alt="image" width="50%" height="auto" style="float: right;">
</div>


# Habitat

<div class="d-flex">

- IT spans over all indunstries <!-- .element: class="fragment" data-fragment-index="2" -->
- Depending on branch more or less <!-- .element: class="fragment" data-fragment-index="3" -->
- Old fashioned banks or airlines <!-- .element: class="fragment" data-fragment-index="4" -->
- Hipster startups <!-- .element: class="fragment" data-fragment-index="5" -->

<img src="./data/4.jpg" alt="image" width="100%" height="auto" style="float: right;">
</div>



# Mobile first

Browser usage
What is a framework - bootstrap is one!
Mobile statistics
Analytics google


# Exercise:

Check pages on mobile/tablet, see where the breakpoints are. See layout shifts and check which elements are not visible anymore.
Do it for yourself


# Exercise:

Check glassdoor and browse companies search for software developer



# Languages

<div class="d-flex">

- Top 7 Programming languages <!-- .element: class="fragment" data-fragment-index="2" -->
- What programming languages will reign in 2017 <!-- .element: class="fragment" data-fragment-index="3" -->
- Be careful: Java is for javascript like the car for the carpet <!-- .element: class="fragment" data-fragment-index="4" -->
- https://haveibeenpwned.com/ <!-- .element: class="fragment" data-fragment-index="5" -->

<img src="./data/5.jpg" alt="image" width="100%" height="auto" style="float: right;">
</div>


# Markdown

- Easy to write <!-- .element: class="fragment" data-fragment-index="2" -->
- Easy to read <!-- .element: class="fragment" data-fragment-index="3" -->
- Easy to convert <!-- .element: class="fragment" data-fragment-index="4" -->
- Used in many places <!-- .element: class="fragment" data-fragment-index="5" -->

Speaker Notes:

- Importance of Markdown in web development
- How to use Markdown for writing and formatting text


# Wordpress

- Easy solution <!-- .element: class="fragment" data-fragment-index="2" -->
- Battletested <!-- .element: class="fragment" data-fragment-index="3" -->
- Plugin ecosystem <!-- .element: class="fragment" data-fragment-index="4" -->
- Big community <!-- .element: class="fragment" data-fragment-index="5" -->


# CSS

- Make things beautiful  <!-- .element: class="fragment" data-fragment-index="2" -->
- Pendant to HTML structure <!-- .element: class="fragment" data-fragment-index="3" -->
- Mostly static except preprocessors <!-- .element: class="fragment" data-fragment-index="4" -->
- No structre <!-- .element: class="fragment" data-fragment-index="5" -->


# Javascript

- Makes the web interactive <!-- .element: class="fragment" data-fragment-index="2" -->
- Possible to used in FE and BE <!-- .element: class="fragment" data-fragment-index="3" -->
- Difference to html & css is logic <!-- .element: class="fragment" data-fragment-index="4" -->
- Allround tool <!-- .element: class="fragment" data-fragment-index="5" -->


# Exercise: 
- Use the browser console to calculate some numbers. <!-- .element: class="fragment" data-fragment-index="2" -->
- Use alert, confirm("Really?") and combine it with timeout <!-- .element: class="fragment" data-fragment-index="3" -->
- Take some time and browse the D3.jsexamples. <!-- .element: class="fragment" data-fragment-index="5" -->


# HTML elements structure

- HyperText Markup Language <!-- .element: class="fragment" data-fragment-index="2" -->
- Tags that can be nested <!-- .element: class="fragment" data-fragment-index="3" -->
- NO PROGRAMMING LANGUAGE <!-- .element: class="fragment" data-fragment-index="4" -->
- Defines the structure, mostly not the style <!-- .element: class="fragment" data-fragment-index="5" -->
- Not interactive <!-- .element: class="fragment" data-fragment-index="6" -->
- Base scaffold for web pages <!-- .element: class="fragment" data-fragment-index="7" -->

<img src="./data/8.jpg" alt="image" width="100%" height="auto" style="float: right;">

Speaker Notes:
- HTML vs HTTP
- Basic tags (headings, paragraphs, etc.)
- Importance of semantics in HTML
- Limitations of HTML (no programming)


# Combine HTML, CSS and maybe Javascript

- Create a HTML file and put html head body and h1 elements in <!-- .element: class="fragment" data-fragment-index="2" -->
- Create a CSS file and give the body a background-color <!-- .element: class="fragment" data-fragment-index="3" -->
- Create a javascript file and console.log something <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes: 

<html><head></head><body><h1>Example</h1></body></html>


# Python

- Simple syntax <!-- .element: class="fragment" data-fragment-index="2" -->
- Used heavy in machine learning <!-- .element: class="fragment" data-fragment-index="3" -->
- Not so fast <!-- .element: class="fragment" data-fragment-index="4" -->
- Easy learning curve <!-- .element: class="fragment" data-fragment-index="5" -->
- Compared to JS no frontend native language <!-- .element: class="fragment" data-fragment-index="6" -->


# Local LLM's

- Ollama <!-- .element: class="fragment" data-fragment-index="2" -->
- Offline helpers <!-- .element: class="fragment" data-fragment-index="3" -->
- Extensible  <!-- .element: class="fragment" data-fragment-index="4" -->



# Tools


# Hammer? or what?

- Browser inspector <!-- .element: class="fragment" data-fragment-index="2" -->
- Code-editor <!-- .element: class="fragment" data-fragment-index="3" -->
- Project management <!-- .element: class="fragment" data-fragment-index="4" -->
- Terminal <!-- .element: class="fragment" data-fragment-index="5" -->
- Git <!-- .element: class="fragment" data-fragment-index="6" -->

Speaker Notes:
- Intro about the toolbelt


# Browser-inspector

- Let you inspect what got finally rendered <!-- .element: class="fragment" data-fragment-index="2" -->
- Good to debug web applications <!-- .element: class="fragment" data-fragment-index="3" -->
- Available in all browsers <!-- .element: class="fragment" data-fragment-index="4" -->
- DOM (Document Object Model) representation of the page <!-- .element: class="fragment" data-fragment-index="5" -->
- Can help identify layout and styling issues <!-- .element: class="fragment" data-fragment-index="6" -->

Speaker Notes:
- Show a simple example of inspecting an element
- Mention how it can be used to troubleshoot common issues like selectors, js issues, missing imports


# Exercise:

Open the inspector in your browser and check some html-elements on pages you frequently visit


# IDE

- Integrated Development Environment <!-- .element: class="fragment" data-fragment-index="2" -->
- Like a text editor - just better <!-- .element: class="fragment" data-fragment-index="3" -->
- Keeps you from repeating and work organized <!-- .element: class="fragment" data-fragment-index="4" -->
- Code completion and auto-suggest <!-- .element: class="fragment" data-fragment-index="5" -->
- Project management and version control integration <!-- .element: class="fragment" data-fragment-index="6" -->
- Debugging tools and error detection <!-- .element: class="fragment" data-fragment-index="7" -->

Speaker Notes:
- Emphasize the benefits of using an IDE over a text editor


# Examples:

- Notepad++ <!-- .element: class="fragment" data-fragment-index="2" -->
- Sublime text <!-- .element: class="fragment" data-fragment-index="3" -->
- VsCode <!-- .element: class="fragment" data-fragment-index="4" -->


# Exercise: 
Download VsCode and create a html file


# Project management tools

<div class="d-flex">

- Advanced todo lists <!-- .element: class="fragment" data-fragment-index="2" -->
- Make work in team possible <!-- .element: class="fragment" data-fragment-index="3" -->
- Track tickets, milestones and general progress <!-- .element: class="fragment" data-fragment-index="4" -->
- Project managements tools <!-- .element: class="fragment" data-fragment-index="5" -->
  - Trello, Jira, Asana 
- Project managements strategies <!-- .element: class="fragment" data-fragment-index="9" -->
  - Agile, Scrum, Scrum, Waterfall

<img src="./data/pm.png" alt="image" height="auto"> <!-- .element: class="fragment" data-fragment-index="2" -->
  </div>


# Terminal/Shell/Bash/CMD

<div class="d-flex">

- Scriptable good for automatisation <!-- .element: class="fragment" data-fragment-index="2" -->
- Execute commands on computer/server <!-- .element: class="fragment" data-fragment-index="3" -->
- Can emulate on a remote machine <!-- .element: class="fragment" data-fragment-index="4" -->
- More precise than clicky boxy Console is terminal of the browser <!-- .element: class="fragment" data-fragment-index="5" -->

<img src="./data/6.jpg" alt="image" height="auto"> <!-- .element: class="fragment" data-fragment-index="2" -->
</div>


# Exercise:

- Open a terminal app for mac <!-- .element: class="fragment" data-fragment-index="2" -->
- Cmd.exe for windows users <!-- .element: class="fragment" data-fragment-index="3" -->
- Navigate to your desktop  <!-- .element: class="fragment" data-fragment-index="4" -->
  - MAC: cd ~/Desktop, MS: cd c:\\Users\username\Desktop
- List all the files there <!-- .element: class="fragment" data-fragment-index="5" -->
  - MAC: ls, MS: dir 


# Git

- Version control to track changes in your work <!-- .element: class="fragment" data-fragment-index="2" -->
- Allows for multiple developers to work on a project simultaneously and collaboratively <!-- .element: class="fragment" data-fragment-index="3" -->
  - No more worrying about losing changes or having different versions of the same file <!-- .element: class="fragment" data-fragment-index="4" -->
- Prevents version conflicts, just like Google Docs does not allow simultaneous edits on the same document <!-- .element: class="fragment" data-fragment-index="5" -->

Speaker Notes:
- Importance of Git for collaborative development
- How to use Git for tracking changes and resolving conflicts
- Use repos for everything

<img src="./data/6.jpg" alt="image" height="auto"> <!-- .element: class="fragment" data-fragment-index="2" -->


# Exercise:

- <span>Practice coding concepts online e.g. https://learngitbranching.js.org</span> <!-- .element: class="fragment" data-fragment-index="2" -->
- Create a GitHub account to collaborate and track progress <!-- .element: class="fragment" data-fragment-index="3" -->
- Connect with me as your guide and mentor <!-- .element: class="fragment" data-fragment-index="4" -->
- Learn from the best: explore Linus Torvalds' (Linux creator) GitHub page for inspiration <!-- .element: class="fragment" data-fragment-index="5" -->
- Fork, branch, and commit your way to web development mastery! <!-- .element: class="fragment" data-fragment-index="6" -->

Speaker Notes:
- Emphasize the importance of hands-on practice
- Highlight how collaboration and mentorship can accelerate learning


# Excerise

Combining the Tools

- Install a dev environment <!-- .element: class="fragment" data-fragment-index="2" -->
  - Open HTML-file in browser <!-- .element: class="fragment" data-fragment-index="3" -->
  - Right-click -> Inspect or F12 to open DevTools <!-- .element: class="fragment" data-fragment-index="4" -->
  - Open IDE <!-- .element: class="fragment" data-fragment-index="5" -->
  - Install live-server extension <!-- .element: class="fragment" data-fragment-index="6" -->
- Get used to the workflow <!-- .element: class="fragment" data-fragment-index="7" -->
  - Change -> Save -> Refresh browser <!-- .element: class="fragment" data-fragment-index="8" -->
- Create some basic HTML elements <!-- .element: class="fragment" data-fragment-index="9" -->
  - img tag for images <!-- .element: class="fragment" data-fragment-index="10" -->
  - a tag for links <!-- .element: class="fragment" data-fragment-index="11" -->
  - button tag for buttons <!-- .element: class="fragment" data-fragment-index="12" -->
  - hr tag for horizontal rules <!-- .element: class="fragment" data-fragment-index="13" -->

Speaker Notes:
- Importance of a dev environment
- How to set up and use DevTools
- Benefits of using an IDE like VsCode


# HTTP


# HTTP... what?

- HyperText Transfer Protocol <!-- .element: class="fragment" data-fragment-index="2" -->
  - Standard protocol for transferring data (like HTML) over the internet <!-- .element: class="fragment" data-fragment-index="3" -->
- Network analysis <!-- .element: class="fragment" data-fragment-index="4" -->
  - HTTP requests and responses <!-- .element: class="fragment" data-fragment-index="5" -->
  - Status codes (200, 404, etc.) <!-- .element: class="fragment" data-fragment-index="6" -->
  - Headers and bodies <!-- .element: class="fragment" data-fragment-index="7" -->

<img src="./data/11.jpg" alt="image" > <!-- .element: class="fragment" data-fragment-index="2" -->

Speaker Notes:
- Key differences between HTTP/HTML
- Importance of HTTP in web development
- How HTML is transported over the internet using HTTP


# GameDev
- Improvise
- https://youtu.be/xyPzTywUBsQ?t=1573


# Exercise:

- Go back to the inspector and inspect network traffic from youtube <!-- .element: class="fragment" data-fragment-index="2" -->
- See statuscodes, content-type and timings in action <!-- .element: class="fragment" data-fragment-index="3" -->


# Difference between HTTP and HTTPS

<div class="d-flex">
<div>

- Named protocol - others are ftp/tcp/wss <!-- .element: class="fragment" data-fragment-index="2" -->
- Letsencrypt certification - open source, free TLS/SSL certificates <!-- .element: class="fragment" data-fragment-index="3" -->
- Google rates non HTTPS sites down in search ranking <!-- .element: class="fragment" data-fragment-index="4" -->
- Additional security measures: <!-- .element: class="fragment" data-fragment-index="5" -->
  - Use a VPN (e.g. NordVPN) <!-- .element: class="fragment" data-fragment-index="6" -->
  - Extended TorBrowser <!-- .element: class="fragment" data-fragment-index="7" -->

## Examples: <!-- .element: class="fragment" data-fragment-index="8" -->
* Bad example: HTTP site with sensitive info <!-- .element: class="fragment" data-fragment-index="9" -->
* Good example: HTTPS site with secure connection <!-- .element: class="fragment" data-fragment-index="10" -->
</div>

<img src="./data/10.jpg" alt="image" width="100%" height="auto" style="float: right;"> <!-- .element: class="fragment" data-fragment-index="2" -->
</div>

Speaker Notes:
- Importance of HTTPS for security and search ranking
- How to obtain a free Letsencrypt certificate
- Additional steps for enhanced security


# DNS

- Telephone book of the web <!-- .element: class="fragment" data-fragment-index="2" -->
  - Maps human-readable domain names to IP addresses <!-- .element: class="fragment" data-fragment-index="3" -->
- Enables communication between devices on a network <!-- .element: class="fragment" data-fragment-index="4" -->
- Crucial for navigating the internet, as it translates URLs into IP addresses <!-- .element: class="fragment" data-fragment-index="5" -->

<img src="./data/13.jpg" alt="image" width="100%" height="auto" style="float: right;"> <!-- .element: class="fragment" data-fragment-index="2" -->

Speaker Notes:
- How DNS works
- Importance of DNS in web development


# Binary

<div class="d-flex">

- Web is built on 0 and 1 <!-- .element: class="fragment" data-fragment-index="2" -->
  - The foundation of computer programming and data storage <!-- .element: class="fragment" data-fragment-index="3" -->
- A 2-number based counting system is called binary <!-- .element: class="fragment" data-fragment-index="4" -->
  - Adequate for machines to understand and process information <!-- .element: class="fragment" data-fragment-index="5" -->
- ASCII characters have decimal and binary representations <!-- .element: class="fragment" data-fragment-index="6" -->
  - Letters are encoded as numbers, allowing computers to process text <!-- .element: class="fragment" data-fragment-index="7" -->

<img src="./data/14.jpg" alt="image" width="100%" height="auto" style="float: right;"> <!-- .element: class="fragment" data-fragment-index="2" -->
</div>

Speaker Notes:
- Importance of binary in computer programming
- How ASCII encoding works


# Hexadecimal

### A Shorter Representation of Numbers

- Computers use hexadecimal (hex) to represent numbers in a shorter form <!-- .element: class="fragment" data-fragment-index="2" -->
  - Base 16 system, using letters and digits from 0-9 and A-F <!-- .element: class="fragment" data-fragment-index="3" -->
- Hexadecimal is used for: <!-- .element: class="fragment" data-fragment-index="4" -->
  - Computer programming and coding <!-- .element: class="fragment" data-fragment-index="5" -->
  - Data representation and storage <!-- .element: class="fragment" data-fragment-index="6" -->
  - Color codes and design <!-- .element: class="fragment" data-fragment-index="7" -->

Examples: <!-- .element: class="fragment" data-fragment-index="8" -->
- 1 = 1 <!-- .element: class="fragment" data-fragment-index="9" -->
- 8 = 8 <!-- .element: class="fragment" data-fragment-index="10" -->
- 10 = a <!-- .element: class="fragment" data-fragment-index="11" -->
- 16 = f <!-- .element: class="fragment" data-fragment-index="12" -->
- 256 = ff <!-- .element: class="fragment" data-fragment-index="13" -->

Speaker Notes:
- Importance of hexadecimal in computer programming
- How hexadecimal works


# Exercise:
- Refer to the ascii table and convert your name into binary
- Refer to the ascii table and convert your name into hexadecimal


# Problems

### Challenges in Computing and Networking

- Unix Time:
  - Representation of time using seconds since January 1, 1970, 00:00:00 GMT <!-- .element: class="fragment" data-fragment-index="2" -->
  - Limited to 32-bit signed integer values, causing issues on or after January 19, 2038, at 03:14:07 UTC <!-- .element: class="fragment" data-fragment-index="3" -->
- Millennium Bug:
  - Fear of widespread computer failures due to the year 2000 not being represented correctly in some systems <!-- .element: class="fragment" data-fragment-index="4" -->
  - Mostly a non-issue, as many systems had already been upgraded or modified by then <!-- .element: class="fragment" data-fragment-index="5" -->
- End of 32-bit epoch/Year 2038 problem:
  - Similar to the Unix time issue, but with more severe consequences if not addressed <!-- .element: class="fragment" data-fragment-index="6" -->
- IPv4/IPv6:
  - Transition from IPv4 (32-bit addresses) to IPv6 (128-bit addresses) required careful planning and implementation <!-- .element: class="fragment" data-fragment-index="7" -->
- Increases the possible DNS (phone book) entries:
  - Larger address space in IPv6 allows for a much larger number of unique IP addresses, reducing the need for NATs and improving internet scalability <!-- .element: class="fragment" data-fragment-index="8" -->

Speaker Notes:
- Overview of common problems in computing and networking
- Importance of addressing these issues to ensure system stability and security

 




# Accessiblity

- html attributes <!-- .element: class="fragment" data-fragment-index="2" -->
- dev-tools tools <!-- .element: class="fragment" data-fragment-index="3" -->
- keyboard accessibility <!-- .element: class="fragment" data-fragment-index="4" -->


# Performance

- Browser vs. embedded vs. cloud <!-- .element: class="fragment" data-fragment-index="2" -->
- Images <!-- .element: class="fragment" data-fragment-index="3" -->
- minification <!-- .element: class="fragment" data-fragment-index="4" -->
- CDN <!-- .element: class="fragment" data-fragment-index="5" -->
- Caching <!-- .element: class="fragment" data-fragment-index="6" -->
- HTTP caching <!-- .element: class="fragment" data-fragment-index="7" -->
- Redis <!-- .element: class="fragment" data-fragment-index="8" -->


# Using AI

- Bad knowledge base, prefer generative aspects <!-- .element: class="fragment" data-fragment-index="2" -->
- Custom instructions <!-- .element: class="fragment" data-fragment-index="3" -->
- Prompt engineering <!-- .element: class="fragment" data-fragment-index="4" -->
- hyperparams <!-- .element: class="fragment" data-fragment-index="5" -->


# Making AI

- Data data data <!-- .element: class="fragment" data-fragment-index="2" -->
- Different kinds of AI <!-- .element: class="fragment" data-fragment-index="3" -->
- Foundation training, fine-tune, RAG <!-- .element: class="fragment" data-fragment-index="4" -->
- ML ops <!-- .element: class="fragment" data-fragment-index="5" -->


# Engineering

- Databases
- DevOps
- Security
- Terminal
- Compilers


# Power user
- Hotkeys
- Zapier
- Alfred or similar
- Don't over-engineer it
- Gamification
- Pomodoro
- Task lists, calender, sync of those
- Calendly 



# Funny things

Some great links
Hackertyper
ThisPersonDoesntExist
React95
Funny things


# Recursion

Exercise:
Google Recursion
Funny things
