# Magical-Creatures
In this programming assignment you will practice using ArrayLists, Inheritance and Polymorphism. 

In this programming assignment you will practice using ArrayLists, Inheritance and Polymorphism. You are to 
write a game called Magical Creatures War. You will do this by implementing a class called MagicalCreature 
that can be used to create a magical creature that is defined by a name, type, color and age. All of these 
characteristics are of String type except age which is an integer. There is one attribute that keeps track of 
whether the creature is alive or dead. Use a Boolean variable called alive to store this information. There are 
four types of magical creatures: Dragon, Elf, Genie and Goblin. Write four derived classes for each of these 
creatures using the tables given below: Write a main program for the game using the rules given.

Create the classes for the four derived types using the tables given below. Note that all attributes will have 
private access and all instance methods will be public.
 Keep the following game rules in mind:
 Rules of the game:
 Dragons cannot be killed. 
 A young dragon who is under 40 years old cannot kill
 Elves and Goblins cannot kill
 Elves can have a shield. Those with a shield cannot be killed
 Genies can have wands. Only Genies that have a wand can kill
 Creatures cannot kill themselves

Read the creatures information from a text file called creatures.txt. Each creature occupies one line in 
the data file and contains name, type, color and age. 
 Create and populate an ArrayList of MagicalCreatures by processing one line at a time of the data file. 
The line of text is to be split using the split method into an array of String containing four String tokens 
representing the four attributes.
 The war game consists of moves. The number of moves is decided by the user. Each move consists of an 
attack by one magical creature on another. The attacker and victim both need to adhere to the rules of the 
game which will decide if the attacker is eligible to kill or the victim is a candidate that can die. In each 
move, the selection of the attacker and victim is done randomly using the Random class.
 After each move, dead creatures are removed from the game, (from the Arraylist) and the list of 
creatures that are still alive is printed.
