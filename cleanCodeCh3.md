
# *CHAPTER THREE: FUNCTIONS*

#### This chapter discusses how to write effective functions, starting from examples where code clarity is improved by refactoring, showing how to reduce their complexity.

## Small!

#### Functions should be small, ideally about 20 lines. The shorter they are, the easier they are to understand and handle.

## Blocks and Indenting

#### Blocks within if or while structures should consist of a single line that invokes a function, which facilitates to read.

## Do One Thing

#### Functions should accomplish only one task. A good function reduces a broad concept to simple steps, avoiding confusing mixes of abstraction levels.

## Sections within Functions

#### Functions that are divided into sections such as “statements” or “filters” usually indicate that they are doing more than one thing. A truly focused function cannot be divided into sections.

![clean_code5.png](Imagenes%2Fclean_code5.png)

## Use Descriptive Names

#### Appropriate names make the code easier to understand, since they describe the purpose of each function. Long and descriptive names are preferable to short and vague ones.

## Function Arguments

#### Functions should ideally have no arguments (monadic). If they need one or two arguments, they are acceptable, but from three or more (polyadic) they are not. Arguments make testing more difficult by requiring additional combinations of values and also make output arguments less intuitive.

## Common Monadic Forms & Flag Arguments

#### There are two main reasons for a single argument: to ask a question or to process and transform the argument, returning a value. In monadic functions, the names should be clear to differentiate.
#### Using boolean arguments is not best because it complicates the signature and suggests that the function does multiple things. This can make the code confusing.

## Dyadic Functions & Triads

#### A function with two arguments is less intuitive than a monadic one. If the two arguments are related (such as coordinates), it is reasonable, but otherwise it is better to make two functions.
#### Functions with three arguments (Triads) are quite difficult to understand, it is better to avoid them when possible and refactor into several functions.

## Verbs and Keywords

#### Selecting appropriate names for functions and their arguments helps to understand the function.In a monadic function, for example, the name should indicate the verb and the argument the noun (example: write(name)).
#### For dyadic or triadic functions, adding keywords to function names improves clarity (example: assertExpectedEqualsActual(expected, actual)).

![clean_code6.png](Imagenes%2Fclean_code6.png)

## Output Arguments

#### Arguments are inputs to a function. For this reason, output arguments should be avoided as input arguments. Instead of appendFooter(report), report.appendFooter() would be preferable.

## Don’t Repeat Yourself & Structured Programming 

#### Duplication of code increases the risk of errors and maintenance overhead so avoid repeating code.
#### Structured programming suggests only one input and output per function, in small functions this rule may change.

## Conclusion

#### This chapter highlights the importance of keeping functions short, well named and structured, but especially that the functions contribute to a clear and precise language that facilitates the understanding of the code.
