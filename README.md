# testrepo
test repository to check the git commands and Pull Requests


# git basic commands

## init

## clone 

## add

## status

## commit

## checkout

## diff

## show

## log


------------------------------------

# Sending pull requests

- requires branches - `main` branch, `feature` branch.
- Once the contributor finishes his work in `feature` branch, he can raise the `PR` to the owner to pull his changes from his `feature` branch to the base that is `original` branch.
- basically same as merge; but to able to raise `PR` there should be *no conflicts* in the merge
- owner gets a chance to review all changes (in UI), add comments to every line change if required, and to `accept` or `decline` the `PR` 
- until and unless the `PR` is either not `accept`ed or `decline`d, its `open`
- normally the owner deletes the `feature` branch, once the `PR` is accepted (i.e. changes are merged to base branch)

## From UI

Demo.

## From commandline

Reference: https://git-scm.com/docs/git-request-pull

Generates a summary of pending changes

	git request-pull [-p] <start> <url> [<end>]
