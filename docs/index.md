# Introduction
Welcome to Intro to Git! This guide will help you learn how to use Git by installing the appropriate version and pushing your code to the repository. 

## Introduction

Welcome to Intro to Git! This guide will help you learn how to use Git by installing the appropriate version and pushing your code to the repository. Git is a version control system used for software development and GitHub is an internet hosting service that provides access control, bug tracking, task management, and other features for Git projects.

Git is a version control system used for software development
and GitHub is an internet hosting service that provides access control, bug tracking, task management, and other features for Git projects.


## Intended Users

This documentation is targeted towards the following Users:

- Beginner developers who are using Git and are using Git to push their code into the repository.

## Software Requirements

Before proceeding, ensure that you have the following requirements installed:

- [GitHub Account](https://github.com/)
- [Visual Studio Code](https://code.visualstudio.com/download)

## Procedure Overview

The main section of the documentation are summarized below.

- [Git Basics](Gitbasics.md)
- [Pushing Code With Git](Pushingcodewithgit.md)
- [Working with Branches](Workingwithbranches.md)
- [Versions Control](Versioncontrol.md)
- [Trouble Shooting](TroubleShooting.md)

## Notes and Warning Messages

Throughout the documentation, we will use message blocks to inform you of relevant information. Each possible message block, from most important to least important:

!!! warning
    Specifies content that must read before proceeding.

!!! info
    Indicates additional important information and tips.

!!! success
    Indicates what success looks like.

## Installing Git

Here are some examples of how to install Git using MacOS and Windows

### MacOS Users

First, install Homebrew if you havent already installed. Click [here](https://brew.sh/)

Then, run :

```
brew install git 

```

inside yout terminal

### Windows Users

For Windows users, vist the following Web page and download Git: Click [here](https://git-scm.com/download/win)

 and click the 64-bit for Windows setup.

![Git](https://fswdw2023.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Ff05972ad-4749-494e-891b-4b90ad7db9c6%2FUntitled.png?id=89773086-9b32-45fa-a2f1-d2ef523047c8&table=block&spaceId=375f15b7-5ef2-4f2a-883b-20b1eb69aeb4&width=2000&userId=&cache=v2){ width=800px}


1. Click, yes if the following pop-up window pops up
   

![](https://fswdw2023.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fb4ceabe2-55c3-44c8-a75a-42cdf2753de1%2FUntitled.png?id=e3139d20-b792-40cf-a275-bfe3f6590e2a&table=block&spaceId=375f15b7-5ef2-4f2a-883b-20b1eb69aeb4&width=2000&userId=&cache=v2){ width=800px }
**figure**
2. Choose next for all the prompt 

Choose next for all the prompt

![](https://fswdw2023.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F58b6d219-e9c9-4c73-a621-06a3ed47d75b%2FUntitled.png?id=fbe0c991-2207-4513-aca8-4590cb373cc0&table=block&spaceId=375f15b7-5ef2-4f2a-883b-20b1eb69aeb4&width=2000&userId=&cache=v2){ align left }

Click the dropdown button to select Visual Studio Code

4. Otherwize, select the default setting which is Vim

![](https://fswdw2023.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F23f437fe-9d8c-4a00-8e75-a87110f716ab%2FUntitled.png?id=88c27141-16bb-4c97-b282-3538517bfa7d&table=block&spaceId=375f15b7-5ef2-4f2a-883b-20b1eb69aeb4&width=2000&userId=&cache=v2)


Select Git from the command line and also from third party software and keep it that way.
![](https://fswdw2023.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F945a36b4-e12a-4972-80a7-dd5d6565a60c%2FUntitled.png?id=7708d4a2-6d16-471f-8bc4-0a928decb8b1&table=block&spaceId=375f15b7-5ef2-4f2a-883b-20b1eb69aeb4&width=2000&userId=&cache=v2){ align left }

Use bundled OpenSSH and Use the OpenSSL library should be the defaults. Keep it that way.

![](https://fswdw2023.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fc77a8050-eaad-4e3e-825d-05390eb8e530%2FUntitled.png?id=97384c39-5f67-4705-abbf-820350d68c91&table=block&spaceId=375f15b7-5ef2-4f2a-883b-20b1eb69aeb4&width=1600&userId=&cache=v2){ align left }

![](https://fswdw2023.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F226c766c-1ab8-433b-b897-6768fc524bc4%2FUntitled.png?id=be0145e9-858f-4acb-90f5-66b266dcbe24&table=block&spaceId=375f15b7-5ef2-4f2a-883b-20b1eb69aeb4&width=2000&userId=&cache=v2){ align left }

7. Select Checkout Windows-style should be default. Keep it that way.

![](https://fswdw2023.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F624cfe4c-acd0-447b-bfcb-6b3056622593%2FUntitled.png?id=9ceb388d-8620-42fc-8291-9b1f65138a08&table=block&spaceId=375f15b7-5ef2-4f2a-883b-20b1eb69aeb4&width=1600&userId=&cache=v2)

8. Choose the terminal emulator: Leave it at the default which is Use MinTTY

![](https://fswdw2023.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F97261ea9-3c72-49a5-ab36-eef800229967%2FUntitled.png?id=998f0d83-f6b9-4e41-ba04-521d6674ba75&table=block&spaceId=375f15b7-5ef2-4f2a-883b-20b1eb69aeb4&width=1600&userId=&cache=v2)

9.  Select the default git pull option checked

![](https://fswdw2023.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F49f4f6c6-ed97-4a8d-b1c2-27338ed617bb%2FUntitled.png?id=525a0c97-d1ad-4de7-a2b7-05260fd1fd84&table=block&spaceId=375f15b7-5ef2-4f2a-883b-20b1eb69aeb4&width=1600&userId=&cache=v2)

10. Select the default Git Credential Manager Core.

![](https://fswdw2023.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fc703b728-d46c-432a-ae5b-5342e77304df%2FUntitled.png?id=98b99a45-c3fb-439d-afc9-cf2ce1542326&table=block&spaceId=375f15b7-5ef2-4f2a-883b-20b1eb69aeb4&width=1600&userId=&cache=v2)

You should be done installing Git. To check if Git is installed, go to your start menu and type
```
Git bash

```
inside the terminal. You should see the Git icon logo which is shown in the screenshot.

![Image title](https://fswdw2023.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F2c93e41e-b487-4974-b9b6-9a4fc6bdeeb6%2FUntitled.png?id=36304b59-61a7-4cd8-8a05-5524e0f8d473&table=block&spaceId=375f15b7-5ef2-4f2a-883b-20b1eb69aeb4&width=1600&userId=&cache=v2){ align=left }

Inside the terminal type

```
git --version

```

this will display the current version of Git

![Image title](https://fswdw2023.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fbed4eebf-76ea-4652-bebf-ebd69c2a91c8%2FUntitled.png?id=78228689-90c9-440d-81f8-76fa76829fc7&table=block&spaceId=375f15b7-5ef2-4f2a-883b-20b1eb69aeb4&width=830&userId=&cache=v2){ align left }

# Conclusion

By the end of this section, you will have successfully learned the following:

- [x] Learn what is Git about
- [x] How to install Git into your environment

Congratulations! 🎉 Go on to the next section to learn more about how to use Git Basic commands.
Click the link below:

[Git Basics](Gitbasics.md)
