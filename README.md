# Interview-questions-

1.	What is HTML and what is its purpose?
   HTML stands for HyperText Markup Language. It is a markup language used to create web pages. The purpose of HTML is to structure content on the web.

2.	What is the difference between HTML and XHTML?
    HTML and XHTML are both markup languages used to create web pages. The main difference between them is that XHTML is stricter than HTML. XHTML requires that 
    all tags be properly nested and closed, while HTML does not.

3.	What are the new features introduced in HTML5?
    HTML5 introduced several new features including semantic elements, audio and video support, canvas element, local storage, and geolocation.


4.	How do you include comments in HTML?
    You can include comments in HTML using the following syntax: <!-- comment goes here -->

5.	Explain the difference between <div> and <span> tags.
    The <div> tag is used to group block-level elements together, while the <span> tag is used to group inline-level elements together.

6.	What are semantic elements in HTML5 and why are they important?
    Semantic elements are HTML5 elements that describe the meaning of their content to both the browser and the developer. They are important because they help 
    improve accessibility, search engine optimization (SEO), and make it easier for developers to understand the structure of a web page.

7.	What is the purpose of the <header>, <nav>, <section>, and <footer> tags in HTML5?
     The <header> tag is used to define a header section for a document or section.
   	 The <nav> tag is used to define a set of navigation links for a document or section.
   	 The <section> tag is used to define a section in a document or section.
   	 The <footer> tag is used to define a footer section for a document or section.

8.	How do you create a hyperlink in HTML?
    You can create a hyperlink in HTML using the following syntax: <a href=“url”>link text</a>

9.	What is the difference between <ol> and <ul> elements?
    The <ol> element is used to create an ordered list, while the <ul> element is used to create an unordered list.

10.	How do you embed an image in HTML?
     Yes, we can embed an image in HTML using the following syntax: <img src=“image.jpg” alt=“description”>

11.	Explain the difference between the <strong> and <em> tags.
    The <strong> tag is used to indicate strong importance, while the <em> tag is used to indicate emphasis.

12.	How do you create a table in HTML?
    You can create a table in HTML using the following syntax:
  	<table> 
      <tr> <th>Header 1</th> 
        <th>Header 2</th> 
      </tr> 
      <tr> <td>Data 1</td>
        <td>Data 2</td>
      </tr>
    </table>

13.	What is the purpose of the <form> tag in HTML and how do you create a form?
    The <form> tag is used to create an HTML form for user input. You can create a form using the following syntax:
   	<form action=“submit.php” method=“post”>
      First name:<br> 
      <input type=“text” name=“firstname”>
      <br> Last name:<br>
        <input type=“text” name=“lastname”><br><br> 
        <input type=“submit” value=“Submit”> 
     </form>

14.	What are some new input types introduced in HTML5?
     HTML5 introduced several new input types including email, url, number, range, date, time, color, and search.

15.	How do you include audio and video content in HTML?
    You can include audio and video content in HTML using the following syntax:
     a.	<audio controls> <source src=“audio.mp3” type=“audio/mpeg”> Your browser does not support the audio element. </audio>
     b.	<video controls> <source src=“video.mp4” type=“video/mp4”> Your browser does not support the video element. </video>

16.	What is the purpose of the <iframe> tag and how is it used?
    The <iframe> tag is used to embed another document within an HTML document. It is often used to embed videos or maps from other websites.

17.	How do you add CSS styles to HTML elements?
    You can add CSS styles to HTML elements using inline styles or external style sheets.

18.	What is the role of the alt attribute in <img> tags?
    The alt attribute is used to provide alternative text for an image if it cannot be displayed. This is important for accessibility and SEO. Here’s an example:
    a.	<img src=“image.jpg” alt=“description of image”>


19.	How do you create a numbered list with custom numbering styles in HTML?
    You can create a numbered list with custom numbering styles using CSS. Here’s an example:
    a.	<ol style=“list-style-type: upper-roman;”>
   	     <li>Item 1</li> <li>Item 2</li> <li>Item 3</li> 
        </ol>

20.	What is the difference between <script async> and <script defer>?
     The <script async> attribute tells the browser to download the script asynchronously while the page continues to load.
   	 The <script defer> attribute tells the browser to download the script after the page has finished loading.

21.	What is responsive web design, and why is it important?
     Responsive web design is an approach to web design that makes web pages render well on a variety of devices and window or screen sizes. It is important 
     because it ensures that users have a good experience on your website regardless of what device they are using.

22.	How do you make a website responsive using CSS?
    You can make a website responsive using CSS by using media queries, flexible grid systems, and flexible images.

23.	What is a media query in CSS, and how is it used for responsive design?
    A media query is a CSS technique that allows you to apply different styles based on the device or screen size. It is used for responsive design by allowing 
   you to create different layouts for different devices.

24.	Explain the difference between a fluid layout and a fixed layout in terms of responsiveness.
     A fluid layout adjusts to the size of the screen or window, while a fixed layout has a set width and does not adjust to the size of the screen or window.

25.	How do you make images responsive in CSS?
    You can make images responsive in CSS by setting their max-width property to 100%.

26.	What are breakpoints in responsive design, and how are they determined?
     Breakpoints are specific screen sizes at which your website’s layout changes. They are determined based on common device sizes and user behaviour.

27.	How can you hide elements on specific screen sizes using CSS?
     You can hide elements on specific screen sizes using media queries and setting their display property to none.

28.	What is the purpose of the max-width property in responsive CSS?
     The max-width property sets the maximum width of an element. This is useful for making sure that elements do not become too large on larger screens.
   	
29.	How do you create a responsive navigation menu using CSS?
    You can create a responsive navigation menu using CSS by using media queries and flexible grid systems.
   	
31.	Explain the concept of mobile-first design and how it relates to responsive CSS.
    Mobile-first design is an approach to web design that prioritizes designing for mobile devices first before designing for larger screens. It relates to 
    responsive CSS because it encourages designers to think about how their designs will look on smaller screens first.

32.	What is CSS Flexbox, and what problem does it solve?
     CSS Flexbox is a layout module that makes it easier to align and distribute space among items in a container even when their size is unknown or dynamic. It 
     solves the problem of creating complex layouts with HTML and CSS.

33.	Explain the difference between flex container and flex items.
     A flex container is an element that contains flex items. Flex items are direct children of a flex container.

34.	How do you create a flex container in CSS?
    You can create a flex container in CSS by setting the display property of an element to flex.

35.	What are the main properties used to control the layout in Flexbox?
    The main properties used to control the layout in Flexbox are justify-content, align-items, align-self, and flex-wrap.

36.	How do you specify the direction of flex items within a flex container?
    You can specify the direction of flex items within a flex container by setting the flex-direction property.

37.	What is the purpose of the flex-grow, flex-shrink, and flex-basis properties?
    The flex-grow property specifies how much an item should grow relative to the rest of the items in the container.
   	The flex-shrink property specifies how much an item should shrink relative to the rest of the items in the container.
   	The flex-basis property specifies the initial size of an item before any remaining space is distributed.
    Example: .item { flex-grow: 1; /* default value / flex-shrink: 1; / default value / flex-basis: auto; / default value */ }

38.	How do you align flex items horizontally and vertically within a flex container?
    You can align flex items horizontally using the justify-content property and vertically using the align-items property.
    Example: .container { display: flex; justify-content: center; /* aligns items horizontally / align-items: center; / aligns items vertically */}

39.	Explain the difference between justify-content and align-items properties in Flexbox.
     The justify-content property aligns items horizontally within a container, while the align-items property aligns items vertically within a container.
     Example: .container { display: flex; justify-content: center; /* aligns items horizontally / align-items: center; / aligns items vertically */ }
   	
40.	How can you control the order of flex items using CSS Flexbox?
     You can control the order of flex items using the order property.
     Example: .item { order: 1; /* default value is 0 */ }
   	
41.	What are flexbox breakpoints, and how can they be used for responsive design?
    Flexbox breakpoints are specific screen sizes at which your website’s layout changes using Flexbox. They can be used for responsive design by allowing you to 
    create different layouts for different devices.
    Example: @media screen and (max-width: 600px) { .container { display: block; } }
   	
42.	What are HTML attributes?
    HTML attributes provide additional information about an element and are defined within a start tag.
    Example: <img src=“image.jpg” alt=“description of image”>
   	
43.	Explain the difference between global attributes and element-specific attributes in HTML.
    Global attributes can be used on any HTML element, while element-specific attributes are only applicable to certain elements.
    Example: <div class=“container” data-id=“123”>…</div>
    
44.	How do you add attributes to an HTML element?
    You can add attributes to an HTML element by including them in the start tag of the element.
    Example: <img src=“image.jpg” alt=“description of image”>
   	
45.	What is the purpose of the id attribute in HTML, and how is it unique?
     The id attribute is used to uniquely identify an HTML element on a page. It must be unique within a page.
     Example: <div id=“header”>…</div>
     
46.	What is the difference between the class attribute and the id attribute?
    The class attribute is used to group elements together based on a common class name, while the id attribute is used to uniquely identify an individual 
    element.
    Example: <div class=“container”>…</div> <div id=“header”>…</div>
    
47.	Explain the role of the href attribute in HTML,particularly in the context of links and anchors.
    The href attribute specifies the URL of the page that you want to link to when creating links and anchors.
    Example: <a href=“https://www.example.com”>Link</a>
    
48.	How do you add alternative text to an image using the alt attribute?
     You can add alternative text to an image using the alt attribute like this:
    Example: <img src=“image.jpg” alt=“description of image”>
   	
49.	What is the purpose of the target attribute in HTML links, and what are its possible values?
    The target attribute specifies where to open a linked document when clicked. Its possible values include _blank (opens link in new window), _self (opens link 
    in same window), _parent (opens link in parent frame), and _top (opens link in full body of window).
    Example: <a href=“https://www.example.com” target=“_blank”>Link</a>
    
50.	How do you use the src attribute to embed an external resource, such as an image or video, in HTML?
    You can use the src attribute like this:
    Example: <img src=“image.jpg”>
    
51.	What is the purpose of the disabled attribute, and how is it used in HTML form elements?
    The disabled attribute is used to disable form elements so that they cannot be edited or submitted by users

52.	Is there any relation between Java and JavaScript?
    Java and JavaScript are two different programming languages with different syntax and semantics.

53.	Is JavaScript a compiled or interpreted language?
     JavaScript is an interpreted language.

54.	Is JavaScript a case-sensitive language?
    Yes, JavaScript is a case-sensitive language.

55.	What is nodejs?
    Node.js is an open-source, cross-platform, back-end JavaScript runtime environment that executes JavaScript code outside of a web browser.

56.	What is the difference between let and var?
    The main difference between let and var is that let has block scope while var has function scope.
      // Example:
      function example() {
      if (true) {
       var x = 1;
        let y = 2;
       }
      console.log(x); // Output: 1
      console.log(y); // ReferenceError: y is not defined
    }

57.	.What are the differences between undeclared and undefined variables?
    Undeclared variable is one that has not been declared using the var, let, or const keyword. An undefined variable is one that has been declared but has not 
    been assigned a value.
    // Example:
    console.log(x); // ReferenceError: x is not defined
    var y;
    console.log(y); // Output: undefined

58.	What is Hoisting?
    Hoisting is a JavaScript mechanism where variables and function declarations are moved to the top of their scope before code execution.
    // Example:
    console.log(x); // Output: undefined
    var x = 1;

59.	What is scope in javascript?
     Scope refers to the visibility of variables in different parts of your code.
    // Example:
    function example() {
      var x = 1;
      if (true) {
        var y = 2;
        console.log(x); // Output: 1
        console.log(y); // Output: 2
      }
      console.log(x); // Output: 1
      console.log(y); // Output: 2
    }

60.	What are reserved words?,Can I use reserved words as identifiers?
       Reserved words are words that have special meaning in JavaScript and cannot be used as identifiers. Examples include var, let, const, if, else, while, 
       for, function, etc.
        // Example:
        var if = "Hello"; // SyntaxError: Unexpected token 'if'

61.	Why do you need strict mode?, How do you declare strict mode?
     Strict mode is used to enforce stricter parsing and error handling rules in JavaScript. You can declare strict mode by adding “use strict”; at the beginning 
     of your code.
    // Example:
    "use strict";
    x = 3.14; // ReferenceError: x is not defined

62.	What are global variables?
     Global variables are variables that are defined outside of any function and can be accessed from anywhere in your code.
    // Example:
    var x = 1;
    function example() {
      console.log(x); // Output: 1
    }
    example();

63.	What are the problems with global variables?
     The main problem with global variables is that they can be accessed and modified from anywhere in your code, which can lead to naming conflicts and other          issues.        

                                                                                                                                 
64.	What is NaN property?
     NaN stands for “Not a Number” and is a value returned when a mathematical operation fails or when a value cannot be converted to a number.
    // Example:
    console.log(parseInt("Hello")); // Output: NaN

65.	What is the purpose of delete operator?
     The delete operator is used to remove a property from an object or to remove an element from an array.
    // Example:
    var obj = {x: 1};
    delete obj.x;
    console.log(obj); // Output: {}

66.	What is the difference between null and undefined?
     Null represents an intentional absence of any object value while undefined represents an uninitialized or unassigned value.
    // Example:
    var x = null;
    var y;
    console.log(x); // Output: null
    console.log(y); // Output: undefined

67.	What are the bitwise operators available in javascript?
     The bitwise operators available in JavaScript include AND (&), OR (|), XOR (^), NOT (~), LEFT SHIFT (<<), RIGHT SHIFT (>>), and ZERO-FILL RIGHT SHIFT (>>>).
    // Example:
    console.log(5 & 9); // Output: 1 (binary representation )

68.	Can I redeclare let and const variables?
     No, you cannot redeclare let or const variables within the same scope.
      // Example:
      let x = 1;
      let x = 2; // SyntaxError: Identifier 'x' has already been declared

69.	Does const variable makes the value immutable?
     No, const only makes the variable reference immutable; it does not make the value immutable.
      // Example:
      const obj = {x: 1};
      obj.x = 2;
      console.log(obj); // Output: {x: 2}

70.	What is ES6?
       List down some of the features of ES6. ES6 (ECMAScript 2015) is a major update to the JavaScript language specification that was released in 2015. Some            of its features include arrow functions, classes, template literals, destructuring assignments, let and const keywords for variable declaration,                   modules for better code organization, etc.
        // Example:
        // Arrow function
        const example = () => {
          console.log("Hello");
        };
        
        // Class
        class Example {
          constructor(x) {
            this.x = x;
          }
        }
        
        // Template literals
        const name = "John";
        console.log(`Hello ${name}`);
        
        // Destructuring assignment
        const obj = {x: 1};
        const {x} = obj;
        console.log(x); // Output: 1
        
        // Let and const keywords for variable declaration
        let y = 2;
        const z = 3;
    
    // Modules for better code organization
    import {example} from "./example.js";

71.	What are the possible ways to create objects in JavaScript?
    There are several ways to create objects in JavaScript:
    •	Object literals
    •	Constructor functions
    •	Classes (ES6)
    •	Object.create() method

72.	What is the difference between slice and splice?
    The slice() method returns a shallow copy of a portion of an array into a new array object selected from start to end (end not included) where start and end       represent the index of items in that array. The original array is not modified.
    The splice() method changes the contents of an array by removing or replacing existing elements and/or adding new elements in place. The original array is         modified.

73.	What is the difference between a. == and === operators? 
a.	The == operator compares values after converting them to a common type while === operator compares both value and type.

b.	 = and == operators?
              The = operator is used for assignment while == operator is used for comparison.
c.	 %= and = operators? 
              The %= operator is used for modulus assignment while = operator is used for assignment.

74.	What is a higher order function?
     A higher order function is a function that takes one or more functions as arguments or returns a function as its result.

75.	What is the currying function?
    Currying is a technique of transforming a function with multiple arguments into a sequence of functions with single arguments. The resulting sequence of 
    functions can be called one after another to achieve the same result as calling the original function with multiple arguments

76.	What are arrow functions?
    Arrow functions are a shorthand syntax for writing function expressions in JavaScript. They have a more concise syntax than traditional function expressions 
   and do not bind their own this value.
    // Example:
    const example = (x, y) => {
     return x + y;};

77.	What is a spread operator?
    The spread operator is a syntax for spreading the elements of an iterable (like an array or string) into places where multiple elements are expected.
      // Example:
      const arr1 = [1, 2, 3];
      const arr2 = [4, 5, 6];
      const arr3 = [...arr1, ...arr2];
      console.log(arr3); // Output: [1, 2, 3, 4, 5, 6]

78.	What is a rest parameter? The rest parameter is a syntax for representing an indefinite number of arguments as an array.
    // Example:
    const example = (...args) => {
      console.log(args);
    };
    example(1, 2, 3); // Output: [1, 2, 3]

79.	What happens if you do not use rest parameter as a last argument?
     If you do not use the rest parameter as the last argument in a function definition, you will get a syntax error.
      // Example:
      const example = (x, ...rest, y) => { // SyntaxError: Rest parameter must be last formal parameter
      };

80.	What are regular expression patterns?
    Regular expression patterns are used to match character combinations in strings.

81.	What is a Regular Expression?
    A regular expression (regex or regexp) is a pattern used to match character combinations in strings.

82.	How do you search a string for patterns?
     You can use the match() method or the test() method of the RegExp object to search a string for patterns.
    // Example:
    const str = "Hello World";
    const pattern = /World/;
    console.log(str.match(pattern)); // Output: ["World"]
    console.log(pattern.test(str)); // Output: true
   	
83.	What is the purpose of switch-case?
     The switch-case statement is used to perform different actions based on different conditions.

84.	What are the conventions to be followed for the usage of switch case?
    Some conventions to follow when using switch-case statements include:
    •	Always include a default case
    •	Use break statements to prevent fall-through
    •	Use meaningful case labels
   	
85.	What are primitive data types?
     Primitive data types are data types that are not objects and do not have methods. They include undefined, null, boolean, number and string.

86.	What are the different ways to access object properties?
    There are two ways to access object properties in JavaScript:
    •	Dot notation (.)
    •	Bracket notation ([]);
   	
87.	What are the function parameter rules?
    Some rules for function parameters in JavaScript include:
    •	Function parameters are optional by default
    •	Function parameters can have default values
    •	Function parameters can be destructured

88.	Different ways which create infinite loops?
    Infinite loops can be created in several ways including:
    •	Forgetting to update the loop counter variable in a for loop
    •	Using while(true) or while(1)
    •	Using recursion without an exit condition

89.	What are template literals?
    Template literals are a syntax for embedding expressions inside string literals in JavaScript.
    // Example:
    const name = "John";
    console.log(`Hello ${name}`);

90.	What are default values in destructuring assignment?
    Default values in destructuring assignment are used to provide a fallback value when the value being destructured is undefined.
      // Example:
      const obj = {x: 1};
      const {x, y = 2} = obj;
      console.log(x); // Output: 1
      console.log(y); // Output: 2

91.	How do you swap variables in destructuring assignment?
    You can swap variables in destructuring assignment by using a temporary variable.
    // Example:
    let x = 1;
    let y = 2;
    [x, y] = [y, x];
    console.log(x); // Output: 2
    console.log(y); // Output: 1

92.	Is that possible to use expressions in switch cases?
    Yes, it is possible to use expressions in switch cases.
    // Example:
    const x = 1;
    switch (true) {
      case x === 1:
        console.log("x is 1");
        break;
      default:
        console.log("x is not 1");
    }

93.	What are the differences between for…of and for…in statements?
    The for…of statement is used to iterate over the values of an iterable object (like an array or string) while the for…in statement is used to iterate over 
    the keys of an object.
    // Example:
    const arr = [1, 2, 3];
    for (const value of arr) {
      console.log(value);
    }
    const obj = {x: 1, y: 2, z: 3};
    for (const key in obj) {
     console.log(key);}
    
94.	What are the differences between arguments object and rest parameter?
    The arguments object is an array-like object that contains all the arguments passed to a function while the rest parameter is a syntax for representing an 
    indefinite number of arguments as an ``.
    // Example:
      function example(x, y) {
        console.log(arguments[0]); // Output: 1
        console.log(arguments[1]); // Output: 2
      }
      example(1, 2);
      
      function example(...args) {
        console.log(args); // Output: [1, 2]
      }
      example(1, 2);

95.	What are the differences between spread operator and rest parameter?
    The spread operator is used to spread the elements of an iterable (like an array or string) into places where multiple elements are expected while the rest 
    parameter is used to represent an indefinite number of arguments as an array.
      // Example:
      function example(x, y) {
        console.log(x + y); // Output: 3
      }
      const arr = [1, 2];
      example(...arr);
      
      function example(...args) {
        console.log(args); // Output: [1, 2]
      }
      example(1, 2);


96.	Explain all the array methods, what are the outputs and whether the method modifies the original Array?
    Here’s a list of some common array methods in JavaScript:
    •	push(): Adds one or more elements to the end of an array and returns the new length of the array. Modifies original array.
    •	pop(): Removes the last element from an array and returns that element. Modifies original array.
    •	shift(): Removes the first element from an array and returns that element. Modifies original array.
    •	unshift(): Adds one or more elements to the beginning of an array and returns the new length of the array. Modifies original array.
    •	slice(): Returns a shallow copy of a portion of an array into a new array object selected from start to end (end not included) where start and end 
               represent the index of items in that array. Does not modify original array.
    •	splice(): Changes the contents of an array by removing or replacing existing elements and/or adding new elements in place. Modifies original array.
    •	concat(): Returns a new array that is a concatenation of two or more arrays. Does not modify original arrays.
    •	join(): Joins all elements of an array into a string. Does not modify original array.
    •	reverse(): Reverses the order of elements in an array. Modifies original array.
    •	sort(): Sorts

