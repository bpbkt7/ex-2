#Exercise 2 <sub><sup>***Due Friday, Feb 7***</sup></sub>


You're going to write a story together as a class. You are encouraged to commit multiple times but don't write more than one sentence per commit and don't commit twice in a row. Remember to create a new line for every commit so the story is easier to follow. The story itself is not the object, so just have some fun with it. 


###Objectives

* Be comfortable in a collaborative environment.
* Make a ridiculous story.
  
###Specifications

* Write more than zero sentences in story.txt
* Add a new line for every sentence.
* One sentence per commit.

### Requirements

* The story must include all of these words.
  * ninjas
  * sink
  * supernova
  * raptor
  * airplane
  * laser
  * hospital
  * professor
  * existentialism
  * fishing
  * hurricane

  
#Using RSA keys
In order to push your changes, the origin repository must know your public rsa keys.

~~https://help.github.com/articles/generating-ssh-keys~~



# Instructions

First, you are going to clone this repository. This will copy all of its contents and history onto your local machine. Navigate to where you would like the directory to be, and then use the following commands:

      $ git clone codeforge

Then have a look at the repo:

      $ git branch
      $ git status

Create a new branch in which to make your changes:

      $ git checkout -b mybranch
      
Add a sentence to the doc using your favorite editor:

      $ vim story.txt
      or
      $ vi story.txt
      or
      $ nano story.txt
      
Commit your changes

      $ git commit -am "added sentence about ninjas"
      $ git checkout master
      $ git pull
      $ git merge myBranch
      $ git push

Check back for more fun
