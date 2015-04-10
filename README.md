# This Repository contains various notes for git

## The following are basic commands:
  * git init (to initialize a local Git repo in this directory)
  * git remote add origin https://github.com/yourUserNameHere/test-repo.git
  * git add <filename> (to add a file)
  * git commit -a -m "Update again"
  * git push (to push it to remote repository.)
  * If modified in github, use 'git pull origin master' to sync local files with remote files.

## R Programming:
  * R.version.string - show current version of R
  * Inf - Infinity (1/0), NaN - Not a Number (0/0)
  * ls() - show current variables/objects
  * getwd() - show working directory
  * attributes(object) - show attributes of an object
  * install.packages("swirl")
  * rm(list=ls()) - remove all objects in the list, as shown using ls().
  * library(swirl) - to load the swirl package
  * swirl() - to run the swirl package

## Swirl Notes:
  You can exit swirl and return to the R prompt (>) at any time by pressing the
  Esc key. If you are already at the prompt, type bye() to exit and save your
  progress. When you exit properly, you'll see a short message letting you know
  you've done so.

  When you are at the R prompt (>):
  * Typing skip() allows you to skip the current question.
  * Typing play() lets you experiment with R on your own; swirl will ignore what you do...
  * UNTIL you type nxt() which will regain swirl's attention.
  * Typing bye() causes swirl to exit. Your progress will be saved.
  * Typing main() returns you to swirl's main menu.
  * Typing info() displays these options again.
