## JavaScript Basics

### 1) Compose a short poem describing how HTTP sends data between computers.
&nbsp; H: Happily delivering information from a server <br>
&nbsp; T: To the browser <br>
&nbsp; T: Through Hyper-text <br>
&nbsp; P: Protocol <br>
HTTP is more or less the language through which a browser and server deliver or share information. 


### 2) Describe how HTML, CSS, and JS files are “parsed” in the browser.
&nbsp; When browsers send a request to the server for information, the browser will first parse the HTML file. As the browser reads the HTML file, it will notice the links within the HTML to the other files, such as CSS and JS. Those files will be parsed next. 

### 3) How can you find images to add to a Website?
&nbsp; There are several free sites online that have pictures to choose from for public use. There are also sites that charge a fee for more premium images. Google images is an easy place to start, just make sure the image is for public use. 

### 4) How do you create a String vs a Number in JavaScript?
&nbsp; There are several different ways to give value to a variable. One way is called a string variable. A string is a sequence of text, within a set of quotes. For example: "Bob" or 'three'. These are both string type variables. <br>
Another variable type is a number. This will be read as a numerical value and does not require quotes. For example: "three" and 3, the text is a string and the digit is simply the number three. 

### 5) What is a Variable and why are they important in JavaScript?
&nbsp; Variables are containers that store values. You start by declaring a variable with the let keyword, followed by the name you give to the variable. You can give a variable any name you like, it will be case sensitive. After declaring a variable, you can give it value. You can then retrieve that value by calling the variable name. 


## HTML Basics

### 1) What is an HTML attribute?
&nbsp; An attribute contains extra or additional information about the element. An attribute does not show up in the content, but can add a style element to the content. 

### 2) Describe the Anatomy of an HTMl element.
&nbsp; An HTML element has an opening tag, the content in the middle, and a closing tag at the end. For example, the element for a heading is < h1 >. So for the heading we would do this, except with no spaces inside the <> <br>
&nbsp; < h1 >This is my heading!< /h1 >

### 3) What is the Difference between < article > and < section > element tags? 
&nbsp; The < article > HTML element represents a self-contained composition in a document, page, application, or site, which is intended to be independently distributable or reusable (e.g., in syndication). Examples include: a forum post, a magazine or newspaper article, or a blog entry, a product card, a user-submitted comment, an interactive widget or gadget, or any other independent item of content. <br>
&nbsp; The < section > HTML element represents a generic standalone section of a document, which doesn't have a more specific semantic element to represent it. Sections should always have a heading, with very few exceptions.

### 4) What Elements does a “typical” website include?
&nbsp; Typial websites will include several elements: Header, Main content, Navigation bar, a side bar and a footer. Each elemenet has its own placement and use on the site. 

### 5) How does metadata influence Search Engine Optimization?
&nbsp; Meta data is additional data about the HTML, such as the author, and important keywords that describe the document. Meta tags and metadata are important elements for SEO because they provide information about a webpage to search engines and web browsers. They can help search engines understand the content and context of a page and can improve the appearance of the page in the search results

### 6) How is the <meta> HTML tag used when specifying metadata?
&nbsp; Metadata is information about data. < meta > tags always go inside the < head > element, and are typically used to specify character set, page description, keywords, author of the document, and viewport settings. The < meta > tag does not require an end tag. 

## Misc Notes

### 1) How to start to design a Website.

#### What is the first step to designing a Website?
&nbsp; The first step to designing a website is to create a visual layout of what it will look like. This will help to create a rough idea of the coding that will be needed to accomplish the desired look. 

#### What is the most important question to answer when designing a Website?
&nbsp; When creating a website, it is important to know the purpose of your site and the intended audience. Having those things locked down will make it easier to design the site to contain all the necessary information and any attributes that may be needed. For example, if the purpose of the site is for a business, you may want to add a section to collect the users info. For other sites, that may not be important. It all depends on what you are trying to accomplish with the site. 

### 2) Semantics

#### Why should you use an < h1 > element over a < span > element to display a top level heading?
&nbsp; the < h1 > element is a block element, it has a set styling of being the largest heading in the section. The < span > element differs in that it is an inline element, and cannot stand alone like a block element. The < span > element could be used wthin the heading if needed, but not the other way around.

#### What are the benefits of using semantic tags in our HTML?
&nbsp; Using semantics allows for more accessibility and readability of your site on the web, especially with SEO. It can also create a better flowing experience for the user. 

### 3) What is JavaScript?

#### Describe 2 things that require JavaScript in the Browser?
&nbsp; JavaScript is required on a site for any interactive features and maneuverability for the user. If JaavaScript is disabled, links within the site will not work. Any pop ups that are added with JS will not initiate. 

#### How can you add JavaScript to an HTML document?
&nbsp; You can link a JS page to your HTML document by adding the JS link into your HTML doc. It can be added anywhere, but typically it will go near the top section near Title. 
