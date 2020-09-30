# lab-02-guess-number

STATE: 
- Guess feedback

VIEW DERIVED FROM STATE: 
- Number of tries remaining
- Guess too high or too low
- Win/Lose Result

HTML & CSS:
1) Page layout (title, header, etc.)
1) Explain the rules to the user
1) An input of type number for specifying the guess
1) A button to click to submit the guess
1) Display of number of tries remaining
1) Display of guess too high or too low
1) Display of lose and win result

ON BUTTON CLICK:
- Random results number generated
- User input compared to the randomly selected number
- Update DOM as state changes
    - Guess too high or too low displayed
    - Number of tries remaining count goes down
    - When user correctly guesses number or runs out of tries, results are displayed
- Reset DOM elements to their initial state 
