# Structure Webpages with HTML

## HTML & CSS: Design and build websites by Jon Duckett

### Chapter 18: Process and Design
It is a good idea to plan out your process and design. Before we begin to code and design a website we need to figure out who are audience is. Who are we building the website for. We need to determine why people would be visiting the websites and what there motivation and goal is for doing so. You need to know the information they are needing and also how often they might visit. It is a good idea to create a diagram of the pages that will be used to structure your site. This is known as a **site map** and will show how pages can be grouped.To help you decide what information should go on each page, you can use a technique called **card sorting**. Another techinque is to use wireframing. A **wireframe** is a simple sketch of the key information that needs to go on each page of a site. It shows the hierarchy of the information and how much space it might require. This will help make it easier for the visitor to navigate and find what they are looking for. By using the design theory techniques, it will help make the presentation, navigation, and look more appealing to the customer. Using visual hierachy techniques can also help the navigation of your site easier as well.

### Chapter 1: Structure
Structure is very important when designing websites. It is important in helping readers understand the messages you're trying to convey and to navigate around the document. By using HTML elements you can create containers for your content and setup the structure of a website. There are many HTML elements you can learn. HTML uses these elements to describe the structure of your webpage. Tags act like containers. They tell you something about the information that lies between their opening and closing tags. Attributes provide additional information about the contents of an element. They appear on the opening tag of the element and are made up of two parts: a name and a value, separated by an equals sign.

### Chapter 17: HTML5 Layout
HTML5 is introducing a new set of elements that help define the structure of a page. HTML5 makes it easier to structure your page by using elements such as header, footer, section, article, aside, nav, main, etc. Before this web developers had to used deeply nested sets of div elements to help structure. These new elements work the same as a div element, but give better understanding to the content you nest inside of them. These new elements provide clearer code. Older browsers that do understand HTML5 need to which elements are block-level elements. For older Internet Explorer versions, in order to be able to have HTML5 work extra JavaScript may be needed.

### Chapter 8: Extra Markup
- **`!DOCTYPE`**  Each web page should begin with a DOCTYPE declaration to tell the browser which version of HTML the page is using.
- **`<!--Comment Goes Here-->`** Is a way to leave comments in your code. The content in here will not show up on the page.
- **id attribute `(id="")`** Used to uniquely identify an element from other elements on the page. Can also be used for stylization in CSS.
- **class attribute `(class="")`** An attribute that can be applied to mulitple elements. Can also be stylized with CSS.

**Block elements** Some elements will always appear to start on a new line in the browser window. These are known as block elements.Examples of block elements are `<h1>`, `<p>`, `<ul>`, and `<li>`.

**Inline elements** Some elements will always appear to continue on the same line as their neighbouring elements. These are known as inline elements. Examples of inline elements are `<a>`, `<b>`, `<em>`, and `<img>`.

The `<div>` element allows you to group a set of elements together in one block-level box. In a browser, the contents of the `<div>` element will start on a new line, but other than this it will make no difference to the presentation of the page. You can style `<div>` using CSS.

The `<span>` element acts like an inline equivalent of the `<div>` element. It is used to either:
-  Contain a section of text where there is no other suitable element to differentiate it from its surrounding text
- Contain a number of inline elements

`<span>` can also be stylized with CSS.

**`<iframe>`** An iframe is like a little window that has been cut into your page — and in that window you can see another page. The term iframe is an abbreviation of inline frame. An iframe is created using the `<iframe>` element. There are a few attributes that you will need to know to use it:
- src (The src attribute specifies the URL of the page to show in the frame.)
- height (The height attribute specifies the height of the iframe in pixels)
- width (The width attribute specifies the width of the iframe in pixels.)

**seamless** In HTML5, a new attribute called seamless can be applied to an iframe where scrollbars are not desired.

**`<meta>`** The `<meta>` element lives inside the `<head>` element and contains information about that web page.

Escape characters are characters that we may want to include on our webages. They need special code to render correctly on the webpage. Such as `< and >`. The special code for these are `&lt;` and `&gt;`. You can put a  &copy; copyright symbol by using `&copy;`. &cent; can be displayed by using `&cent;`. &trade; to display a trademark you simply use `&trade;`. Those are just a few examples, there are more.

