# KnowTheScoreBefore

Final project for the Building AI course

## Summary

Predicts the outcome of football matches. Even a game as unpredictable as football can be described by a mathematical model and an outcome of the game can be calculated using AI methods.


## Background


Half of the world's population older than 10 years can be more or less attributed to the army of football fans, including both fans and people who sympathize with this game. But the game itself is only half of the story. The rest of the time people spend arguing, analyzing and predicting. 

A program that makes scientific predictions of the outcome of football matches will certainly not replace the Octopus - predictor, but will be a huge addition to football life off the field.

Besides this, the program will be a very good advertisement for Artificial intelligence methods and Programming in general. Seeing correct predictions people will wonder - HOW??. If the forecast is wrong, people will think - What if we add this and this parameter? Then it should work.


Which problems does your idea solve? How common or frequent is this problem? What is your personal motivation? Why is this topic important or interesting?

KnowTheScoreBefore will have the following functions:
* Scientific approach to predicting outcome of the football match
* Enliven football analysis and debates
* Encourage and inspire to study AI


## How is it used?

The AI will gather data of all players of both teams. By considering several parameters such as Fifa indexes of all players, recent hystory of mathces between the given teams, new players and etc. it will give a probsbility predictions of Win or Loose. Also by considering individual skills of Defenders, Forwards and Goalkeepers the program will be able to estimate the score of the game.

Neural Networks can be used to predict the outcome. The system can be trained with a huge amount of open football results from football hystory.

Simple code example using NumPy:
![football match predictions](/AI.png)


This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods

Due to the huge popularity of football, all the data can be found on various open sources and there is no need to collect it yourself. 
All statistics of each player - their strengths and weaknesses expressed in numerical terms can be taken from [fifaindex.com](https://www.fifaindex.com)
Hystory of matches between the given teams can be taken from [flashscore.com] (https://www.flashscore.com)


| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

Obtained predictions are just a possibility. Football is not an exact science and, fortunately for fans, carries an element of unpredictability. The outcome depends on a large number of different factors, including even the goalkeeper's yesterday's diarrhea. All of them cannot be taken into account. Thus, the programm will never be able to forecast an outcome with 100% probability.

We should take into account that the program can be used for betting purposes, which is highly undesirable.

## What next?

In the future, the program will be able to predict not only football matches but also other sports. 

If we consider business competition as a game between two entrepreneurs, we can draw parallels with the game of football and transform the program to indicate the steps that will lead to "victory" in business.


## Acknowledgments

  <br>For example: [Football match predictions Designed by Flatstudio](https://naked-science.ru/article/sci/iskusstvennyy-intellekt-predskazal) / [CC BY 3.0](https://creativecommons.org/licenses/by/3.0)
