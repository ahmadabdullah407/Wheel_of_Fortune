# Wheel_of_Fortune
## Description:
- This is final course Project of course [Python Classes and Inheritence](https://www.coursera.org/learn/python-classes-inheritance) of [Python 3 Programming Specialization](https://www.coursera.org/specializations/python-3-programming) offered by [University of Michigan](https://umich.edu/) on [Coursera](https://www.coursera.org/).  
- This is a game of wheel of fortune played between a specified number of human players and computer players.
- There is 1 [python code file](https://github.com/ahmadabdullah407/Wheel_of_Fortune/blob/main/Wheel_of_Fortune.py) as well as 2 [.json](https://en.wikipedia.org/wiki/JSON#:~:text=JSON%20(JavaScript%20Object%20Notation%2C%20pronounced,or%20any%20other%20serializable%20value).) files ([phrases](https://github.com/ahmadabdullah407/Wheel_of_Fortune/blob/main/phrases.json) and [wheel](https://github.com/ahmadabdullah407/Wheel_of_Fortune/blob/main/wheel.json))that contain [.json](https://en.wikipedia.org/wiki/JSON#:~:text=JSON%20(JavaScript%20Object%20Notation%2C%20pronounced,or%20any%20other%20serializable%20value).) format data required for code to run.
## Requirements:
- You need [Python 3](https://www.python.org/) installed to run this code
- This code requires random,json and time modules to run (All of them come builtin so you may not need to worry about it much)
## How to play:
1. 1st of all computer will ask you "how many human player?" (you need to specify number of human players).
2. Then computer will ask you name of each player (you need to specify name of each player).
3. Then computer will ask you "How many computer players?" (you need to specify number of computer players).
4. Computer will ask you "what difficulty for the computers?" (you need to enter integer between 1 to 10, 10 being most difficult).
5. Computer will autoselect cetagory and shows the phrase as hidden blanks.
6. At players turn computer will auto rotate wheel of fortune and specify a cash amount as well as prize to player at his turn according to wheel.
07. Remember there are penalties too on wheel you can land on bankrupt and loose all the cash you won(does not affect prizes) or land on loose a turn and loose your turn.
06. Each player will either have to guess an alphabet "a-z"at his turn or he can also guess complete phrase and win game or skip your turn by entering "pass".
07. For each correct letter guessed you will get the cash amount that you landed on in wheel.
08. For a letter appearing more than once in phrase player will get "cash * number of times letter appeared".
9.  Letters will be revealed as they are guessed and you will not be able to guess a letter thats already been guessed.
10. For wrong guess you will loose your turn.
11. Person who wins most cash wins the game.
