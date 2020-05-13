**Handy git one liner which deletes all local branches except for master**<br>- *shared by Jethro May*

`git branch | grep -v "master" | xargs git branch -D`

**Delete all local branches except master and develop.**<br>
*The -v means “except” and the -e’s add words to be excepted*<br>- *shared by Wesley Martin*

`git branch | grep -v -e "master" -e "develop" | xargs git branch -D`