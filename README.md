# DCE-iteration-1

A simple scripted chatbot example for TU/e Industrial Design's Master course Designing Conversational Experiences. The example saves a user response and uses them later. In addition, the user is provided a question with three options, which each have a separate response.

This example uses PicoCSS, a CSS framework that helps with simplicity. https://picocss.com/

# Functions

Different reusable functions are used:

`sendMessage()` to 'send' user input, and provide a response

`userChoice(choice)` to provide a different response for each of the three options provided

`addMessage(type, input)` to place add the messages to the screen. For `type`, choose between `'user'` or `'assistant'`. This will place the message either to the right or left side of the screen. for `input`, provide the text to be placed on the screen.

If you want to save a message to a variable, you can do so as soon as it is received, such as is done with the `hobby` variable (`hobby = msg`). In addition to this, you have access to the complete message history through the `messageHistory` array. Retrieving that same hobby is possible by running `messageHistory[1].content`.
