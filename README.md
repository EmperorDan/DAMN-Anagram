# Damn Anagrams



## Introduction

The aim of this project was to create a web based Anagram solver. We needed it to solve three letter anagrams, but if possible more.

## Mechanics

- Solves Anagrams.
- Has built in library.

## Difficulties

- My problem was incorporating a library of words into my code. I was shown a way to add the library to my program, which made it possible to draw from easily (ifstream infile("words.csv");).
- My next issue is getting the program to determine the first viable anagram. (I am currently figuring this out) [to be updated]

## Screenshots

# Current Version

Below is the current version of my anagram solver. It accepts users input, (word) and compares the letters and length of the word with the library. The problem i have is getting my program to stop, when a viable anagram has been found.

![](https://i.imgur.com/ZXiPkO4.png)

Below is a screenshot showing the problem i have encountered. The program is sorting through every word in the library. This is causing lag due to the massive amount of information that is being processed. 

![](https://i.imgur.com/AqA4kEi.png)






