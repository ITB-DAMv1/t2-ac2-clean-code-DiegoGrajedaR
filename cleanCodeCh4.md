
## CHAPTER FOUR: COMMENTS

#### Comments in code can be detrimental if they are unnecessary. Comments are “necessary bugs” because, ideally, code should be self-explanatory. It is preferable to write clear and expressive code that eliminates the need for comments.

## Comments Do Not Make Up for Bad Code & Explain Yourself in Code

#### Comments should not be used as a solution for messy or confusing code. It is better to correct and clean up the code, making it understandable without the need for comments. The code must be clear enough to convey the programmer's intentions.

## When Comments Are Necessary

#### Although it is ideal to avoid comments, there are situations in which they are useful:

- *Legal Comments:* Mandatory for copyright reasons.

- *Informative and Intentional Comments:* Explain results of specific methods or decisions, especially in complex algorithms.

- *Consequence Warnings:* To warn about effects of certain tests or methods that may be costly in terms of performance.

## TODO Comments

#### They serve as reminders for future improvements or pending tasks. However, they should be used sparingly and reviewed regularly.

## Documentation in Public APIs

#### In public APIs, documentation such as Javadoc is essential for user understanding. It should be clear, accurate and relevant.

![clean_code7.png](Imagenes%2Fclean_code7.png)

## Avoid Problematic Comments

- Redundant or Obvious Comments: Do not add value, such as describing a constructor with “Default constructor”.

- Confusing or Incorrect Comments: Can be misleading and make it difficult to understand the code.

- Stammering or Rule Comments: Those that are added only to fulfill a requirement, without useful content.

- Change Log Comments: Obsolete with version control systems, they no longer provide relevant information and can hinder the code.

## Avoid Redundant Comments

#### Unnecessary Javadoc comments (for example, describing simple variables) add no value and can be misleading if poorly worded.

## Use Functions or Variables to Clarify

#### Instead of explanatory comments, it is preferable to refactor code to make it clearer and more self-descriptive, thus eliminating the need for additional explanations.

## Non-Local and Excessive Information Comments

#### Comments should refer only to nearby code. Avoid including information about other modules or irrelevant technical details, as these can quickly become outdated and confusing.

## Clear Connections

#### Comments should be precise and directly related to the code they explain. Ambiguous or confusing details are counterproductive and complicate understanding.

## Function Headers

#### Well-named, specific-purpose functions do not need extensive headers. A clear name is sufficient to express their functionality.

## Conclusion

#### In conclusion comments should be kept to a minimum and only clarify essential or non-obvious aspects of the code, avoiding irrelevant details or unnecessary historical information.
