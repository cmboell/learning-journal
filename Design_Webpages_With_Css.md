# Design Webpages With CSS
**CSS(Cascading Style Sheets)** is a programming language used to add style and design to the elements of a webpage. By using selectors that identify with the HTML you want to apply style to using '{ }' (curly brackets) and putting the stylization ques in between them you are able to style elements. A colon goes between the value and property, while a semi-colon goes at the end of each property. You may put multiple styling effects between the curly brackets.
## HTML & CSS: Design and build websites by Jon Duckett
### Chapter 10: Introducing CSS
HTML flows within invisible boxes, whether they be block or inline elements. CSS allows you to create rules that control the way that each individual box (and the contents of that box) is presented. We used CSS to control the stylization of each box. Example of a CSS style:

'h1{
    font-size: 10px;
    color: #000000;
}'

CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration. In the above example h1 would be the selector and font-size would be a declaration.

CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon. You can specify several properties in one declaration, each separated by a semi-colon. In the above example color would be a property and #000000 would be the value.
[Back To Home](/README.md)

#### Different Types of CSS
You can use CSS in three different ways: Externally, Internally, and Embedded
- Externally: You need to create a new file (example name style.css) and nest the link inside the head portion of your HTML file. You then write your CSS within your CSS file to be rendered to the HTML files it is connected to.
- Internally: You can nest your style tags within the head of your HTML file. Your styles that you write will be rendered within the HTML file.
- Embedded: You can add style directly to an HTML tag by using the style attribute.

#### CSS Selectors
- Universal Selectors: Target all elements on the page.
- Type Selectors: Matches element names.
- Class Selectors: Matches an element whose class attribute has a value that matches the one specified after the period (or full stop) symbol.
- ID Selectors: Matches an element whose id attribute has a value that matches the one specified after the pound or hash symbol.
- Child Selectors: Matches an element that is a direct child of another.
- Descendant Selector: Matches an element that is a descendent of another specified element (not just a direct child of that element).
- Adjacent Selector: Matches an element that is the next sibling of another.
- General Sibling Selector: Matches an element that is a sibling of another, although it does not have to be the directly preceding element.

#### Cascading 
The word cascading refers to the order in which competing style rules are applied. If two style rules have the same property and are created using the same selector, the last one in the code will be applied.

### Chapter 11: Color
There are multiple ways you can add and specify color using CSS:
   Way          Example
- Color name :  Black
- Hexadecimal : #123456
- RGB values :  rgb(255, 0, 0)
- RGBA values:  rgba(0,0,0,0.5)
- HSL values :  hsl(0, 100%, 50%)
- HSLA values:   hsla(0,100%,100%,0.5)
- CMYK values : cmyk(0, 1, 0.5, 0)

You can use colors to change text, background, and borders. Using a color picker can help you find the color you are looking for. There are 100 predefined color names. Using RGB or Hexadecimal values can broaden your color range (16 million color combonations.) By using HSL value you can control the hue, saturation, and lighness of the colors. When choosing colors for your webpage it is important to understand the flow of your color scheme. Your webpage should be readable. Using light background with dark text is a good practice. A good color scheme for your webpage should make it easy to read and accessable for everyone who visits. 






