# Coding 101 Gettting Started

Start here to ensure you can connect an existing repository to a scratch org and push your work.

# Setup

[Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) this repository

Create a [new branch](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository) - name it whatever you like, but note it down!

[Clone](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository) to your local machine

On your local machine, `cd` into the directory created for your clone and switch to your new branch using the command:

`git checkout <branchname>`

## Implementing

Carry out all work in your local filesystem using VS Code, as you will 
need to send them back to Github.

1. Create a scratch org or connect to an existing developer edition
1. Push/deploy the code - this will fail as there is a class missing
1. Using the Salesforce extensions for VS Code, execute the command to create a new Apex class. Name the class `GettingStarted` and accept the default location.
1. Push the source again - this time it should succeed.

## Submitting Your Solution for Assessment

Please note that assessment is only available to BrightGen employees or by prior arrangement with Keir Bowden (aka Bob Buzzard). If you don't satisfy this criteria your pull request will not be reviewed.

Add `keirbowden` as a [collaborator](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/managing-access-to-your-personal-repositories/inviting-collaborators-to-a-personal-repository) to your new repository

The commands below are if you are using Git from the command line - you can also use the VS Code built-in [source control functionality](https://code.visualstudio.com/docs/editor/versioncontrol).

Stage your new and changed files using the command:

`git add <filename>`

and then commit the changes :

`git commit`

and push these to the remote repository

`git push origin <branchname>`

Once you are happy with your solution, [open a pull request](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)

Then wait!
