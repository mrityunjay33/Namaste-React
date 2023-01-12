Q. What is Emmet?
Emmet is a plugin for text editors that allows for fast HTML and CSS development.
 It uses abbreviations that expand into valid HTML and CSS code. For example, typing "div" 
 and then pressing the Emmet shortcut will expand to "<div></div>". This can save a lot of time 
 and typing for developers.



Q. Difference between a Library and Framework?
A library is a collection of pre-written code that can be used to perform common tasks, such as 
connecting to a database or handling HTTP requests. Libraries are typically called from the code 
written by the developer and are designed to be flexible and reusable.

A framework, on the other hand, is a pre-built structure for organizing the code, which provides a 
set of predefined classes and functions that the developer must use in order to create an application. 
Frameworks enforce a specific structure and flow on the code, which can make development faster but 
also less flexible.

In summary, a library is a collection of functions that you can call, while a framework is a structure 
to build your application upon.


Q. What is CDN? Why do we use it?
A Content Delivery Network (CDN) is a distributed network of servers that can be used to deliver 
content to users. The goal of a CDN is to reduce latency and improve the performance of a website 
or application by serving content from a server that is geographically closer to the user.

CDNs are often used to deliver static assets such as images, JavaScript, and CSS files, as well as 
other types of content like video and audio. By caching and delivering content from a nearby server,
 CDNs can help to reduce the time it takes for a page to load, which can improve the user experience.

Using CDN also helps to offload the traffic from the origin server, reducing the load on the origin 
server, which can help to improve the scalability and reliability of the website or application.

In summary, CDN is used to improve the performance and reliability of a website or application by 
serving content from a geographically close server, reducing latency and offloading traffic from origin
 server.


 Q. Why is React known as React?
React is known as React because it was created to address the problem of building large, complex user
 interfaces that can update efficiently in response to changing data. React allows developers to build
  reusable components that can update independently of one another, which makes it easy to build large,
   dynamic web applications. The name "React" is short for "responsive" and reflects the library's
    ability to efficiently update the user interface in response to changes in data.

React is developed and maintained by Facebook and released as an open-source library. It's known as a
 JavaScript library for building user interfaces and it uses a virtual DOM (Document Object Model) to
  efficiently update the view.

In summary, React is known as React because it was created to efficiently build complex, dynamic user
 interfaces that respond to changes in data, and the name "React" is short for "responsive" which 
 reflects the library's ability to efficiently update the user interface in response to changes in data.


Q. What is crossorigin in script tag?
The crossorigin attribute in a <script> tag is used to indicate that the script should be loaded using 
CORS (Cross-Origin Resource Sharing). This allows a web page to load a script from a different origin 
(domain) than the one that served the web page. This can be useful in situations where a script is 
hosted on a different domain than the web page, but the script is intended to be used by that page. 
The attribute can have the value "anonymous" or "use-credentials", depending on whether the script 
should be loaded without credentials or with credentials, respectively.


Q. What is diference between React and ReactDOM
React and ReactDOM are both libraries created by Facebook and are used in developing web applications
 using React.

React is a JavaScript library for building user interfaces. It allows developers to build web
 applications using a component-based architecture, where the UI is broken down into small, reusable 
 components. React provides a way to efficiently update the UI based on changes to the data and the 
 state of the application.

ReactDOM, on the other hand, is the specific React library that provides the bindings between React
 and the Document Object Model (DOM). It allows React components to be rendered in the browser, and 
 provides methods for interacting with the DOM.

In short, React is the core library for building web applications using React, while ReactDOM is the
 library that provides the necessary bindings to interact with the DOM.


Q. What is difference between react.development.js and react.production.js files via CDN?
react.development.js and react.production.js are two different versions of the React library that are
 available for use via a CDN (Content Delivery Network). The main difference between the two is in 
 their intended use and the level of optimizations that have been applied to them.

react.development.js is intended for use during the development phase of a project. It includes helpful
 features such as additional warnings and error messages that can aid in debugging, as well as a 
 detailed call stack in case of an error. This version is typically larger in size and has a slower 
 performance than the production version.

react.production.js, on the other hand, is intended for use in a production environment. It has been
 optimized for performance, with features such as minification and dead code elimination applied to it. 
 This version is typically smaller in size and has a faster performance than the development version.

In general, it is recommended to use the react.production.js version when deploying a React application
 to a production environment, and the react.development.js version during development.



Q. What is async and defer?
async and defer are attributes that can be added to the <script> tag in HTML, which are used to specify
 the loading behavior of the script.

async attribute tells the browser to load the script asynchronously, which means that the script will
 be loaded in parallel with the rest of the page. The script will execute as soon as it has finished 
 loading, regardless of the order in which the script tags appear in the HTML document. This means that 
 other elements on the page can continue to be parsed and rendered while the script is loading.

defer attribute tells the browser to load the script after the page has finished parsing. The script will 
execute only after the entire page has been loaded, and they will execute in the order they appear in the 
HTML document.

Both async and defer allow the browser to continue rendering the page while the script is being loaded.
 However, async can lead to unpredictable behavior of scripts if there are dependencies between them, 
 whereas defer ensures that scripts are executed in the order they are loaded, which can make it easier 
 to manage dependencies.





In HTML, it is generally recommended to place <link> tags with a rel attribute of "stylesheet" in the <head>
 section of the document, while <script> tags are placed at the bottom of the <body> section of the document.

The reason for this is that when a browser loads an HTML document, it starts parsing the document from the top,
 and when it encounters a <link> tag with a rel attribute of "stylesheet", it immediately starts downloading 
 the linked CSS file. By placing the <link> tags in the <head> section of the document, the browser can start 
 downloading the CSS files as soon as possible, which can improve the perceived performance of the page.

When the browser encounters a <script> tag, it stops parsing the HTML and starts downloading and executing the
 script. This can cause a delay in the rendering of the page, especially if the script is large and takes a 
 long time to download and execute. By placing the <script> tags at the bottom of the <body> section of the 
 document, the browser can finish parsing and rendering the rest of the page before it starts downloading and 
 executing the scripts. This can help improve the perceived performance of the page, as the user can start 
 interacting with the page as soon as possible.




Regenerate respon