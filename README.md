# String
The program counts the number of characters in a user-entered string while ignoring spaces. It uses two different ways to declare character arrays (strings) and demonstrates string input and manipulation.

Algorithm :

Create two character arrays 'str1' and 'str2' to store strings, initialized with values.

Display 'str1' and 'str2' using cout.

Create a character array 'str3' of size 100 to store user input.

Display "Enter a string - ".

Read and store user input in 'str3' using cin.get().

Create a character pointer 'sptr' and initialize it to point to the first character of 'str3'.

Create integer variables 'counter' and 'a' and initialize 'a' to 0.

Use a 'while' loop with the condition 'a == 0': a. Inside the loop: i. Check if the character pointed to by 'sptr' is the null terminator ('\0'): - If yes, set 'a' to 1 to exit the loop. - If no, continue to the next step. ii. Check if the character pointed to by 'sptr' is not a space: - If yes, increment 'counter'. iii. Move 'sptr' to the next character in the string.

Display "Number of characters = " followed by the value of 'counter'.

End of the program.
