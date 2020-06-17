# Polish-Math
 A calculator that uses polish notation
 
 ![](https://i.imgur.com/VRstLLp.png)

### Explanation
As opposed to the "normal" way we're accustomed to writing mathematical equations, [Polish notation](https://en.wikipedia.org/wiki/Polish_notation) assumes the operator to preceed the integers being calculated, that means that an equation you know to be written as `(4 + 5)`, would be written as `(+ 4 5)`

Or for example, `4 * ((3 / 9) * (6 - 3))` would be written as `* 4 (* (/ 3 9) (- 6 3))`

This is the way the `Lisp` programming languages take in and process information

### Usage

#### Simple usage
Download `calculator.exe` and double click it. Then type in your equations.

Supported operations are `+, -, *, /, and %`

#### Compilation
Download/clone all files and run `gcc -std=c99 -Wall parsing.c mpc.c -o calculator
ls` to compile

(assumes you have gcc compiler installed)
