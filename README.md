# CFGDataDegreeNotes
Notes from the CFG Degree - Data Stream

#JavaScript Notes
#Session 1
console.log() - Prints direct to to the console


#Session 2
For loops: for(var i = starting number; i < largest number; i++) {
  statement1;
  statement2;
}

#Session 3
Array indexing starts at 0
array.length - .length is an object method, not a function
array.shift() 
array.split(',') - converts string to array, which expects the delimiter argument from the string
array.concat(arg=Array) - concat is a method, which adds the argument array to the original array
Variable incrementing: ++, --


#Session 4: HTML and CSS
Use DOM (Document Object Model)
array.appendChild(listElement);

#Session 6
getElementsByTagName()
getElementsById()
Event listeners
Timers
Traversing the DOM
Local Storage



--- Random
I have created an array and got them to populate in an ul using the DOM. Is there a way to use the DOM to create a button that appears with them. I’ve used document.createElement() but can’t work out the syntax to use the append to show the item in the array AND the button.

Stavros - Assistant 19:13
Maybe you want to create the ul element and then you can add the following:

const li = document.createElement("li");
li.textContent = items[i];
1. Reference the <ul> element.
2. Loop through each item in the array.
3. Inside the loop, create a new <li> element and set its text content to the current item.
4. Still inside the loop, create a new <button> element and set its text.
5. Add an event listener to the button.
6. Append the button to the <li> element.
7. Finally, append the <li> element.


![image](https://github.com/ttcng/CFGDataDegreeNotes/assets/68971902/59c96807-521e-490e-8532-938fe9ea3322)

# Design Flow and Design Patterns

Design pattersn are typical solutions to common prbolems in software design - blueprints that can customize to solve particular design problems in code.

- Creation: patterns to create objects and design ways of creating objects simply
- Structural: assembling classes into larger structures, keeping them effecient
- Behavioural: algorithms and assignment of responsibiliites between objects

  ## Approach
  1. Clarify requirements using design questions
  2. High level design (diagram)
 
### Requirements
### Design questions
- 

  
