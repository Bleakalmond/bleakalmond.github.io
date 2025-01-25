``` Mermaid
flowchart TD
Start([Start]) --> End([End])
*A(["Number is picked 1-100"]) --> B["Player enters number"]
B --> C{"Is number correct"}
C -- Yes --> D(["Congratulation you win"])
D --> E["Do you want to play again"]
E --> A
C -- NO --> F["Tell player higher or lower"]
F --> B
```

## Number guessing game ##
  * Computer picks random number 1-100
      * Player enters number in text box
      * Computer determines if number is correct
  * If number is correct
      * Player is show congratulations image
      * Asked if they want to guess again
      * Number is picked again
  * If number is incorrect
      * Player is given hint if number is higher or lower
      * Player enters another number in text bos based on clue
