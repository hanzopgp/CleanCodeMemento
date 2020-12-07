# CleanCodeMemento

## Links :

- [Robert C. Martin's github](https://github.com/unclebob)
- [Cleancoder](http://cleancoder.com/products)
- [Youtube first lesson](https://www.youtube.com/watch?v=7EmboKQH8lM&ab_channel=UnityCoin)

## General :

- Cleaning code is almost as long as making code work
- Sometimes, making code work is less important than doing clean code because no one will be able to help if no one understands it
- Avoid switch statements unless it's really easy to understand or won't need update 
- A module should be open for extension but closed for modification (Open Close principle)
- Use lambda expression to avoid side effects caused by pair function (open()/close() ...)
- If there is a try catch returning an exception, it should be in a seperate function
- Avoid code duplication
- It is more important your peers know how your code works, not the computer

## Functions :

- The name of a function should always contain verbs
- Should be really small
- Around 3-15 lines
- One function does one thing
- It shouldn't be possible to extract another function if the function is clean
- Won't be lost in all these tiny function if you name it well
- Avoid more than 3 arguments
- Boolean should not be a function argument, it mean functions could be extracted from that function
- If it return a value, it should not have side effects

## Indenting :

- One or two level of indentation maximum in a function 

## Objects :

- When a function needs several arguments, you should use objects
- Some switch statements can be replace by OOP
