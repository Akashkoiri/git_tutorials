# Merge branchs with conflicts

    ## On abc branch:

        1. Complete your project (make all commits time to time)

    ## On master branch:

        1. merge abc branch to the master branch with the squash flag [Recomended to use squash flag]

            $$ git merge abc --squash

        2. Edit the conflict, delete the extra lines of conflict

        3. Add changes to the staging area

        4. commit the changes with your desired massage

## How to undo a conflict & start over

    $$ git merge --abort

    $$ git rebase --abort
