

## ToDo: World Travel File Navigation

We're going to practice our command line file navigation skills by traveling around the world. Get your bags packed! We have a file structure representing the world that looks like this: 

![alt text](http://www.gliffy.com/go/publish/image/6025639/L.png "Countries Tree")
[Click here for a larger version](https://camo.githubusercontent.com/508535c0e81338f8d74168b9d04b272ef487661b/687474703a2f2f7777772e676c696666792e636f6d2f676f2f7075626c6973682f696d6167652f363032353633392f4c2e706e67)

### Refresher
You're going to be identifying the `cd` command to switch into different directories and travel around the geography tree. 

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

# Your Challenge

Write the commands for the following directory changes:

?: Mexico City to Caracas

(X) cd ../../../South_America/Venezuela/Caracas
( ) cd Earth/South_America/Caracas
( ) cd South_America/Venezuela/Caracas

?: Caracas to Europe

( ) cd ../Earth/Europe
( ) cd ../../Europe
(X) cd ../../../Europe

?: Europe to Africa
(X) cd ../Africa
( ) cd Africa
( ) cd ../../../Africa

?: Africa to Addis Ababa

( ) cd ~/Addis_Ababa
( ) cd Addis_Ababa
(X) cd Ethiopia/Addis_Ababa

?: Addis Ababa to Rome

(X) cd ../../../Europe/Italy/Rome
( ) cd Europe/Italy/Rome
( ) cd Earth/Italy/Rome

?: Rome to Windhoek

( ) cd ../Namibia/Windhoek
(X) cd ../../../Africa/Namibia/Windhoek
( ) cd Earth/Africa/Namibia/Windhoek

?: Windhoek to Brazilia

(X) cd ../../../South_America/Brazil/Brazilia
( ) cd ../../South_America/Brazil/Brazilia
( ) cd ../../Earth/Brazilia

?: Brazilia to Mexico City to Italy to Beijing

( ) cd Earth/Mexcio_City/Beijing/Italy
( ) cd ../../Mexico/Italy/Beijing
(X) cd ../../../NorthAmerica/Mexico/MexicoCity/../../Europe/Italy/../../Asia/China/Beijing

???


<p data-visibility='hidden'>View <a href='https://learn.co/lessons/hs-cli-world-travel-todo' title='ToDo: World Travel File Navigation'>ToDo: World Travel File Navigation</a> on Learn.co and start learning to code for free.</p>
