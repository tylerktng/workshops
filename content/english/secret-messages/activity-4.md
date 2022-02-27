---
title: "Activity 4 - Conditions"
date: 2022-2-23
weight: 4
draft: true
---

Very well!

We are getting closer and closer to making our secret messages. But also, let's not forget that we have to be able to decipher those messages!

For that, we are going to enter in the console a 1, if we want to encrypt a message, or the number 2, if we want to decrypt it.

For this we will need the CONDITIONS.

{{% notice tip %}}

Conditions if / else
A condition in programming is an instruction or a group of instructions, which can be executed or not, based on whether a condition is true. It would look something like this: IF (if) this happens, execute these instructions, IF NOT (else), execute these other instructions.

Example

if(3 > 1){
  cout << "3 es mayor que 1" << endl;
}else{
  cout << "3 no es mayor que 1" << endl;
}
The program will print:

3 es mayor que 1
There we are indicating that if the number 3 is greater than 1, let what is between its keys be executed. And otherwise, let what is in the block be executed. In the example, the else block will not run because the if condition is true, since 3 is greater than 1.if(3>1){ }else

To create conditions, we usually use the following logical operators in the parentheses of the if statements:()

Example: and a=5b=3

Less than: (5 is less than 3?)a < b
Less than or equal to: (is 5 less than or equal to 3?)a <= b
Greater than: (5 is greater than 3?)a > b
Greater than or equal to: (is 5 greater than or equal to 3?)a >= b
Same as: (5 equals 3?)a == b
other than : (5 is different than 3?)a != b
{{% /notice %}}

For the activity, we are going to use a condition to know if what we want is to create a secret message (encrypt it) or decrypt a message (decrypt it).

For that, we must follow the following steps:

Creates a variable of type int.
Enter the contents of that variable by console.
It creates an if/else condition to know if the number entered is equal to 1, therefore, we want to encrypt a message, or else, we want to decrypt it.
Print by console in each case which is what we want to do. Ex: "Encrypt a message" or "Decrypt a message".
To help, remember that you can go back to the other activities.

<iframe height="600px" width="100%" src="https://replit.com/@nuevofoundation/actividad-4?lite=true#main.cpp" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin-allow-scripts allow-modals"></iframe>