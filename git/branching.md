**Handy git one liner which deletes all local branches except for master** *- shared by Jethro May*

`git branch | grep -v "master" | xargs git branch -D`

---

**Delete all local branches except master and develop** *- shared by Wesley Martin*

*The -v means “except” and the -e’s add words to be excepted*

`git branch | grep -v -e "master" -e "develop" | xargs git branch -D`

---

