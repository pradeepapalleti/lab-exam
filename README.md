# lab-exam
exp 4 :- cloning is completed using
---
$ git clone https://github.com/pradeepapalleti/lab-exam.git
---
exp1:- creating,adding to stagging area and commiting new file
---
$ touch exp1.c
$ git add .
$ git commit -m "created nd commited new file"
---
exp 2 & 6 :- creating a new branch and merging it to main branch
---
$ git branch featurebranch
$ git checkout featurebranch
$ touch exp2.c
$ git add .
$ git commit -m "created new file in new branch"
$ git checkout main
$ git merge featurebranch -m "merging the feature branch"
---