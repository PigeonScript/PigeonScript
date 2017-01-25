# Instruction Listings #

## Instructions ##
Note: "(X(Y) inputs)" is to be read as "X or Y inputs", and similarly, "(X(Y)(Z) inputs)" is to be read as "X or Y or Z inputs"

### Math ###
- `+` (2(1)(0) inputs)
  - *int, int*: Adds two integers: `12+` -> `3`
  - *int*: Takes an integer input from the user, adds it to *int*: `1+`(user input 2) -> `3`
  - *null*: Takes integer input from the user twice, adds them together: `+`(user input 1)(user input 2) -> `3`
- `-` (2(1)(0) inputs)
  - *int, int*: Subtracts two integers: `31-` -> `2`
  - *int*: Takes an integer input from the user, subtracts it from *int*: `3-`(user input 2) -> `2`
  - *null*: Takes integer input from the user twice, adds them together: `-`(user input 1)(user input 2) -> `3`
- `*` (2(1)(0) inputs)
  - *int, int*: Multiplies two integers: `32*` -> `6`
  - *int*: Takes an integer input from the user, multiplies it to *int*: `3*`(user input 2) -> `6`
  - *null*: Takes integer input from the user twice, multiplies them together: `*`(user input 3)(user input 2) -> `6`
- `^` (2(1)(0) inputs)
  - *int, int*: Raises one integer to the power of another: `32^` -> `9`
  - *int*: Takes an integer input from the user, subtracts it from *int*: `3-`(user input 2) -> `2`
  - *null*: Takes integer input from the user twice, adds them together: `^`(user input 1)(user input 2) -> `3`
- `%` (2(1)(0) inputs)
  - *int, int*: Takes the first integer mod the second integer: `32%` -> `1`
  - *int*: Takes an integer input from the user, takes the first integer mod the user-input integer: `3%`(user input 2) -> `1`
  - *null*: Takes integer input from the user twice, takes the first user-input integer mod the second: `%`(user input 3)(user input 2) -> `1`
- `!` (1 input)
  - *int*: Takes the factorial of the integer: `3!` -> `6`
