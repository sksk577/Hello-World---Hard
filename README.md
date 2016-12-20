# Hello World-Hard
project by 24-team


## Project contributer
- Sang Won Kim
- 
- 

## Goal and Introduce of this project

'Hello World!' is a sentense that we meet necessarily when we start study about programming.
Our goal is to make several programs, which use basic principle, like sentense 'Hello World!'.
ex) simple games

Our project is using 'Python', and license is 'Apache License 2.0'.


### Apache License 2.0

This license means anybody can make a program derived from this software, and transfer copyright of this software.
Also, anybody can use software privately and commercially which followed 'Apache License 2.0'.

When you used software which followed 'Apache License 2.0' for development, or privately and commercially use, etc.,
you must specify in program clearly that 'This software follow 'Apache License 2.0', and developed by Apache Software Foundation.'.

If you want to know about this license detailedly, please click this link.
http://www.apache.org/licenses/LICENSE-2.0


## Commited program list

1. lottery.c
2. daylotto.py(Name is modified : lottery.py -> daylotto.py)
3. matgo.zip(matgo.py and many flies of 'matgo.py's class' are here.)
4. lottery_2.zip(New program)
 

## Manual of commited program

*lottery.c - uncompleted*
*Lottery.py*
*NOTICE : This program's name is modified -> daylotto.py*
```
This program is a daliy lottery program in 'Final Fantasy XIV'.
We make this program in Python.

1. Program will make 3*3 matrix, and will put natual number randomly(1~9). these numbers are not revealed. 
2. Program will open one space in matrix, and you can choose three space, which you want to know.
3. You should choose one row, or column.
4. Program will open all numbers, and sum three numbers you choosed.
5. You will get the amount that corresponds to the sum of the numbers.
```

*Matgo.py*
```
This program is a gamble program which called 'matgo' in Korea.
To play this game, you must follow some rules: 
```
![matgo1](/matgocards.jpg)
```
From upper left to bottom right, this cards have numbers : 1~12.
* Kinds of 11st card is called 'Ttong', and Kinds of 12nd card is called 'Be'.
```
![matgo2](/matgoicon.png)
```
Cards having this icon, they are called 'Gwang'.
```
```
Cards having red or blue band, they are called 'Tthi'.
Cards having birds, animals, insects, they are called 'Youlkkot'. 
The rest of cards, they are called 'Phe'.

These cards are setting specific positon:
'Gwang' : left
'Tthi' : bottom of center
'Youlkkot' : upper 'Tthi'(not above 'Tthi')
'Phe' : leftest position

Set four cards on the floor -> Give five cards to another player -> Bring five cards ->'
Set four cards on the floor -> Give five cards to another player -> Bring five cards ->
Pile up the rest of cards at the center -  between you to another player. 

In your turn, you can set one card in your hand on the floor.

If three 'Gwang' cards are gathered, you get 3 points. If 'Be' card is in that cards, you get 2 points.
If any four 'Gwang' cards are gathered, you get 4 points.
If any five 'Gwang' cards are gathered, you get 15 points.

If three 'Tthi' cards are gathered, you get 3 points. These cards must have same color of band.
If three 'Tthi' that have red band without words, you get 3 points.
If any five 'Tthi' cards are gathered, you get 1 points. six cards = 2 points, seven cards = 3 points....

If any ten 'Phe' cards are gathered, you get 1 points. eleven cards = 2 points, twelve cards = 3 points....
In these cards,
* 'Ttong' card(11st card) that has red color, this card is 2 points.
* 9th card is 2 points. This card also can use 'Youlkkot' card.
* 12nd card that has red color, this card is 2 points.
* If another player's ten 'Phe' cards are gathered, while a number of yours are lower than seven,
Points that another player will get are doubled.

If any five 'Youlkkot' cards are gathered, you get 1 point. six cards = 2 points....
* If three 'Youlkkot' cards that have a bird picture are gathered, you get 5 points.
* If any seven 'Youlkkot' cards are gathered, Points that you will get are doubled.

Player that get 7 point first is winner of that game.

If you want to know about matgo, please ask about matgo to your korean friends.
```

*Lottery_2.py*
```
This program is gambler simulation program containing daylotto.py, Matgo.py, etc.
In this program, you will be a gambler who have a goal - Of course earn lot of money.
Try to earn lot of money as you can!

NOTICE for Korean user : This program's korean name is '주갤러 시뮬레이션'
```
## Screenshot

### Lottery.py
![Screenshot1](./Screenshot1.PNG)
### Matgo.py
![Screenshot2](./Screenshot2.PNG)
### Lottery_2.py
![Screenshot3](./Screenshot3.PNG)
