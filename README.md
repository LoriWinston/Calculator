# Calculator

##Outcomes

-Addition - GOAL: Display the sum of the two numbers to the user
HTML SETUP-We should be able to see on the screen: two user input boxes, a plus sign, and a button (there is also a secret place where we put the result)
        -Why do we need the input box? Because that's where the user input lives so we can add the numbers
    -Why do we need the button? we need something to click to tell the computer to show the answer
    Why do we need a secret box? We need a place to make the answer actually visible
    -Validation: Look at the screen

1)What: Grab the dom elements (the input box and the button) in javascript (using an id attribute)
    -How: make variables for each dom element using document.getElementById('whatever-id)
    -Validation: we can log the dom elements out
2) Add an Eventlistener to the button
validation: console.log 'hello world' on click
3) Get access to what the user typed in
    -How: get the '.value' property of the input element --in the cool zone of the event handler
-Validation: we can log out the user input (the number they type) on click

Use the user input to calculate the results
    Validation: log out the result to the console (in the cool zone)
   4) display that result to the user
    -How: we need to grab the secret box and inject the answer into its 'textContent' property (in the cool zone)



2) -We should be able to "get" the user input
    Add an eventlistener to the button
-Validation: console.log 'hello world' on click
-Validation: we can log out the user input (the number they type) on click

Use the user input to calculate the results
Validation: log out the results to the console
5) display that result to the user
    -How: we need to grab the secret box and inject the answer into its 'textContent' property (in the cool zone)
