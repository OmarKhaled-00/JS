# Basics:
  - JavaScript is case-sensitive and uses the Unicode character set. For example, the word Früh (which means "early" in German) could be used as a variable name.
      - ## JS Example
        - ## const Früh = 1;
        - But, the variable früh is not the same as Früh because JavaScript is case sensitive
      ---
  - In JavaScript, instructions are called statements and are separated by semicolons (;).
      -Always write a semicolon after a statement, even when it is not strictly needed. This practice reduces the chances of bugs getting into the code.
--- 
# Comments: 
  - Like every programming languages , the way you write comments is common.
      - To write MultiLine comment , which allows you to write more than one line is ( /**/ ).
      - To write SingleLine comments ( // ).
  - Unless , there is a comment that looks different from those , which called **HashBang** 
      - **HashBang** comment is mostly used when you want to **Specify the interpreter automatically.**
          - If you asking what is interpreter?
              - Interpreter is a program that **reads and executes code directly**, line by line, without first turning it into a separate compiled file.
          - If you asking what is the difference between **Compiler and interpreter**
              - Compiler → Translates the entire code into machine language first, then runs it (e.g., C, C++).
              - Interpreter → Executes code line by line immediately (e.g., Python, JavaScript).
              - [What is HashBang and How can i use it](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Lexical_grammar#hashbang_comments)
  --- 
  # Outputs on the screen:
 - #### There Are many ways to display a string or a message on the screen.
  - **We will talk about the most popular ones**
    -  **console.log("Hello World");** : Prints text in the console.
    -  **window.alert("Hello World");** or **alert("Hello World");** : Displays text in a modal dialog box **(not preferred because it interrupts user interaction)**. 
    -  **document.write("Hello World");** : Displays text directly on the page like making \<h1> Hello World </h1>.
    -  **document.getElementById("demo").innerText="Hello World";** : You can change element's text with id "demo" in your html with any string you want.
    -  **Window.print()**: You can call the window.print() method in the browser to print the content of the current window.
  [See Outputs for Those](https://www.w3schools.com/js/js_output.asp)
  [See Outputs for Those](https://youtu.be/FYRypqj4Epw?si=5R0EyJJK0GQXEvYH)
    
        

