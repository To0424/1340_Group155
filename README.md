# 1340_Group155

Members:  <br />



Game Description: <br />

**Archeforce** <br />
--------------------
This is a ordianry Japan style RPG game combined with wordle. <br />
Instead of collecting items by walking around the map, we decided to implement wordle for user to make attack. <br />
The faster you guess the word, the higher damage you can make! <br/>
Gold will drop throughout the battle so that players can upgrade their damages and HP bar. <br />

Game Rule: <br />
1. Follow the instruction strictly.
2. Enjoy!

**Features implemented:** <br/>
Generation of random game sets or events: Used in wordle part to random generate a word from word list to be guessed. <br/>
Data structures for storing game status: Vector and Map have been used to store Player/Enemy HP and Attack values.<br/>
Dynamic memory management: We used vector in wordle with .shrink() function to ensure no extra memory is used.<br/>
File input/output: We used a word_list.txt to store all the words for wordle and import all of them into a vector when executing the code so that extra words could be added easily.<br/>

HOW TO COMPILE <br/>
1. Download this Repo with "git clone https://github.com/vincent3036/1340_Group155", or choose download as zip and unzip it.
2. Type "make" to compile the file and type "make clean" to clean * .o files.<br/>
3. Type the command "./main" to run the game.<br/>
