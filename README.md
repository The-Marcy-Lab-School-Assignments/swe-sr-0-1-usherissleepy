# Technical Writing Assignment

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/how-tos/working-with-assignments#how-to-work-on-assignments).

## Prompt 1

A good technical explanation often uses a metaphor to help others understand a complex concept. Choose a metaphor to represent a Git commit. 

In a few brief paragraphs, use your chosen metaphor to explain:
* What a commit is
* How a commit is created (include the command-line syntax)
* Why commits are useful in version control.
* Why it is important to write descriptive clear messages in team settings.

### Response 1
A commit is used to save your code how it is in that moment.  Each commit is a memory of your code, so if something isn't working properly you can go back to earlier commits and inspect it.  A commit is created by first using 'git add' which stages whatever code you wrote, you'll need to stage your changed files first in order to get it ready to commit.  If you want to stage everything you've changed in any and all files you can use 'git add -A' which saves the time of individually added each file to the stage.  Then you use 'git commit -m' to commit, after '-m' you write a message to in a sense label your commit so you know which commits were for what.  An example of this would be if you added a new feature to your program you would write 'git commit -m "new feature added"'
Commits are useful because it saves each "part" added to your code so you can easily, this helps keep you organized and makes it easier to access older commits.  It's also very useful in a team setting, because it makes it easier for the team to track changes made to the program, who made those changes, where they were made, and when.  It's important to write clear descriptive clear messages in team settings because if you don't have a clear message it can make it hard for other people on your team to be able to tell what that specifc commit was for.