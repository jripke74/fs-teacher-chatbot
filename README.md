# fs-teacher-chatbot
In this workshop, you will continue to learn more about JavaScript strings by building a chatbot.

You will learn how to work with template literals, and the indexOf method.

Step 1
In this workshop, you are going to continue learning about strings by building a Teacher Chatbot.

To begin, add a console statement, with the message of "Hi there!".

Step 2
Now it is time to set the bot's name.

Create a variable called botName and assign it the string value of "teacherBot".

Step 3
Now it is time to create a greeting using the botName variable.

In the previous lecture videos, you learned how to concatenate strings using template literals like this:

Example Code
const name = "John";

// "Hello, John!"
`Hello, ${name}!`;
Start by creating a variable called greeting.

Next, using template literal syntax, assign a string that says My name is, followed by the botName variable, and ending with a period (.).

Finally, log the greeting variable to the console.

Step 4
The next step is to create a few more variables that will be used in future bot messages.

Create a variable called subject and assign it the string value "JavaScript".

Then create a variable called topic and assign it the string value "strings".

Step 5
Now, it's time to use the variables you created in the previous step.

In the lecture videos, you learned how to work with template literals like this:

Example Code
const name = "John";
const age = 30;

// My name is John and I am 30 years old.
`My name is ${name} and I am ${age} years old.`;
Start by creating a sentence variable.

Using template literal syntax, assign the string Today, you will learn about [topic variable goes here] in [subject variable goes here]. to the sentence variable.

You will replace the [topic variable goes here] and [subject variable goes here] placeholders with the topic and subject variables and ${} syntax.

Finally, log the sentence variable to the console.

Step 6
For this next portion of the project, the bot will teach working with the string length property.

Start by creating a new variable called strLengthIntro.

Then using template literal syntax, assign the string Here is an example of using the length property on the word [subject]. to the strLengthIntro variable.

Replace [subject] with the subject variable like you did earlier.

Finally, log the strLengthIntro variable to the console.

Step 7
To get the length of a string, you can use the length property. This property returns the number of characters in a string.

Here is an example:

Example Code
const greeting = "Hello, world!";

// Output: 13
console.log(greeting.length);
Start by using the length property to get the length of the subject string and log that value to the console.

Step 8
Now it is time to get the length of the topic string.

You can use template literals inside console statements like this:

Example Code
const developer = "Jessica";
console.log(`Hello, my name is ${developer}.`);
Start by outputting the message Here is an example of using the length property on the word [topic]. to the console.

Remember to replace [topic] with the topic variable, and use proper template literal syntax as you did in the previous steps.

Then, add a second console.log statement that outputs the length of the topic string to the console.

Step 9
The next part of this workshop is to review accessing characters from a string.

Start by outputting the message Here is an example of accessing the first letter in the word [subject]. to the console.

Remember to replace [subject] with the subject variable and use proper template literal syntax like you did in the previous steps.

Step 10
In the previous lecture videos, you learned how to access characters in a string like this:

Example Code
const firstName = "Jessica";
// returns "J"
firstName[0];
Remember that index numbers start at 0, so the first letter in a string will always be at index 0.

Start by adding another console statement.

Inside the console statement, output the first letter of the subject variable using bracket notation and the correct index number.