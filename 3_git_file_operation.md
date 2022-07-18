# Check current status

    $$ git status

## How to check all the changes of a file

    $$ git diff {file name}

## Add changes to the staging area

    ## For a specific untracked file

        $$ git add index.html

    ## For all untracked files

        $$ git add .

## Discard changes of a not staged file

    $$ git restore index.html

## Restore changes from the staging area

    $$ git restore --staged index.html

## Commit the changes from staging area

    $$ git commit -m "Your massage"

## Check all the commits we have made

    ## Default view:

        $$ git log

    ## Oneline view:

        $$ git log --oneline

## Change the last commit massage if any mistake is happend

    $$ git commit --amend -m "Created our first feature"
        => From:
            770697b (HEAD -> master) Created the first feature
        
            To
            7cfa710 (HEAD -> master) Created our first feature
