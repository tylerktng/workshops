---
title: "Activity 6 - Functions"
date: 2022-02-23
weight: 4
draft: true
---

Very well!

You've already done a lot of the program!

In this activity we will use the functions to group parts of the code.

{{% notice tip %}}

Functions
Functions allow us to divide the work a program does into smaller tasks separate from the main part, that is, from the main function.

We can understand functions as a machine that when we turn it on, executes instructions and processes, which return a final result. You can have several machines that perform different processes, and we identify each one with the type of result it returns and a name.

In this activity we will use the void functions, which do not return anything, but only process instructions.

To declare (create) a function, we must use the following structure outside the main function:

void name_funcion(){
    //Code here
}
In this code we can distinguish:

The type of variable. First of all we must indicate what the function will return. In this case it is why you will not return anything.void
The name we want to give to the function. In the example it is: .nombre_funcion
The parentheses that are added to the name to identify that it is a function.()
The braces that determine the block of code that will execute the function.{}

Calling a function
As we said, functions go outside the function. Therefore, when we press Run, the code block of functions will not run. Therefore, within the function we must call the function. We must tell the program when we want that block of code to run. To call a function, we must use the following statement:main()main()

name_funcion();
We just have to write the name we gave to the function, followed by the parentheses, and of course a semicolon This will cause the instructions that are inside the function to be executed.;nombre_funcion()

Parameters of a function
When we declare a function, we can pass parameters to it. These are variables that we give the function to use, because, the function not being in the main function, cannot access the variables that we declare there. The parameters go within the parentheses of the function. Example:

void name_funcion(int sum, int &number){
    number += sum
}
And in the main function we should have the following:

int main(){
    int x = 25;
    int y = 5;
    name_funcion(y, x);
}
Let's understand in detail what we did:

In the function, we write within the parentheses which variables we are going to pass on. Then, within the function we can use those variables.
In main, we had two variables already declared, which we then passed as a parameter to the created function. By doing this, the variable equals the variable . The variable has this symbol forward. This means that if we modify the variable within the function, the variable that we pass to it in the main function will also be modified. That is, the variable will be modified by the function since we pass it by reference when writing that symbol in front. When we do not put this symbol, even if we modify its value in the function, in main we will not see that change. {{% /notice %}}sumaynumero&numerox
That's great! Let's create 2 functions. One to encrypt the message, and the other to decrypt it. For this, we're going to use code we already had, and we'll program something new as well.

Declares a void function, just like encrypting, but to decrypt the name.

Copies the contents of the encrypt() function into the new function.

In the sum variable, instead of adding, subtract the character of the name and character of the keyword, and add a letter 'a' (not subtraction) so that the final character is a letter of the alphabet and not any character.

Change the condition to turn in the alphabet. Instead of seeing if the sum is greater than the character 'z', write if the sum is less than 'a', and then if that condition is met, add 25 to the variable addition (not subtraction).

In the main function, it calls the corresponding function in the condition if it is to encrypt or decrypt a message.

When you're done, you can press Run and try the following examples:

programmer
1
reina
witvczxipigrmg
2
reina
Also make up your own secret words!

{{< alert theme="warning" >}} Be careful, in this program we must always write the strings and characters in lowercase letter. {{< /alert >}}

Remember that you can always go back to previous activities to remember something.

<iframe height="600px" width="100%" src="https://replit.com/@nuevofoundation/actividad-6?lite=true#main.cpp" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin-scripts allow-modals"></iframe>
{{< alert theme="danger" >}} Be careful. To paste something into the console, right-click paste. Otherwise it may not work. {{< /alert >}}