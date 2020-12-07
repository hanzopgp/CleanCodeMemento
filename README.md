# CleanCodeMemento

## General :

- Cleaning code is almost as long as making code work
- Sometimes, making code work is less important than doing clean code because no one will be able to help if no one understands it
- Avoid switch statements unless it's really easy to understand or won't need update 
- A module should be open for extension but closed for modification (Open Close principle)

## Functions :

- The name of a function should always contain verbs
- Should be really small
- Around 3-15 lines
- One function does one thing
- It shouldn't be possible to extract another function if the function is clean
- Won't be lost in all these tiny function if you name it well
- Avoid more than 3 arguments
- Boolean should not be a function argument, it mean functions could be extracted from that function

## Indenting :

- One or two level of indentation maximum in a function 

## Objects :

- When a function needs several arguments, you should use objects
- Some switch statements can be replace by OOP
