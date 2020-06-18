# Technical-Documentation-Page



<!DOCTYPE  html>
<html>
  <head>
    <title> Technical Documentation Page </title>
    <style>
      body {
       background-color: #D3D3D3; 
      }
      #main-doc }
      
      }
      h1, h2 {
        font-size: 70px;
      }
      
      .main-section {
        
      }
      #Introduction {
        line-height: 1.5;
      }
      #JavaScript_And_Java {
        line-height: 1.5;
      }
      #Hello_World {
        line-height:: 1.5;
      }
      #Variables {
        line-height: 1.5;
      }
      #Declaring_Variables {
        line-height: 1.5;
      }
      #Variable_Scope {
        line-height: 1.5;
      }
      #Global_Variables {
line-height: 1.5;
      }
      #Constants {
        line-height: 1.5;
      }
      #Data_Types {
        line-height: 1.5;
      }
      #navbar {
        line-height: 1.5;
        position: fixed;
      }
      .nav-link {
        display: block;
        text-decoration: none;
        color: green;
        font-size: 30px;
      }
      #References {
        line-height: 1.5;
      }
      p, li, code {
        font-size: 30px;
      }
      @media (min-width: 1200px) {
      p {
     font-size: 30px;
      }
      }
    </style>
  </head>
  <body>
    
    <div>
         <nav id="navbar">
           <header> <h2> JS Documentation </h2> </header> 
           <a class="nav-link" href="#Introduction"> Introduction </a>
           <a class="nav-link" href="#JavaScript_And_Java"> JavaScript And Java </a>
           <a class="nav-link" href="#Hello_World"> Hello World </a>
           <a class="nav-link" href="#Variables"> Variables </a>
           <a class="nav-link" href="#Declaring_Variables"> Declaring Variables </a>
           <a class="nav-link" href="#Variable_Scope"> Variable Scope </a>
           <a class="nav-link" href="#Global_Variables"> Global Variables </a>
           <a class="nav-link" href="#Constants"> Constants </a>
           <a class="nav-link" href="#Data_Types"> Data Types </a>
           <a class="nav-link" href="#References"> References </a>
      </nav>
      </div>
    
    <main id="main-doc">
    <section class="main-section" id="Introduction">
      <header> <h1> Introduction </h1> </header>
      <p> JavaScript is a cross-platform, object-oriented scripting language. It is a small and lightweight language. Inside a host environment (for example, a web browser), JavaScript can be connected to the objects of its environment to provide programmatic control over them.
      </p>
      <p>
JavaScript contains a standard library of objects, such as Array, Date, and Math, and a core set of language elements such as operators, control structures, and statements. Core JavaScript can be extended for a variety of purposes by supplementing it with additional objects; for example:
      </p>
      <ul>
  <li>
Client-side JavaScript extends the core language by supplying objects to control a browser and its Document Object Model (DOM). For example, client-side extensions allow an application to place elements on an HTML form and respond to user events such as mouse clicks, form input, and page navigation.
  </li>
  <li>
Server-side JavaScript extends the core language by supplying objects relevant to running JavaScript on a server. For example, server-side extensions allow an application to communicate with a database, provide continuity of information from one invocation to another of the application, or perform file manipulations on a server.
  </li>
      </ul>

   
    
    
    
    
      </section>
      
    <section class="main-section" id="JavaScript_And_Java">
      <header> <h1> JavaScript And Java </h1> </header>
      <p>  JavaScript and Java are similar in some ways but fundamentally different in some others. The JavaScript language resembles Java but does not have Java's static typing and strong type checking. JavaScript follows most Java expression syntax, naming conventions and basic control-flow constructs which was the reason why it was renamed from LiveScript to JavaScript.
      </p>
      <p>
In contrast to Java's compile-time system of classes built by declarations, JavaScript supports a runtime system based on a small number of data types representing numeric, Boolean, and string values. JavaScript has a prototype-based object model instead of the more common class-based object model. The prototype-based model provides dynamic inheritance; that is, what is inherited can vary for individual objects. JavaScript also supports functions without any special declarative requirements. Functions can be properties of objects, executing as loosely typed methods.
      </p>
      <p>
JavaScript is a very free-form language compared to Java. You do not have to declare all variables, classes, and methods. You do not have to be concerned with whether methods are public, private, or protected, and you do not have to implement interfaces. Variables, parameters, and function return types are not explicitly typed.   </p>
 
    
    
    
    
      </section>
      
      <section class="main-section" id="Hello_World">
        <header> <h1> Hello World </h1>  </header>
        <p>       To get started with writing JavaScript, open the Scratchpad and write your first "Hello world" JavaScript code: </p>
        <code> function greetMe(yourName) { alert("Hello " + yourName); } 
          greetMe("World"); </code>
          <p>
Select the code in the pad and hit </p>
      
      
      
      
    
      
      
      </section>
      
      <section class="main-section" id="Variables">
        <header> <h1> Variables  </h1> </header>
        <p>   You use variables as symbolic names for values in your application. The names of variables, called identifiers, conform to certain rules. </p>

<p> A JavaScript identifier must start with a letter, underscore (_), or dollar sign ($); subsequent characters can also be digits (0-9). Because JavaScript is case sensitive, letters include the characters "A" through "Z" (uppercase) and the characters "a" through "z" (lowercase). </p>

<p> You can use ISO 8859-1 or Unicode letters such as å and ü in identifiers. You can also use the Unicode escape sequences as characters in identifiers. Some examples of legal names are Number_hits, temp99, and _name.  </p>
        
        
        
        
        
        
        
        
      </section>
      
      <section class="main-section" id="Declaring_Variables">
        <header> <h1> Declaring Variables  </h1> </header> 
        <p>      You can declare a variable in three ways: </p>
        <p> With the keyword var. For example, </p>
var x = 42.
        <p> This syntax can be used to declare both local and global variables. </p>

        <p> By simply assigning it a value. For example, </p>
        <code> x = 42. </code>
<p> This always declares a global variable. It generates a strict JavaScript warning. You shouldn't use this variant. </p>

        <p> With the keyword let. For example, </p>
        <code> let y = 13. </code>
<p> This syntax can be used to declare a block scope local variable. See Variable scope below. </p>
        
        
        
        
        
        
        
      </section>
      
      <section class="main-section" id="Variable_Scope">
        <header> <h1> Variable Scope </h1> </header>
        <p>    When you declare a variable outside of any function, it is called a global variable, because it is available to any other code in the current document. When you declare a variable within a function, it is called a local variable, because it is available only within that function. </p>

<p> JavaScript before ECMAScript 2015 does not have block statement scope; rather, a variable declared within a block is local to the function (or global scope) that the block resides within. For example the following code will log 5, because the scope of x is the function (or global context) within which x is declared, not the block, which in this case is an if statement. </p>

        <code>if (true) { var x = 5; } console.log(x); // 5 </code>
<p>  This behavior changes, when using the let declaration introduced in ECMAScript 2015. </p>

<code> if (true) { let y = 5; } console.log(y); // ReferenceError: y is not
  defined </code>
 
        
        
        
        
        
        
      </section>
    
      <section class="main-section" id="Global_Variables">
        <header> <h1> Global Variables </h1> </header>
        <p>     Global variables are in fact properties of the global object. In web pages the global object is window, so you can set and access global variables using the window.variable syntax. </p>

<p> Consequently, you can access global variables declared in one window or frame from another window or frame by specifying the window or frame name. For example, if a variable called phoneNumber is declared in a document, you can refer to this variable from an iframe as parent.phoneNumber.  </p>
        
        
        
        
        
        
        
      </section>  
        
        <section class="main-section" id="Constants">
          <header> <h1> Constants  </h1> </header>
          <p>      You can create a read-only, named constant with the const keyword. The syntax of a constant identifier is the same as for a variable identifier: it must start with a letter, underscore or dollar sign and can contain alphabetic, numeric, or underscore characters. </p>

          <code> const PI = 3.14; </code>
<p> A constant cannot change value through assignment or be re-declared while the script is running. It has to be initialized to a value. </p>

<p> The scope rules for constants are the same as those for let block scope variables. If the const keyword is omitted, the identifier is assumed to represent a variable. </p>

<p> You cannot declare a constant with the same name as a function or variable in the same scope. For example: </p>

<code>// THIS WILL CAUSE AN ERROR function f() {}; const f = 5; // THIS WILL
CAUSE AN ERROR ALSO function f() { const g = 5; var g; //statements
  } </code>
<p> However, object attributes are not protected, so the following statement is executed without problems. </p>
          <code> const MY_OBJECT = {"key": "value"}; MY_OBJECT.key = "otherValue";    </code>
          
          
          
          
          
          
          
          
      </section>
      
      <section class="main-section" id="Data_Types">
        <header> <h1> Data Types </h1> </header>
        <p>     The latest ECMAScript standard defines seven data types: </p>
<ul> 
  <li>
        Six data types that are primitives:
  </li>
        </ul>
Boolean. true and false.
null. A special keyword denoting a null value. Because JavaScript is case-sensitive, null is not the same as Null, NULL, or any other variant.
undefined. A top-level property whose value is undefined.
Number. 42 or 3.14159.
String. "Howdy"
Symbol (new in ECMAScript 2015). A data type whose instances are unique and immutable.
<ul>
  <li>
        and Object
  </li>
        </ul>
<p> Although these data types are a relatively small amount, they enable you to perform useful functions with your applications. Objects and functions are the other fundamental elements in the language. You can think of objects as named containers for values, and functions as procedures that your application can perform.
</p>
        
        
        
        
        
        
        
        
        
      </section>
        
      <section class="main-section" id="References">
        <header> <h1>  References </h1> </header>
        <ul>
          <li> All the documentation in this page is taken from <a href="freecodecamp.org"> freecodecamp.org </a> </li>
        </ul>
        
      </section>
          
    </main>
    </body>
  
       <script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"> </script>

      </html>
