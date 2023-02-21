## Code 201 - Foundations of Software Development

1. Compose a short poem describing how HTTP sends data between computers.

   > So imagine you got peoples right! and a package of informantion that you got needs to keep tight. To access this information we have to use Big Browser Mane to go to DNS server who be spitting game. When we request what we are looking for, Browser Mane looks to DNS to find the website's IP adress before it can retrieve the website. Browser Mane then sends an Hyepertext Transfer Protocol. Do yall know him at all? HTTP is an applicant that defines a language for clients and servers to speak to each other. So Browser sends request to the server asking a make a copy of the website to the client. Now if server dude approves the request from HTTP no s, the server will send a "200 OK" message, which means of course you can access the infomation to was looking for on this computer.

2. Describe how HTML, CSS, and JS files are “parsed” in the browser.

   > First the browser parses the HTML file and it recognizes any link element that references external CSS stylesheets and any script element references to scripts. after the browser sends request back to server for any CSS files and Java script files from link elements and script elements and from those, then parses the CSS and JavaScript.

   **Some definitions** </br>

- **Parsed** is the step the browser takes to turn the data it receives over the network into DOM and CSSOM, which is used by the renderer to paint a page to the screen. </br>
  - **DOM** - Document Object Model (DOM) connects web pages to scripts or programming languages by representing the structure of a document—such as the HTML representing a web page—in memory. </br>
  - **CSSOM** - is a set of APIs for reading and modifying a document's style-related (CSS) information. In other words, similar to the way in which the DOM enables a document's structure and content to be read and modified from JavaScript, the CSSOM allows the document's styling to be read and modified from JavaScript.

3. How can you find images to add to a Website?

   > You can find images online

4. How do you create a String vs a Number in JavaScript?

   > String is a sequence of text. To signify that the value is a string, use single or double quote marks. let myVariable = 'Max'; or let myVariable = "Max";
   >
   > > Numbers don't have quotation around the value so it looks like : let myVariable = 10;

5. What is a Variable and why are they important in JavaScript?
   > Variables are containers that store values. You start by declaring a variable with the "let" keyword, followed by the name you give to the variable. With this we can easily interact with specific varibles we have created.

### Introduction to HTML

1. What is an HTML attribute?

   > Attributes is extra information about the element that won't appear in the content. class="edit-reading"👈🏽 Attributes

2. Describe the Anatomy of an HTMl element.

   > First you have the < opening > and </ closing> tags then you have content in between the opening and closing tags which could be text and the entire thing will be an element.  
   > ![Example:](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started/grumpy-cat-small.png) </br>

3. What is the Difference between < article > and <section > element tags?

   > The difference is that section element defines sections of the page and article is used for wrapping similar content.

4. What Elements does a “typical” website include?

   > A typical website have a header element, navigation bar, main content, sidebar, and a footer.

5. How does metadata influence Search Engine Optimization?

   > It tells search engine how to read and display sites on search engine.

6. How is the <meta> HTML tag used when specifying metadata?
   > Okay so the < meta> tag defines metadata about the HTML doucment. Metadata is info. about data and meta tags will go inside the head element.

#### How to start to design a Website.

1. What is the first step to designing a Website?

   > When getting an idea draw it out first.

2. What is the most important question to answer when designing a Website?
   > What exactly do I want to accomplish? How will a website help me reach my goals? What needs to be done, and in what order, to reach my goals?

semantics

1. Why should you use an <h1> element over a <span> element to display a top level heading?

   > It is good to use h1 element over span element because no semantic value will be added using span, so it will not get any extra benefits.

2. What are the benefits of using semantic tags in our HTML?

   > Semantic naming mirrors proper custom element/component naming and Search engines will consider its contents as important keywords to influence the page's search rankings

   1.Describe 2 things that require JavaScript in the Browser?

   > adding interactive behavior to the webpage and running code in execution environments.

   2.How can you add JavaScript to an HTML document?

   > You can use the value for the src attribute and it should be the path to your JavaScript file.

object- can be anything. Everything in JavaScript is an object and can be stored in a variable. Keep this in mind as you learn. let myVariable = document.querySelector('h1');
