## 1. Write a blog on the difference between between documents and Window objects

### What is the Document Object?

The document object represents the entire HTML document within a browser window. It serves as an interface to access and manipulate the content, structure, and styles of a web page.

### Key Characteristics of the Document Object:

1. DOM Structure: The document object provides a hierarchical representation of the HTML elements on a webpage, allowing developers to navigate, modify, and manipulate the content dynamically.<br>
2. Methods: The document object offers methods like "getElementById()", "getElementsByClassName()", and "querySelector()", enabling developers to select specific elements based on their IDs, classes, or other attributes.<br>
3. Properties: Properties such as document.title, document.URL, and document.body provide information about the document's title, URL, and body, respectively.<br>
4. Content Manipulation: Through the document object, you can dynamically create, modify, or delete elements, attributes, and text content on a webpage.

5. ### Example:

   ```Javascript
         // Change the title of the document
            document.title = "New Title";
        // Get element by ID and change its content
            document.getElementById("myElement").innerHTML = "Updated Content";
   ```
## What is the Window Object?
The window object represents the browser window or tab containing the DOM document. It acts as a global object, providing methods and properties related to the browser environment, including navigation, location, history, and timing.
### Key Characteristics of the Window Object:
1. Global Scope: The window object serves as the global scope in JavaScript, meaning variables and functions declared without the var, let, or const keyword become properties of the window object.<br>
2. Browser Information: The window object offers properties like window.innerWidth, window.innerHeight, and window.navigator to provide information about the browser's dimensions, navigator object, and other related details.<br>
3. Navigation: Methods such as window.open(), window.close(), and window.location allow developers to control browser navigation, open new windows or tabs, and manipulate the current URL.<br>
4. Timers: The window object provides functions like setTimeout(), setInterval(), and clearTimeout() to manage time-based operations and execute code asynchronously.<br>

### Example:

 ```Javascript
    // Open a new window
       window.open("https://www.example.com");
    // Resize the current window
       window.resizeTo(500, 500);
 ```
### Conclusion

In summary, while the document object focuses on representing and manipulating the content within an HTML document, the window object provides a broader scope, encompassing the browser window's properties, methods, and functionalities. Understanding the distinctions between these two objects is essential for effective web development, as it enables developers to leverage their unique capabilities and functionalities to create dynamic and interactive web applications.        
