---
tags: cli, kids, bash
language: cli, bash
level: 1
type: todo
---

##ToDo: World Travel File Navigation

We're going to practice our command line file navigation skills by traveling around the world. Get your bags packed!

![alt text](http://www.gliffy.com/go/publish/image/6025639/L.png "Countries Tree")
[Click here for a larger version](https://camo.githubusercontent.com/508535c0e81338f8d74168b9d04b272ef487661b/687474703a2f2f7777772e676c696666792e636f6d2f676f2f7075626c6973682f696d6167652f363032353633392f4c2e706e67)

###Refresher
You're going to be using the `cd` command to switch into different directories and travel around the geography tree above. 

Let's quickly review absolute and relative file paths. If I'm currently in the directory called TORONTO and I want to move to another city inside Canada, OTTAWA, there are two ways I can do this:

**Absolute**, where we explicitly write the entire path to the directory where we're trying to go. An absolute path is a path that points to the same location on the file system regardless of the working directory. They start with / because that is the root of your file system.
```
cd /Earth/NorthAmerica/Canada/Ottawa
```

**Relative**, where we write the path based on our current working directory. A relative path is a path relative to the working directory of the user or application, so the full absolute path will not have to be given. They start with the name of a directory or a file.
```
cd ../Ottawa
```
Remember that `..` is used to go up a level on the tree.

So if I wanted to use a relative path to go from Madrid to Peru, I would write:
```
cd ../../../SouthAmerica/Peru
```
(I use `..` three times in a row because I need to move up three levels before I can go down the tree.)

???

###Your Challenge

Write the commands for the following directory changes:

?: Mexico City to Caracas
() cd ../../../SouthAmerica/Venezuela/Caracas
() cd Earth/SouthAmerica/Caracas
() cd SouthAmerica/Venezuela/Caracas

?: Caracas to Europe
() cd ../Earth/Europe
() cd ../Europe
() cd ../../../Europe

?: Europe to Africa
() cd ../Africa
() cd Africa
() cd ../../../Africa

?: Africa to Addis Ababa
() cd ~/AddisAbaba
() cd AddisAbaba
() cd Ethiopia/AddisAbaba

?: Addis Ababa to Rome
() cd ../../../Europe/Italy/Rome
() cd Europe/Italy/Rome
() cd Earth/Italy/Rome

?: Rome to Windhoek
() cd ../Namibia/Windhoek
() cd ../../../Africa/Namibia/Windhoek
() cd Earth/Africa/Namibia/Windhoek

?: Windhoek to Brazilia
() cd ../../../SouthAmerica/Brazil/Brazilia
() cd ../../SouthAmerica/Brazil/Brazilia
() cd ../../Earth/Brazilia

?: Brazilia to Mexico City to Italy to Beijing
() cd Earth/MexcioCity/Beijing/Italy
() cd ../../Mexico/Italy/Beijing
() cd ../../../NorthAmerica/Mexico/MexicoCity/../../Europe/Italy/../../Asia/China/Beijing

???
###Bonus

Using the `mkdir` command, build out the file structure in the diagram and use `touch` to place a text file called `me.txt` inside the 'Mexico City' directory. Then use the `mv` command to move `me.txt` along the path that we made above (Mexico City to Caracas, etc...).
