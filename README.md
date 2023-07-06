# Lesson 1 Independent Challenges

## Challenge 1: from GitHub to Azure DevOps

Once you've cloned this repo, create a new repo in Azure DevOps (called `lesson-1.YOUR.NAME`), WITHOUT a README or a .gitignore, and run the following commands, replacing `___` by a suitable URL for your new repo:

```
git remote remove origin
git remote add origin ___
```

This will unlink your local repo from GitHub and link it into your new Azure DevOps repo instead. (Think of it like unplugging an appliance from one socket and plugging it into another instead.)

Finally, push the existing content to Azure DevOps (you may need to configure an upstream branch).

## Challenge 2: create a branch, add a file, commit and push

Let's get some practice creating branches.

Create a new branch off main called `groceries` and switch to this branch. Then, create a new file called `shopping_list.txt`. Add a few items on separate lines. For example:

```
Mushrooms
Broccoli
Bread
Orange juice
```

Add the file to Git's staging area, make a commit with a suitable message, and push the commit to your remote repository (you may need to configure an upstream branch).

## Challenge 3: set up a pull request

Let's get some practice opening pull requests.

On Azure DevOps, check that your new branch is present and open a pull request back to the main branch. Your shopping list file should appear in the summary of the changes.

## Challenge 4: update the file

Let's get some practice following the add-commit-push sequence.

Add some new items to your shopping list file. Add the changed file to Git's staging area, make a commit with a suitable message, and push the commit to your remote repository.

## Challenge 5: update the file without pushing

Let's try making a change that we won't push for now.

Add a single new item to the end of your shopping list file. Add the changed file to Git's staging area and make a commit with a suitable message.

## Challenge 6: update the remote file

Let's try making a non-conflicting change in the remote repo.

Within Azure DevOps, edit the shopping list file by adding a single new item to the start.

## Challenge 7: pull the changes and push

Let's watch Git handle non-conflicting changes.

Pull the changes from the remote branch and see how the shopping list file now contains both recently-added items. Push the new version of the branch to the remote repository.

## Challenge 8: update the file without pushing

Let's see what could happen if we don't push our changes frequently.

Add a single new item to the end of your shopping list file. Add the changed file to Git's staging area and make a commit with a suitable message.

## Challenge 9: update the remote file

Let's set the stage for a conflict.

Within Azure DevOps, edit the shopping list file by again adding a single new item to the end.

## Challenge 10: pull the changes, resolve the conflict and push

Let's handle the conflict.

Pull the changes from the remote branch and accept both new items at the end of the file in your editor. Add the changed file to Git's staging area, complete the merge using `git commit`, and push the commit to your remote repository.

## Challenge 11: set up reviewers

Let's get some practice following the reviewing protocol.

Find another student to review your work. Within Azure DevOps, add both the student and your instructor as reviewers. They will look at your commits and check whether you have followed the steps correctly. If anything isn't right, they will ask you to carry out certain steps again.

## Challenge 12: complete your pull request

Let's get some practice completing pull requests.

Once the review process has taken place and you have fixed any issues, complete your pull request within Azure DevOps. Back in your local repository, switch to the main branch and pull the merged changes. You should see your final shopping list appear. If you wanted to make a new set of changes, you could then branch off main post-merge.
