# **<u>Git & GitHub</u>**

**GIt** - FOSS version control system

**Version Control** - The management of changes to documents, computer programs, large web sites, and other collection of information.



<u>Terms</u>

Directory = Folder

CLI = Command line interface

cd = change directory

Repository = Project , or the folder where a project is kept

GitHub = A Website where we store all our git repository

Clone = Bring a repository that is hosted somewhere like GitHub into a folder on your local machine

add = Track your files and changes in Git

commit = Save your files in Git

push = Upload Git commits into a remote repo, like Github

pull = Download changes from remote repo to your local machine, the opposite of push





Step 1 is to SignUp for GitHub - onebitjoy



A <u>repository</u> is usually used to organize a single project. Repositories can contain folders and files, images, videos, spreadsheets, and data sets -- anything your project needs. Often, repositories include a `README` file, a file with information about your project. GitHub makes it easy to add one at the same time you create your new repository. It also offers other common options such as a license file.

# *Day* 1

+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+

## Creating a Repository

1. In the upper-right corner of any page, use the drop-down menu, and select **New repository**.
2. ![Drop-down with option to create a new repository](https://docs.github.com/assets/cb-11427/images/help/repository/repo-create.png)
3. In the **Repository name** box, enter `hello-world`.
4. In the **Description** box, write a short description.
5. Select **Add a README file**.
6. Click **Create repository**.

Ex - 

![image-20211212105330145](C:\Users\Abhishek\AppData\Roaming\Typora\typora-user-images\image-20211212105330145.png)







## Creating a branch

Branching lets you have different versions of a repository at one time.

By default, your repository has one branch named `main` that is considered to be the definitive branch. You can use branches to experiment and make edits before committing them to `main`.

When you create a branch off the `main` branch, you're making a copy, or snapshot, of `main` as it was at that point in time. If someone else made changes to the `main` branch while you were working on your branch, you could pull in those updates.

This diagram shows:

- The `main` branch
- A new branch called `feature`
- The journey that `feature` takes before it's merged into `main`

![branching diagram](https://docs.github.com/assets/cb-24632/images/help/repository/branching.png)

Have you ever saved different versions of a file? Something like:

- `story.txt`
- `story-joe-edit.txt`
- `story-joe-edit-reviewed.txt`

Branches accomplish similar goals in GitHub repositories.

Here at GitHub, our developers, writers, and designers use branches for keeping bug fixes and feature work separate from our `main` (production) branch. When a change is ready, they merge their branch into `main`.



### Create a branch

1. Click the **Code** tab of your `hello-world` repository.
2. Click the drop down at the top of the file list that says **main**.![Branch menu](https://docs.github.com/assets/cb-6253/images/help/branch/branch-selection-dropdown.png)
3. Type a branch name, `readme-edits`, into the text box.
4. Click **Create branch: readme-edits from main**.

![Branch menu](https://docs.github.com/assets/cb-27418/images/help/repository/new-branch.png)

Now you have two branches, `main` and `readme-edits`. Right now, they look exactly the same. Next you'll add changes to the new branch.



## Making and committing changes

When you created a new branch in the previous step, GitHub brought you to the code page for your new `readme-edits` branch, which is a copy of `main`.

You can make and save changes to the files in your repository. On GitHub, saved changes are called commits. Each commit has an associated commit message, which is a description explaining why a particular change was made. Commit messages capture the history of your changes so that other contributors can understand what you’ve done and why.

1. Click the `README.md` file.

2. Click to edit the file.

3. In the editor, write a bit about yourself.

4. In the **Commit changes** box, write a commit message that describes your changes.

5. Click **Commit changes**.

   ![Commit example](https://docs.github.com/assets/cb-75138/images/help/repository/first-commit.png)

These changes will be made only to the README file on your `readme-edits` branch, so now this branch contains content that's different from `main`.



## Opening a pull request

Now that you have changes in a branch off of `main`, you can open a pull request.

Pull requests are the heart of collaboration on GitHub. When you open a pull request, you're proposing your changes and requesting that someone review and pull in your contribution and merge them into their branch. Pull requests show diffs, or differences, of the content from both branches. The changes, additions, and subtractions are shown in different colors.

As soon as you make a commit, you can open a pull request and start a discussion, even before the code is finished.

By using GitHub's `@mention` feature in your pull request message, you can ask for feedback from specific people or teams, whether they're down the hall or 10 time zones away.

You can even open pull requests in your own repository and merge them yourself. It's a great way to learn the GitHub flow before working on larger projects.

1. Click the **Pull requests** tab of your `hello-world` repository.

2. Click **New pull request**

3. In the **Example Comparisons** box, select the branch you made, `readme-edits`, to compare with `main` (the original).

4. Look over your changes in the diffs on the Compare page, make sure they're what you want to submit.

   ![diff example](https://docs.github.com/assets/cb-32983/images/help/repository/diffs.png)

5. Click **Create pull request**.

6. Give your pull request a title and write a brief description of your changes. You can include emojis and drag and drop images and gifs.

7. Click **Create pull request**.

Your collaborators can now review your edits and make suggestions.

## Merging your pull request

In this final step, you will merge your `readme-edits` branch into the `main` branch.

1. Click **Merge pull request** to merge the changes into `main`.
2. Click **Confirm merge**.
3. Go ahead and delete the branch, since its changes have been incorporated, by clicking **Delete branch**.