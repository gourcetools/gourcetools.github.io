---
layout: default
title: 🧠 proompting
nav_order: 2
---

# Creating Effective Coding Prompts for ChatGPT: A Comprehensive Guide

## Basics of a prompt:

### Specify the programming language:
Begin the prompt by explicitly stating the programming language you want to use. This ensures that ChatGPT generates code in the correct language, avoiding potential misunderstandings.
Example: "Please help me write a Python program..."

### Provide clear instructions:
Clearly describe the task or problem you need help with. Be specific about input, output, and any constraints or conditions that should be met by the solution.
Example: "...to read a CSV file, process its data, and generate a summary report containing the average, minimum, and maximum values for each column."

### Break down the problem:
When working with complex tasks, it can be helpful to break the problem into smaller, more manageable steps. This approach makes it easier for ChatGPT to provide accurate, focused code snippets.
Example: "First, let's start by writing a function to read the CSV file and store its contents in a data structure."

###Request step-by-step explanations:
Ask for step-by-step explanations or code walkthroughs alongside the generated code. This will help you better understand the logic and flow of the program, and allows for easier troubleshooting if issues arise.
Example: "Please provide a step-by-step explanation of the code and its functionality."

### Encourage modularity:
Request the code in a modular format, such as functions or classes, that can be easily integrated into an existing codebase. This also facilitates testing and debugging individual components of the solution.
Example: "Please provide the solution as a series of reusable functions."

### Be mindful of code length:
When asking for longer code snippets, be aware that the response may be cut off due to character limitations. To mitigate this, consider requesting code in smaller segments, focusing on specific parts of the task.
Example: "Now that we have the CSV data stored, let's write a function to calculate the average value for each column."

### Requesting code continuation:
If a response is cut off or you need a continuation, reference the previous response in your new prompt to maintain context.
Example: "Please continue from where we left off in the previous code snippet for calculating column averages in Python."



## 10 Examples of Final Prompts for Coding Tasks:

```
"Celp me write a Python function to find the nth Fibonacci number using recursion. 
The function should take an integer 'n' as input and return the corresponding Fibonacci number."
```

```
"Create a JavaScript function to validate an email address using regular expressions. 
The function should return 'true' if the email is valid, and 'false' otherwise."
```

```
"Please provide a step-by-step tutorial on implementing a basic REST API using Node.js and Express. 
Start with setting up the project and creating endpoints for CRUD operations on a 'tasks' resource."
```

```
"Help me design a SQL query to retrieve the total sales for each product from a 'sales' table,
grouped by product ID and ordered by total sales in descending order."
```

```
"Create a Java method to check if a given string is a palindrome. 
The method should return 'true' if the string is a palindrome and 'false' otherwise."
```

```
"Assist me in writing a C++ program to perform matrix multiplication. 
The program should read two matrices from the user, multiply them, and output the resulting matrix."
```

```
"Help me create a Ruby script to scrape data from a website using the Nokogiri gem. 
The script should extract the titles and URLs of articles from a given news website's homepage."
```

```
"Write a PHP function to connect to a MySQL database using PDO. 
The function should take database credentials as input and return a PDO instance if the connection is successful."
```

```
"Help me implement a simple 'to-do list' app using React. 
Start with creating a form to add new tasks, and display the list of tasks with checkboxes to mark them as completed."
```

```
"Guide me through building a basic neural network in TensorFlow for image classification. 
Begin with loading and preprocessing the data, then define and train the neural network model."
```


# Elaboration:

When crafting prompts for coding tasks, it's crucial to *provide clear instructions* to ensure that the generated code accurately addresses the problem at hand. Here are some tips to help you achieve clarity in your instructions:

## Define the problem statement:
*Begin by outlining the problem* or task that the code should address. 
*Be specific about the desired outcome*, which will help the AI to understand the scope of the task.

```
Write a Python function to merge two sorted lists into a single sorted list. The function should accept two sorted lists as input and return a new list containing all elements from the input lists in ascending order."
```


## Specify input and output:
Clearly state the expected *input* and *output* for the code, including data types, structures, and constraints. 
This information helps the AI to generate code that meets *your requirements*.

```
Create a JavaScript function that takes two arrays of integers, 'array1' and 'array2',
and returns a new array containing the intersection of the two input arrays, 
i.e., elements that are present in both arrays
```


## Describe desired behavior:
*Explain any special requirements or desired behavior* of the code, such as handling edge cases, performance considerations, or specific algorithms to be used.

```
write a Java method to implement the binary search algorithm on an array of integers.
The method should accept a sorted array and a target value as input,
and return the index of the target value if found, or -1 if not found.
The solution should have a time complexity of O(log n).
```


## Provide examples:
Include *examples of input* and *expected output* to help the AI understand the desired functionality more concretely. 
This can also help to clarify any ambiguities in your instructions.

```
Create a Python function to convert an integer to its Roman numeral representation.
For example, if the input is 42, the output should be 'XLII';
if the input is 1990, the output should be 'MCMXC'.
The input integer will be between 1 and 3999.
```


## Use precise language:
Be explicit and precise in your wording to minimize the chances of *misinterpretation*. 
Avoid using *vague or ambiguous language* that might lead to *confusion* or *incorrect code generation*.

```
Write a C++ function to calculate the arithmetic mean of an array of floating-point numbers. The function should accept an array and its length as input, and return the mean value as a floating-point number with a precision of two decimal places.
```


## Ask for explanations:
Request explanations, *comments*, or *documentation* within the code to ensure that the generated solution is easy to understand and maintain.

```
Please provide comments explaining each part of the code you provide and its purpose.
```

```
Please write documentation the API.
```

By following these guidelines, you can provide clear instructions that will enable ChatGPT to generate accurate and useful code for your specific tasks.
*Clear instructions are key* to a successful collaboration with the AI and will help you get the most out of your interactions.



