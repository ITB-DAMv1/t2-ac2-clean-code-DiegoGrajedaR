
# *CHAPTER SEVEN: ERROR HANDLING*

#### Error handling is essential for good code performance, but it must be handled carefully. In this chapter, we propose techniques for handling errors so that code is clear and robust.

## Use Exceptions Rather Than Return Codes

#### Using return codes to indicate errors clutters up logic, as it requires immediate and repetitive checking by the caller. It is preferable to use exceptions, which separate the main logic from error handling.

## Write Your Try-Catch-Finally Statement First

#### It is useful to start by creating a try-catch-finally block to define the transactional scope. This allows you to structure your code around possible errors from the start, separating the main actions from the corrections required in case of failures.

## Provide Context with Exceptions

#### For exceptions to be useful, they must include specific context that makes it easier to identify the cause and location of the error.

![clean_code9.png](Imagenes%2Fclean_code9.png)

## Don’t Return Null

#### Returning null from a method leads to increased null checks in the code, which are error-prone. Instead, it's better to return a special object, such as an empty list (Collections.emptyList() in Java).

## Don’t Pass Null

#### Passing null as an argument is a problem, as it generates errors that are difficult to handle at runtime. Avoiding passing null allows you to write more robust and predictable code, and simplifies function calls.

## Conclusion

#### Clean code should be robust, and these goals are not mutually exclusive. By treating error handling as a separate concern from the core logic, we can write cleaner, more maintainable code.
