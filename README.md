# JS-notes


-------------------------------------
console.log('script.js has loaded');
// Single-line and multi-line comments in JavaScript
// are the same as the ones in C#

-----------------------------------

-----------------------------------
**Function** performs a specific task, taking the input (Parameters) and return output (Return Value)
it's like a box that contains items, 
function calculateRectangle can be used repeatedly for a calculation where let you'd have to rewrite the calculation again and again

function calculateRectangleArea(width, height) {
  return width * height;
}

let area1 = calculateRectangleArea(5, 10);
console.log("Area 1:", area1); // Output: Area 1: 50

let area2 = calculateRectangleArea(3, 7);
console.log("Area 2:", area2); // Output: Area 2: 21
-----------------------------------

-------------------------------
let declares variables, let myHeading = document.querySelector('h2');  
**myHeading** was created by using let and selected the first h2 element using .querySelector 
.querySelector returns a reference by finding the element
let myHeading =      document.querySelector('h2'); //it only stops at the first variable found

let=declaration, document.querySelector('h2'); =Assignment

{
   **let** only accessible within the block
}
PS don't always require a function
-------------------------------

----------------------------------
**div > p**   > is the child combinator, it only selects p elements that are direct children of a div element  css 005
----------------------------------

--------------------------------
**prompt** is used to show a message in the code, let firstParty = prompt('Enter the name of the disclosing party'); 006
--------------------------------

----------------------------
**const** is constant,meaning variables declared with const cannot be reassigned once they are initialized
const myConstant = 10;
// myConstant = 20; // Error: Assignment to constant variable
{
   **const** only accessible within the block
}
------------------------------

-----------------------------------------------
**@param** is used as documenting/noting, it is only seen in the js by you
@param {string} username The name of someone 
--------------------------------------------------

--------------------------------
**block** {
curly brackets as blocks
}
--------------------------------

--------------------------------
**var** If you declare a var inside a function, it's accessible anywhere within that function, even inside nested blocks 
like if statements or for loops
if outside a function, it is completely accessible anywhere in the code
