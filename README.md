1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
2. How do you create and insert a new element into the DOM?
3. What is Event Bubbling and how does it work?
4. What is Event Delegation in JavaScript? Why is it useful?
5. What is the difference between preventDefault() and stopPropagation() methods?


 1.**ans**: getElementByI it is used to find a HTML elemenet by it's id name, getElementsByClassName it is used to find a html element by it's class name and querySelector / querySelectorAll is used to find all HTML element that match a specified CSS selector.

 2.**Create a New Element**: We use document.createElement() and to insert into DOM we can use method like apppendChild(),append().

 3.**ans**: Event bubbling a mechanism where an event triggered on a child element propagates upward through its Parents. 

 4.**ans**: Event Delegation is a mechanism where when we want some code to run when the user interacts with any one of a large number of child elements, we set the event listener on their parent and have events that happen on them bubble up to their parent rather than      having to set the event listener on every child individually.

 5.**ans**: PreventDefault() stops the Default action of a browser where StopPropagation() works when it is called inside an event handler, prevents the event from bubbling up to any other elements.
