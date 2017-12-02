# Damn Anagrams

## Project: 003
### Required Language:
c++

## Introduction

The aim of this project was to create a web based Anagram solver. We needed it to solve three letter anagrams, but if possible more.

## High level Description

An application where the user is asked to enter three letters. Upon input the program should compare the given characters, and find out if its an anagram. You will be alerted if your letters were an anagram , if not an error message will display. After this you will be sent to the start page.  

### High level functional specifications

- Accepts users input.

![](https://i.imgur.com/Sdda9Gf.png)

- Compares the letters and length of the word with the library.

![](https://i.imgur.com/DKdV21f.png)

- Solves Anagrams.
- Has built in library.

### High level non-functional specifications

- The ability to solve longer anagrams.
- Possible link to definition of found word.
- Better UI: Game menu, settings, ect. 

### Application requirements
- Google Chrome
- Repl.it

### Mock-ups

### Storyboards
### Flowcharts components
### High-level user stories
### Research
### Teamwork
## Troubleshooting

- An issue i had, was that my program was displaying every word in my ![](https://i.imgur.com/SrcldYe.png) file. So that i could test my code without fear of it crashing. I created a smaller file named ![](https://i.imgur.com/7AGFixB.png) this file contained several words, making it much less intensive.
- It was a learning curve linking my library to my code. I asked my classmate if he could help me, and he showed me a way. I needed to add the ![](https://i.imgur.com/SrcldYe.png) file (Library of words) to repl.it. After doing this, i needed to link the file to my main code. I linked the two using ![](https://i.imgur.com/sUaok2C.png) . This allowed my program to access the file.

Below is a screenshot showing the problem i encountered. The program is sorting through every word in the "words.csv" file. This was causing lag due to the massive amount of information being processed. 

![](https://i.imgur.com/bslslPQ.png)

I then made a new file named ![](https://i.imgur.com/7AGFixB.png). This file contained several words, far less than the thousands in ![](https://i.imgur.com/SrcldYe.png). Switching these round made the code far less intensive.   

![](https://i.imgur.com/QdVOdBA.png)
