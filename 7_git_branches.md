# List all the branches

    $$ git branch

## Create a branch

    $$ git branch xyz

## switch between branches

    $$ git checkout xyz

    $$ git switch abc

## Delet a branch

    $$ git branch -d xyz

## Switch to a branch by creating it (easy way)

    $$ git checkout -b xyz

## Merge a branch into master branch

    $$ git merge xyz

## Undo merging a branch

    $$ git reset --hard <commit ID of the last commit in master branch>

## Merge a branch into master with only one commit

    [1] First way:

        1. Merge the xyz branch into master using squash flag (--squash)

        2. Make a commit

    [2] Second way:

        1. Merge the xyz branch into master

        2. Normal reset (not --hard) to the last commit was made in the master branch

        3. Make a commit
