# Checking out a previous commit

    $$ git checkout <commit id>

## Return to the last commit

    $$ git checkout master

## Restore the changes of a previous commit using a new commit

    $$ git revert <commit id>

    @@ We can change the massage in the file that opens after revert

## Merging commits

    [Note: rebase should use before any push if working in a team]

    $$ git rebase -i HEAD~5
                          ^
                          |
    @@ How many commits you want to merge:
        @@ Squash : If we want all massages in the new commit together
        @@ fixup : If we don't want those massages

## If we make a commit mistakenly & we want to delet the commit but we want to keep the changes in the file

    $$ git reset <commit id>

## If we don't want the commit as well as the changes in the file

    $$ git reset <commit id> --hard
    
    @@ [Alert: Use with precautions]
