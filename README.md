NBA COUNTER APP.


NBA COUNTER APP THAT UPDATES SCORES (three point plays, free throws, jumpers/postups).


Built using HTML, CSS, JAVASCRIPT.

This JavaScript code sets up event listeners for three buttons, increase, decrease, and reset.
When the "increase" button is clicked, the count is incremented by 1.
When the "decrease" button is clicked, the count is decremented by 1. 
When the "reset" button is clicked, the count is reset back to 0. 

The value of the count is displayed on the page by updating the text content of the element with an ID of "value".
This JavaScript code is a simple implementation of a counter that increments, decrements, and resets the count value. It uses the DOM API to manipulate the HTML elements on the page.
The code starts by declaring the variables for the count, and the three buttons used to increment, decrement, and reset the count. The document.querySelector method is used to select the HTML elements using their CSS selectors.
The code then sets up three event listeners for each of the buttons. The addEventListener method is used to attach an event listener to each button. When a button is clicked, the corresponding event listener function is triggered, which updates the count value and displays it on the page. The e.currentTarget.classList property is used to determine which button was clicked, based on its class name.
