This is the Decoder ring project from Thinkful's Flex Engineering course. The instructions are as follows:

"You are planning a surprise birthday party for one of your friends who loves escape rooms and puzzles. What better way to practice your new coding skills than to build an application that will help you encode and decode all kinds of fun messages?

You are tasked with building functions for an application that will either encode or decode a string using a variety of ciphers. For each cipher, you should make a series of tests using Mocha and Chai to confirm that your cipher works.

All of the functions can be found inside of the src/ directory. Each function and cipher is described below.

Below is a checklist of what you need to accomplish.

[ ] Complete the caesar() function.
[ ] Write tests for the caesar() function.
[ ] Complete the polybius() function.
[ ] Write tests for the polybius() function.
[ ] Complete the substitution() function.
[ ] Write tests for the substitution() function.

The Caesar shift is a type of substitution cipher originally used by Julius Caesar to protect messages of military significance. It relies on taking the alphabet and "shifting" letters to the right or left, based on the typical alphabetic order.

For example, if you were to "shift" the alphabet to the right by 3, the letter A would become D.

The Polybius square is a cipher that is achieved by arranging a typical alphabet into a grid. Each letter is represented through a coordinate. For example, in the above table, the letter B would be represented by the numerical pair 21.

Typically, it is possible to arrange the letters however you like and read off the coordinates in whatever direction you like. In this example, the grid will be arranged as above and coordinates will be read by comparing the first digit to the number on the top of the table and the second digit to that on the left.

The substitution cipher requires a standard alphabet and a substitution alphabet. Letters from the standard alphabet will be transposed to the substitution alphabet. This cipher requires that the recipient have the substitution alphabet, otherwise it will be difficult for them to decode the message.

For example, in the image above, the word HELLO would be translated as follows:

H becomes R.
E becomes M.
L becomes W.
O becomes L.
This would result in the code RMWWL. To decrypt this code, you would simply take the result and transpose back from the substitution alphabet to the standard alphabet."
