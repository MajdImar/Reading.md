
# JavaScript : Ch 10, “Error Handling & Debugging”
- If you understand execution contexts and stacks, you are more likely to find the error in your code. 
- Debugging is the process of finding errors. It involves a process of deduction. 
- The console helps narrow down the area in which the error is located, so you can try to find the exact error. 
- JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error. 
- If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback. 
- the exception object is an instance of a subclass of Throwable and is only available in error pages.
- Checked exceptions :
A checked exception is an exception that is typically a user error or a problem that cannot be foreseen by the programmer. For example, if a file is to be opened, but the file cannot be found, an exception occurs. These exceptions cannot simply be ignored at the time of compilation.
- Runtime exceptions :
A runtime exception is an exception that probably could have been avoided by the programmer. As opposed to the checked exceptions, runtime exceptions are ignored at the time of compliation.
- Errors :
These are not exceptions at all, but problems that arise beyond the control of the user or the programmer. Errors are typically ignored in your code because you can rarely do anything about an error. For example, if a stack overflow occurs, an error will arise. They are also ignored at the time of compilation.
