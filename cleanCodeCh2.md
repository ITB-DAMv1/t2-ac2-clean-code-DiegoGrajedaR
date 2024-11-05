
# *CHAPTER TWO: MEANINGFUL NAMES*

#### In software development, names are fundamental, on variables, functions, files and directories. Naming correctly helps to organize the code, facilitates its understanding and maintenance.

## Use Intention-Revealing Names & Avoid Disinformation

#### A good name should clearly indicate the purpose, function and use of an element in the code, avoiding the need for clarifying comments. Precise and specific names, for example: (correct: int elapsedTimeInDays) / (incorrect: int d)

#### It is important to avoid confusing names. For example, do not use terms associated with concepts outside the context (such as hp or accountList if it is not really a list).

![clean_code3.jpg](Imagenes%2Fclean_code3.jpg)

## Use Pronounceable Names & Use Searchable Names

#### Names that are easy to pronounce help to explain the code without having to invent words. Opting for meaningful names like (generationTimestamp) instead of complex abbreviations helps to understand the code.

#### Short or numeric names (such as e or 7) make it difficult to find them in the code. Using descriptive names makes them easier to find and avoids confusion.

## Interfaces and Implementations

#### It is best to avoid prefixes on interfaces (such as “I” for IShapeFactory).It is recommended that interfaces have clear names, and, if you need to differentiate implementations, you can opt for suffixes such as Imp or C on the concrete class.

## Avoid Mental Mapping

#### Single letter names, such as i, j or k, can be used in limited scope loop counters, but in other cases they require a mental “translation”, which makes them difficult to read.

![clean_code4.jpg](Imagenes%2Fclean_code4.jpg)

## Class Names

#### Classes should have names significant or be phrases, such as Customer or AddressParser. Generic terms such as Manager, Processor, Data or Info should be avoided, as well as names that are verbs, since they do not reflect the purpose of a class.

## Don’t Pun

#### Do not use the same words for different purposes, as they generate confusion. Use distinct names such as insert or append to reflect different intentions and prevent the reader from misinterpreting the functionality.

## Final Words

#### Choosing good names requires skill, experience, and a focus on clarity and precision. Although changing names can be seen as a disruption, it improves the understandability and readability of the code.
#### Modern tools such as IDEs facilitate these changes and allow you to focus on the overall structure and clarity of the code.
