client.py :
Main file that contains all the code for retrieving the flags and solving the wordle.
Approach: 
1. I start out by putting the wordlist into a list.
2. I guess the first word in the list and store the solution (receive 2, correct indices and letters) and sotore that in the sol list anmd the correct index
3. I also save the letter if it's present in a list (receive 1, correct letter, incorrect index) so we can use it later 
4. I then move onto the next word in the list and check if that word has EVERY letter in the presenet letters list and has the sol indices correct as well. If they satisfy both the conditions, then I guess that word and repeat the process, otherwise I move onto the next word in the list.

