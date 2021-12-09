# README #

## What
This is a text based black jack game in Ruby.

It can be run in any command line that has access to Ruby. To start the game change directories in the command line until you are in the same folder as the file "black_jack.rb". Then type `ruby black_jack.rb`.

## Why
I wrote this game as the final project for RB120 at Launch school. This is there introductory to OOP in Ruby. Here is a link to the program https://launchschool.com/?utm_source so you can learn more if you are interested, but the most important part for me about this program is that it is mastery based. I don't move on to the next material until I take rigorous tests showing mastery of the material. In order for this to work they focus on the fundamentals.

Some of the fundamentals of OOP showcased in this project are polymorphism through class based inheritance and interface inheritance, access control, getter and setter methods, and collaborator objects.

Some things that I learned while working on this project.
  - Because it was so large I introduced bugs with illnamed methods for example I originally had a method named `sum` instead of `total` and a separate getter method which made it so that the method for `total` didn't update the total after changing the value of an ace from 11 to 1. I learned to be more deliberate with my setters and getters.
  - I also learned that after coding the full program is not the best time to determine which methods should be public vs private and that I should do that as I am building the classes.
  - I learned more about black_jack and how it is played in a casino. I have only played it with friends where there is no dealer.
  - I learned from rubocop that (&:method_name) is a short way to itterate through an array of objects where you only want to call one method on each object.
  - I learned how to write a readme and include a license for a github repo


## Future ideas for this project:
  - add a betting system
  - add a system pause between dealer moves (#sleep)
  - add multiple players
  - use the known cards to show probability to help train card counting
  - show text based version of card  
"------"\
"|&nbsp;&nbsp;&nbsp;&nbsp;A|"\
"|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|"\
"|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|"\
"------"
  - add automatic stand if player has 21
  - add double down
  - add split
  - add option to place insurance bet
