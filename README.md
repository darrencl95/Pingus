Fuck you shantanu

======================================
Git Basics
======================================

BEFORE MAKING ANY CHANGES:

    git checkout -b <your branch name>
    =make changes=
    git add .
    git commit -m "<helpful commit message>"
    git push origin <your branch name> (OPTIONAL)



TO MERGE WITH MASTER:

    git checkout <your branch name>
    git pull --rebase origin master
    git checkout master
    git pull
    git merge <your branch name>
    git status (CHECK CHANGES)
    git log (MAKE SURE YOUR COMMIT IS ON TOP)
    git push



TO ROLL BACK CODE CHANGES:

    git reset --hard <commit hash>
    =or=
    git reset --hard HEAD~<number of commits to roll back>



TO ROLL BACK COMMITS ONLY:

    git reset --soft <commit hash>
    =or=
    git reset --soft HEAD~<number of commits to roll back>

