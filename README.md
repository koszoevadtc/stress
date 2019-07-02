# Assignment: Write documentation for git

Good to see you GitLanders again! It is time to split the work into multiple units so you can work in parallel.
Here you have to cooperate again with your partner to solve mysteries of Gitland.

## Section 1 - Clone the repo and browse it

First of all you need to get familiar with the repository setup and its branches. You can find the following branches in the repo:

* **master**: You can modify it only by pull requests
* **develop**: every new feature branch should starts from here
* **feature/first**: first feature: **person A**
* **feature/second**: second feature: **person B**

In any case you need to do a new feature let's create a new dedicated branch from the **develop** branch.

Clone the repository from your GUI.

> You can use<br/>
> [GitHub Desktop](https://desktop.github.com/) - simple UI or<br />
> [GitKraken](https://www.gitkraken.com/) - a bit more complex UI with more features

## Section 2 - Let's write our documentation

**Person A**:

1. Let's checkout the **feature/first** branch. You will work on it.
2. Your task is to write a simple documentatation DITA format about how to [add](https://git-scm.com/docs/git-add). The basic description is enough.
3. Let's check the state of the repository in your GUI. It will show what are the current changes (tracked or untracked).
4. If you have created your first version add and commit your changes.
5. Push the changes into the origin.

**Person B**:

1. Let's checkout the **feature/second** branch. You will work on it.
2. Your task is to write a simple documentatation in DITA format about how to [push](https://git-scm.com/docs/git-add) to a remote repository. The basic description is enough.
3. Let's check the state of the repository in your GUI. It will show what are the current changes (tracked or untracked).
4. If you have created your first version add and commit your changes.
5. Push the changes into the origin.

## Section 3 - Merge the new features into the develop

1. **Person A**: Navigate to your repository on GitHub.
2. It will notify you that you have unmerged changes in different branches.
3. **Person A** Create a new pull request to merge your changes from **feature/first** -> **develop**.
4. Set as Person B as a reviewer.
5. Change to **Person B** computer. You probably got an email about someone needs your protecting eye.
6. Let's see what are the changes and is there any additional steps need to do before the merge. [If you think it is not enough or something needs to be changed then you can add comments/approval/request-changes to any file in the changeset.](https://help.github.com/en/articles/about-pull-request-reviews)
7. If you decide it's ok and well descripted then you can approve the changes.
8. **Person A**: now you can merge the changes to the develop.
9. Now switch to Person B and do the same process with **feature/second**.

## Section 4 - Create map to your new topics

After you merged both new topics to the develop it's time to create a map for them. But it is a new feature so it deserves its own branch.

1. Create a new branch named **feature/map** from develop. You can create the branch [directly on GitHub](https://help.github.com/en/articles/creating-and-deleting-branches-within-your-repository).
2. Both of you should pull this new branch.
3. Checkout the new branch.
4. Create the new map file. Let's define the name of it together.
5. Put the reference to your topic into the map file. Person A should insert reference only to *git-add* topic.
6. Person B should inert reference only to *git-push* topic.
7. Add and commit your changes.
8. Try to push to the remote. If you were the slower than git will ask you to pull first because of your teammate pushed some changes.
9. Resolve the conflicts.
10. Commit the changes. And push it again.

### Section 5 - New request for the documentation

Add examples to both of the topics which can ease the usage of the commands. What would you do now?
