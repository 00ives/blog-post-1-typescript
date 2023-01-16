<!--
 to create a link to another site use [Placeholder](https://site.com)
-->
<!--
References [1]https://www.youtube.com/watch?v=d56mG7DezGs
-->

<img align="center" alt="GIF" src="https://images.pexels.com/photos/1089438/pexels-photo-1089438.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" width="100%" height="200px"/>

# TypeScript

## Introduction
<!--_Create a site or blog from your GitHub repositories with GitHub Pages._ -->

<!--
  <<< Author notes: Start of the course >>>
  Include start button, a note about Actions minutes,
  and tell the learner why they should take the course.
  Each step should be wrapped in <details>/<summary>, with an `id` set.
  The start <details> should have `open` as well.
  Do not use quotes on the <details> tag attributes.
-->

<!-- to create a link to another site use [Placeholder](https://site.com)-->

Statically-typed we know the type of variables at compile time
<br>
Dynamically-typed - variables are determined at run time 

### Problem: 

One functionality of JavaScript that could be considered as a negative pertains to the fact that the language is dynamically-typed. For instance this means that, we could have a variable initialized as a String value and later on change that variable to a number value. This sparks an issue. For example, If we have a parameter taking function that accepts only a String value, and our variable that was passed into the function was switched from a String to a Number. Our code would end up breaking, and we won’t find this out until we run the program or have unit tests.[1]

 <img align="right" alt="GIF" src="https://media.istockphoto.com/id/174183942/photo/verified.jpg?s=1024x1024&w=is&k=20&c=y7--3wQXzJIj4qx-8yYcW3MFrozRWkLIUnrjXvP4hPI=" width="25%" height="200px"/>

### Solution:

TypeScript is in essence JavaScript wrapped with Static Type Checking. In TypeScript we must explicitly initialize the [type](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html) of our variables upon the declaration point. Then we pass our code to the TypeScript compiler which catches compile errors.

TypeScript is considered the brother/sister of JavaScript
Built on top of JS so that every JS file is a valid TS file
Contains: 
- **Static Typing**
- **Code Completion**
- **Refactoring**
- **Shorthand notations**
