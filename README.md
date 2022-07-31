# Uncle Bob - Clean Code
My notes from listening to lessons available on [youtube](https://www.youtube.com/watch?v=7EmboKQH8lM)

___

## Comments
- degrade over time
- can be misleading if they simplify things or aren't exactly correct
- TODO code must be either done or deleted before you checked the code in
- should be easily understandable

## Naming
- a variable named just "d" (days) or "i" (index) has a proper name length for it's scope, if it's just a single line. For multi-line code it's not sufficient, because you might lose context
- variable name length could be based on the scope of the code that contains them - local for function, instance for class, global for app
- classes like "Proudct" and "ProductData" - you can't tell the difference from them

## Other
- release the code when you know it works and it's entirely finished to the best of your ability
- your expectation of code should be - the code should become with time
- write/design code to be testable from the beginning
- write as less code as possible that does the job
- technical debt introduces problems wight from the beginning - you go fast by going well
