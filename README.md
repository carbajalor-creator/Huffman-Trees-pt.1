# Huffman-Trees-pt.1
Gabriela Carbajal Ortiz
007715715
https://github.com/carbajalor-creator/Huffman-Trees-pt.1.git

Collaboration & Sources
For this project I used outside resources to learn how to use filesystem and how that interacted with the functions I would be making to make sure I was reading the input in correctly and getting the tokens to the output file correctly. I looked up if there were any functions that help with traversing a string such as in.peek() and how to use them correctly. I used AI to help me fix bugs when I couldn't find them myself or when I had errors that I didn't understand what they meant. 

Implementation Details
In this project I made a couple helper functions that work as filters for the the tokens. The function isLetter takes in a character and makes sure that it is a letter without an accent. The flushToken function cleans up the token making sure it is in lowercase and adds it to the words vector. I had issues with capitalized letters still getting through to the output file so in my tokenize function I made sure to lower all the letters before they were being sent to the output file. My readWord function reads in the input and makes the tokens allowing apostrophes only when in between letters. 

Testing & Status
I've tested my program with TheBells.txt and it successfully prints the words in the output file all lowercased and separated by a newline. The tokens do not have any unwanted characters and every unwanted character is treated as a separator. The only issue is that it does not let apostrophes in that are between letters.
