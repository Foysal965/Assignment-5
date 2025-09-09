<!-- Questions and Answers -->

<!-- Question 1 -->
1.What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
Answers: 
###getElementById Returns one element with the specified ID.
###getElementsByClassName Returns a live HTMLCollection of all elements with the given class.
###querySelector Returns the first matching element (CSS selector based).
###querySelectorAll Returns a static NodeList of all matching elements (CSS selector based).
<!-- Question 2 -->
2.How do you create and insert a new element into the DOM?
Answers:
###For creating a new element into the DOM i will use document.createElement() this method.
###For insert a new element into the DOM i will use appendChild() this method.
<!-- Question 3 -->
3.What is Event Bubbling and how does it work?
Answers:
###Event Bubbling is a JavaScript event propagation method and it works by letting an event triggered on a child element automatically propagate up to its parent elements.
<!-- Question 4 -->
4.What is Event Delegation in JavaScript? Why is it useful?
Answers:
###Event Delegation is a technique where instead of attaching separate event listeners to child elements it attach a single event listener to the parent element and Instead of adding separate listeners for multiple child elements the parent's single listener handles them all.
<!-- Question 5 -->
5.What is the difference between preventDefault() and stopPropagation() methods?
Answers:
###Prevents the default browser behavior for an event.
###stopPropagation() method is being used to prevent the event from bubbling or capturing up to parent elements.