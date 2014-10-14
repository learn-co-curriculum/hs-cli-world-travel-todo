---
tags: cli, kids, bash
language: cli, bash
level: 1
type: todo
---

#ToDo: World Travel File Navigation

We're going to practice our command line file navigation skills by doing some world travel.

![alt text](http://www.gliffy.com/go/publish/image/6025639/L.png "Countries Tree")
(Click on the image to get a larger version!)

##Refresher
We're going to be using the `cd` command to switch in to different directories and travel around the geography tree above. 

Let's remind ourselves about absolute and relative file paths. If I'm currently in the directory called TORONTO and I want to move to another city inside Canada, OTTAWA. There are two ways I can do this.

**Absolute**, where we explicitly write the enitre path to the directory where we're trying to go:
```
cd Earth/NorthAmerica/Canada/Ottawa
```

**Relative**, where we write the path based on our current working directory:
```
cd ../Ottawa
```

Remember that `..` is used to go up a level on the tree.

So if I wanted to use a relative path to go from Madrid to Peru, I would write:
```
cd ../../../SouthAmerica/Peru
```
(I use `..` three times in a row because I need to move up three levels before I can go down the tree).

##Your Challenge

Write the commands for the following directory changes:

+ Mexico City to Caracas
+ Caracas to Europe
+ Europe to Africa
+ Africa to Addis Ababa
+ Addis Ababa to Rome
+ Rome to Windhoek
+ Windhoek to Brazilia
+ Brazilia to Mexico City to Italy to Beijing

## Bonus

Using the `mkdir` command, build out the file structure in the diagram and use touch to place a text file called me.txt inside the 'Mexico City' directory. Then use the `mv` command to move 'me.txt' along the path that we made above (Mexico city to Caracas, etc...).
