# Dynamic Webpages With Javascript
## Javascript and Jquery by Jon Duckett
Javascript is a computer programing language that you can write code that instructs the browser how to behave when the user is interacting with the app. JavaScript and jQuery can be used to access and manipulate the DOM, making the user’s experience dynamic and interactive.
### Chapter 1c (pages 43-52)
There are 3 languages used to program web pages: HTML, CSS & Javascript. HTML is the content layer of the web page, CSS visually presents the page and Javascript is the layer that tells the page how to behave when a user interacts with it. All 3 are kept in separate files. These 3 layers working together are a popular approach used when building web pages called *progressive enhancement*.

Javascript files are generally kept in their own js file & have a .js extention at the end of the file name. To use a javascript with a web page, you use the `<script>` element in the HTML file to tell the browser it's reading a script. It's "src" attribute tells where it is stored.

#### Javascript example:

`var today = new Date();`
`var hourNow = today.getHours();`
`var greeting;`

`if (hourNow > 18) {`
`    greeting = 'Good evening!';`
`} else if (hourNow > 12) {`
`    greeting = 'Good afternoon!';`
`} else if (hourNow > 0) {`
`    greeting = 'Good morning!';`
`} else {`
`    greeting = 'Welcome!';`
`}`

`document.write('<h3>' + greeting + '</h3>');`

#### HTML including javascript source:

`<!DOCTYPE html>`
`<html>`
`    <head>`
`        <title>Constructive &amp; Co.</title>`
`        <link rel="stylesheet" href="css/index.css"/>`
`    </head>`
`    <body>`
`        <h1>Constructive &amp; Co.</h1>`
        **`<script src="js/add-content.js"></script>`**
`        <p>For all orders and inquiries please call`
`            <em>555-3344</em></p>`
`    </body>`
`</html>`


Javascript can be added between two script tags, but that could also slow down your page, so that it why is it better to be kept in a separate file that the script tags on your html page just link to.

### Chapter 2 (pages 53-69)
- It is important to note that Javascript is case sensitive. 
- A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a **statement**. Statements should end with a semicolon(;).
- Statements are instructions and each one starts on a new line. 
- Some statements are surrounded by curly braces, these are known as **code blocks**. The closing curly bracket is not followed by a semicolon. 
- To write a comment that stretches over more than one line, you use a **multi-line** comment, starting with `/*` and end with `*/`. Anything inbetween will not be processed by javascript.
- In a **single-line** comment, anything that follows the two forward slash characters // on that line will not be processed.
- A script will temporarily store the bits of information it needs to do its job, it can store data in **variables**. A variable is a good name for this concept because data stored in  a variable can change or vary each time a script is run. 
- When scripts can use variables to find the information it needs when running with different data, the result is said to be calculated or computed using the data stored in the variables.
- var is an example of what programmers call a keyword. In order to use the variable , you must give it a name (in this case the variable is called quantity).
- If a variable name is more than one word, it is usually written in camelCase.
- When you set a value to a variable it is called quantity. The = sign is an assignment operator meaning you are setting a value to the variable. 
- Until you set a value to a variable, it is **undefined**
- JavaScript distinguishes between numbers, strings, and true or false values known as **Booleans**

[Back To Home Page](/README.md)