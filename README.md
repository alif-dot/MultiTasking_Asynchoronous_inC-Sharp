# MultiTasking&Asynchoronous

![Screenshot (32)](https://github.com/alif-dot/MultiTasking_Asynchoronous_inC-Sharp/assets/62230465/14eae005-26b9-487d-a3e1-f24898f42dc9)

The given C# program demonstrates various ways to start a task in C# .NET using different techniques and approaches. It also showcases the concepts of multi-tasking and asynchronous programming.

The program includes multiple static methods that create tasks using different mechanisms. Here's an overview of each method:

1. CreateTaskUsingAction(): This method creates a task using the Action delegate. It demonstrates how to define a task that performs a specific action.

2. CreateTaskUsingDelegate(): This method creates a task using a delegate. It showcases the use of delegates to define the task's functionality.

3. CreateTaskUsingLambdaAndNamedMethod(): This method creates a task using a lambda expression and a named method. It combines the power of lambda expressions with the clarity of a separate named method.

4. CreateTaskUsingLambdaAndAnonymousMethod(): This method creates a task using a lambda expression and an anonymous method. It demonstrates how to define a task with an anonymous method for concise and inline functionality.

5. CreateTaskUsingAsyncAwait(): This method creates a task using the async and await keywords. It showcases the use of asynchronous programming to create tasks that can await the completion of other tasks.

6. CreateAsyncTask(): This async method creates an async task using the Task.Run method. It demonstrates how to run a task asynchronously using the Task.Run method with the await keyword.

7. SolveTheMath(int firstInt, int secondInt): This async method solves a math problem by adding two integers asynchronously. It demonstrates how to use the await keyword with the Task.FromResult method and Task.Delay method to perform calculations and introduce a delay.

The Main method of the program starts by printing a description of the different ways to start a task. It then demonstrates each method by creating and starting tasks using various techniques. It also prompts the user to input two integers and solves a math problem asynchronously.

This program showcases the flexibility and power of task-based programming in C# and illustrates different approaches to achieve multi-tasking and asynchronous execution.
