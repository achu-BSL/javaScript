<h5>1. What is the use of window object? </h5>

<p>The window object in JavaScript represents the global window, which is the top-level browsing context in a web browser. It is part of the browser's JavaScript API and provides access to various properties, methods, and events related to the browser window and the document loaded within it. Here are some common uses of the window object:

1. Accessing global variables and functions: When you define a variable or function in the global scope (outside of any functions or blocks), they become properties and methods of the window object. This allows you to access them anywhere in your JavaScript code using the window object. For example, if you define a global variable varName, you can access it as window.varName.

2. Manipulating the browser window: The window object provides methods to manipulate the browser window, such as window.open() to open a new browser window or tab, window.close() to close the current window, and window.resizeTo() to resize the window.

3. Accessing the document object: The window object also provides access to the document object, which represents the web page loaded in the window. You can access and manipulate the HTML elements, modify the content, handle events, and more using the document object.

4. Working with timers: The window object provides methods to schedule and control the execution of code at specified intervals. For example, you can use window.setTimeout() to execute a function after a specified delay, or window.setInterval() to repeatedly execute a function at a specified interval.

5. Handling events: The window object allows you to register event handlers for various events that occur within the browser window, such as window.onload to run a function when the web page finishes loading, or window.addEventListener() to attach event handlers for user interactions or other events.

6. Managing browser history: The window object provides methods to navigate the browser history, such as window.history.back() to go back to the previous page, or window.history.pushState() to add a new entry to the browser history.

These are just a few examples of the capabilities provided by the window object. It plays a central role in client-side web development, allowing you to interact with the browser, manipulate the DOM, control the flow of code execution, and handle various browser events.</p>
