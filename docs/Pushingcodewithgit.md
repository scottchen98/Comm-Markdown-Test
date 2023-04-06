# Overview
Once you have created your code and you are happy with it, you can push the code to the remote repository

## Learning Outcome
 - How to create a remote repository.
 - How to link your code to the remote repository with your local repository.
 - How to push your code to the remote repository.

## Create a Remote Repository on GitHub
1. Go to your [GitHub Account](https://github.com/).
2. Click the `"+"` button on the top right of your profile picture and click "New Repository".
3. Enter a name for your remote repository.
4. Click public or private, either one is fine.
5. Click the green "Create Repository" button.

!!!tip
    you should name your remote repository with a unique name becuase it will be easier to find the repository on Github if you have multiple projects that is going on. 


## Connect the Local Repository to the Repmote Repository
Type the following commands inside the terminal.

```
git remote add origin https://github.com/<Your_username>/<your_repository_name.git>
git push -u origin main

```
!!! important
    replace `<Your_username>` and `<your_repository_name.git>` name with your username and repository name that you assigned.

`git remote` is a command that will list all the remotes that is available on your Git repository that is running beinhd the scene.

!!! note
    If you run the command `git remote` without the `add origin` follow by the url in your terminal nothing happends. This is because you have not set your remote repository as the remote to your local repository. 

To sent the remote type, enter `git remote add origin` followed by a space and paste in the URL that you see above.


## Sending Your Code to the Remote Repository
Now that you have added a remote repository, you can send your latest code by using `git push`.

`git push` command takes two arguments. 
 1. the first arguments is the name of the remote repository.
 2. the second argument is the branch name of the remote repository.

`origin` is just an alias name or "short name" that refers to the reopsitory name.

!!! note
    You can change `origin` to any name that you want to be.
    ```
    git remote add apple https://github.com/<Your_username>/<your_repository_name.git>
    git push -u apple main

    ```

To push your code to the remote repository to GitHub, run this command.
```
git push -u origin master

```

!!! important
    When you push your code up to the newly added remote repository, using the `-u` will tell Git to save the repository as the default push destination for your current branch. Meaning everytime you push your code to the main or master branch you will only need to run `git push` instead of `git push origin master or main`. 



#Conclusion
Congratulation, you have successfully uploaded your code to the Remote Repository with git.

 - [x] learned what is remote repository is.
 - [x] Learned how to use `git push` and pushed to the remote repository.
 - [ ] 


