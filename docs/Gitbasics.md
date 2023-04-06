## Create a local repository

Follow these steps below to create a local repository:

**1. Create a folder for our repository**

In the terminal, navigate to a directory of your choice (e.g., your desktop). In your terminal, create the folder by running the following:

```shellscript
mkdir my_new_directory
```

This command creates a new directory named `my_new_directory`.

**2. Navigate into the new folder**

```shellscript
cd my_new_directory
```

This command moves into the newly created directory. Your terminal should display `my_new_directory`, indicating that you are now inside the new folder. Open the folder in VS Code.

## Initialize a Git Repository with `git init`

Now that we're **in the directory** where we want Git to watch for changes (adding, removing, and editing files), we next need to *initialize* this directory as a Git repo.

In the terminal type `git init`. It should look something like this:

```shellscript
$ git init
Initialized empty Git repository in C:Users/yourUserName/my_new_directory/.git/
```

The message indicates that Git is now tracking the new directory, and it has created a hidden subfolder called `.git`. This subfolder contains crucial data, such as the commit history. If you really mess things up and want to start from scratch with Git, you can delete the `.git` folder and all its contents using `rm -rf .git` command. This will restore the directory to a regular folder that's no longer linked to Git.

!!! warning

    Make sure to be aware of which folder you are currently in within your terminal. It is important to avoid accidentally running the init command in your home directory or desktop. Only type `git init` within the specific directory that you want `git` to track. Forgetting to do so may cause Git to track every file on your computer, which is not desired.

## Check the Status of a Repository with `git status`

```shellscript
git status
```

This command tells us about the status of a repository and the staging area. It displays which files that aren't being tracked by Git and which changes have or haven't been staged.

Since there are no files that are being added yet, we'll see:

```text
On branch main (or maybe it'll say master)

No commits yet

nothing to commit (create/copy files and use "git add" to track)
```

!!! note

    It is important to note that `main` and `master` are both names for the core branch of a repository. While a repository can have many branches, it will always have only one primary branch. Previously, this branch was typically called `master`, but going forward it will be called `main`. As you work with both new and old repositories, you may encounter both names.

Let's create and add content to a new README.md file in the `my_new_directory` directory by following the steps below:

**1. Create a README.md file**

```shellscript
touch README.md
```

This command creates a new file named `README.md`. Alternatively, you can create a new README.md file in VS Code by choosing `File -> New File`.

**2. Add content to the README.md file**

A README.md file describes the project. To add content to the README.md file, run the following command:

```shellscript
echo "This is my readme file" >> README.md
```

This command adds the content `"This is my readme file"` to the README.md file. Alternatively, you can directly type in content for the README.md file in VS Code. If you have the README.md file open in VS Code, the new text will appear.

Now if we type `git status` again, git will show us what our current repository looks like and what changes it sees.

```text
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

  README.md

nothing added to commit but untracked files present (use `git add` to track)
```

Git acknowledges the existence of the file `README.md`, but it is not currently monitoring it. Git is not interacting with the file, nor is the file interacting with Git...at least not yet.

!!!tip
    `git status` is useful whenever you want to check the status of your Git repository.

## Keep track of File Changes with `git add`

The file in our repository is not being tracked by Git yet. To ensure that the file is considered part of our project, we need to inform Git about all the files we want it to keep track of by typing:

```text
git add README.md
```

This command adds our new `README.md` file to the repository. To check the status of our repository, type `git status`.

```text
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

new file:   README.md
```

The README.md file has now been staged and Git is ready to keep track of all the changes in the README.md file.

!!!tip
    You can also use the `git add .` command to add *all* the files that have been changed since the last commit.

## Create a Commit and Apply a Commit Message with `git commit`

Now that we have staged the README.md file, let's create our first commit by typing:

```shellscript
git commit -m "initial commit"
```

This command will capture and create a "snapshot" of the changes in the commit. Whenever we make a commit, we use the `-m` flag to specify a commit message, in this case `"initial commit"`.

!!!important
    Anytime we make a commit, we should provide a commit message using the `-m` flag.

```text
$ git commit -m "initial commit"

[main (root-commit) e55477d] initial commit
 1 file changed, 1 insertions(+), 0 deletions(-)
 create mode 100644 README.md
```

Git has created a new version of our repository. In the Terminal, we see that there was one file changed which was our README.md file with one insertion which was the `"This is my readme file"` content we added to earlier.

If we run the `git status` command now, we should see that it is at a "clean state".

```text
$ git status
On branch main
nothing to commit, working tree clean
```

We see that our `main` (or maybe `master` on yours) branch has nothing to commit and is up to date.

## Conclusion

By the end of this section, you will have successfully learned the following:

- [x] Make a new Git repository out of a directory using `git init`
- [x] Check the status of our repo using `git status`
- [x] Track and stage files that have been changed using `git add <filename or path>`
- [x] Commit (save) changes with an explanatory message using `git commit -m "Any message"`

Congratulations! 🎉 Go on to the next section to learn more about how to push code with Git.
Click on the link below:

[Pushing Code With Git](Pushingcodewithgit.md)
