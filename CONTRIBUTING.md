## GETTING CONNECTED
To connect to the repo from your local environment, run:

`git remote add origin <repository.git>`

If existing .git, then run first:

`git remote remove origin`


## GETTING UP-TO-DATE
To start, pull all of the existing `main` code into your local repo by running:

`git checkout main`

and

`git pull`


## MAKING CONTRIBUTIONS
To use the primary `edit` branch, run:

`git push -u origin edit`
This will set the default push location to the branch named `edit` (will always exist).

If you would like to use a separate branch, run:

`git branch <branch-name>` to create
NOTE: main, edit, and master are protected names. Please do not use.

`git checkout <branch-name>` to select
This is another way to set your default push branch without using the `-u` flag on push.

`git push` to push to the checked out branch



## MERGING REQUESTS
Requests will merged to `main` by initiating a pull request on GitHub.com
