# Wordle-C
This project implements a fun wordle game!

#Usage
This code is supposed to be ran from the terminal. Having the terminal open on this folder run ".\wordle.exe 5" or recompile it using "gcc -o  wordle wordle.c cs50.c" and then run ".\wordle.exe 5"
See that the extension of the output file mighy vary depending on your operatig system.

You can run:
".\wordle.exe 5" This will choose words of 5 letters
".\wordle.exe 6" This will choose words of 6 letters
".\wordle.exe 7" This will choose words of 7 letters
".\wordle.exe 8" This will choose words of 8 letters

We run it like this because this program takes command line argument for the number of letter word we want

#Rules
You have 6 attempts to get the correct answer.
We give color hints so you know what letters are in the word either in the correct position or not, and the words that are not in the word at all.

<font color="green">Green background on the letter means the letter is in the word and in the correct position</font>
<font color="yellow"Green background on the letter means the letter is in the word but in the incorrect position</font>
<font color="red"Red background on the letter means the letter is not in the word</font>

<span style="color:green">Your text goes here</span>
<span style="color:green">Your text goes here</span>
<span style="color:green">Your text goes here</span>

$${\color{green}Red}$$
$${\color{yellow}Red}$$
$${\color{red}Red}$$

Example:

![image](https://github.com/lndmri/Wordle-C/assets/69853165/5ba4b899-3e79-4730-bf42-704731bc2bc4)

![image](https://github.com/lndmri/Wordle-C/assets/69853165/c698f744-e996-44a4-bf0e-d89800df047e)

# Language:
C
This code uses CS0 library from the CS50 course

#Enjoy Wordle!!!


