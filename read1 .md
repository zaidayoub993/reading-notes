## Introductory HTML and JavaScript
Web pages are created with three main parts:
* Hypertext Markup Language (HTML)
* Cascading Style Sheets (CSS)
* JavaScript (JS)
# HTML
Hypertext Markup Language (HTML) is the standard markup language for documents designed to be displayed in a web browser. It can be assisted by technologies such as Cascading Style Sheets (CSS) and scripting languages such as JavaScript.

Web browsers receive HTML documents from a web server or from local storage and render the documents into multimedia web pages. HTML describes the structure of a web page semantically and originally included cues for the appearance of the document.

HTML elements are the building blocks of HTML pages. With HTML constructs, images and other objects such as interactive forms may be embedded into the rendered page. HTML provides a means to create structured documents by denoting structural semantics for text such as headings, paragraphs, lists, links, quotes and other items. HTML elements are delineated by tags, written using angle brackets. Tags such as <img /> and <input /> directly introduce content into the page. Other tags such as <p> surround and provide information about document text and may include other tags as sub-elements. Browsers do not display the HTML tags, but use them to interpret the content of the page.

HTML can embed programs written in a scripting language such as JavaScript, which affects the behavior and content of web pages. Inclusion of CSS defines the look and layout of content. The World Wide Web Consortium (W3C), former maintainer of the HTML and current maintainer of the CSS standards, has encouraged the use of CSS over explicit presentational HTML since 1997.[2]
# css 
What is CSS? And How Does It Relate to HMTL?
CSS stands for Cascading Style Sheets with an emphasis placed on “Style.” While HTML is used to structure a web document (defining things like headlines and paragraphs, and allowing you to embed images, video, and other media), CSS comes through and specifies your document’s style—page layouts, colors, and fonts are all determined with CSS. Think of HTML as the foundation (every house has one), and CSS as the aesthetic choices (there’s a big difference between a Victorian mansion and a mid-century modern home).

How Does CSS Work?
CSS brings style to your web pages by interacting with HTML elements. Elements are the individual HTML components of a web page—for instance a paragraph—which in HTML might look like this:

<p>This is my paragraph!</p>
If you wanted to make this paragraph appear pink and bold to people viewing your web page through a web browser, you’d use CSS code that looks like this:

p  {  color:pink;  font-weight:bold;  }
In this case, “p” (the paragraph) is called the “selector”—it’s the part of CSS code specifying which HTML element the CSS styling will effect. In CSS, the selector is written to the left of the first curly bracket. The information between curly brackets is called a declaration, and it contains properties and values that are applied to the selector. Properties are things like font size, color, and margins, while values are the settings for those properties. In the example above, “color” and “font-weight” are both properties, and “pink” and “bold” are values. The full bracketed set of

{  color:pink;  font-weight:bold;  } 
is the declaration, and again, “p” (meaning the HTML paragraph) is the selector. These same basic principles can be applied to change font sizes, background colors, margin indentations, and more. For instance. . .

body  {  background-color:lightblue;  }
. . .would make your page’s background light blue, or. . .

p  {  font-size:20px;  color:red;  }
. . .will create a 20 point font paragraph with red letters. 
# java script
JavaScript (or "JS") is a programming language used most often for dynamic client-side scripts on webpages, but it is also often used on the server-side, using a runtime such as Node.js.

JavaScript should not be confused with the Java programming language. Although "Java" and "JavaScript" are trademarks (or registered trademarks) of Oracle in the U.S. and other countries, the two programming languages are significantly different in their syntax, semantics, and use cases.

JavaScript is primarily used in the browser, enabling developers to manipulate webpage content through the DOM, manipulate data with AJAX and IndexedDB, draw graphics with canvas, interact with the device running the browser through various APIs, and more. JavaScript is one of the world's most commonly-used languages, owing to the recent growth and performance improvement of APIs available in browsers.
What is JavaScript ?
JavaScript is a dynamic computer programming language. It is lightweight and most commonly used as a part of web pages, whose implementations allow client-side script to interact with the user and make dynamic pages. It is an interpreted programming language with object-oriented capabilities.

JavaScript was first known as LiveScript, but Netscape changed its name to JavaScript, possibly because of the excitement being generated by Java. JavaScript made its first appearance in Netscape 2.0 in 1995 with the name LiveScript. The general-purpose core of the language has been embedded in Netscape, Internet Explorer, and other web browsers.

The ECMA-262 Specification defined a standard version of the core JavaScript language.

JavaScript is a lightweight, interpreted programming language.
Designed for creating network-centric applications.
Complementary to and integrated with Java.
Complementary to and integrated with HTML.
Open and cross-platform
Client-Side JavaScript
Client-side JavaScript is the most common form of the language. The script should be included in or referenced by an HTML document for the code to be interpreted by the browser.

It means that a web page need not be a static HTML, but can include programs that interact with the user, control the browser, and dynamically create HTML content.

The JavaScript client-side mechanism provides many advantages over traditional CGI server-side scripts. For example, you might use JavaScript to check if the user has entered a valid e-mail address in a form field.

The JavaScript code is executed when the user submits the form, and only if all the entries are valid, they would be submitted to the Web Server.

JavaScript can be used to trap user-initiated events such as button clicks, link navigation, and other actions that the user initiates explicitly or implicitly.

Advantages of JavaScript
The merits of using JavaScript are −

Less server interaction − You can validate user input before sending the page off to the server. This saves server traffic, which means less load on your server.

Immediate feedback to the visitors − They don't have to wait for a page reload to see if they have forgotten to enter something.

Increased interactivity − You can create interfaces that react when the user hovers over them with a mouse or activates them via the keyboard.

Richer interfaces − You can use JavaScript to include such items as drag-and-drop components and sliders to give a Rich Interface to your site visitors.

Limitations of JavaScript
We cannot treat JavaScript as a full-fledged programming language. It lacks the following important features −

Client-side JavaScript does not allow the reading or writing of files. This has been kept for security reason.

JavaScript cannot be used for networking applications because there is no such support available.

JavaScript doesn't have any multi-threading or multiprocessor capabilities.

Once again, JavaScript is a lightweight, interpreted programming language that allows you to build interactivity into otherwise static HTML pages.