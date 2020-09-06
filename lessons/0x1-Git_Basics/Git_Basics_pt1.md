# Learn Git and Github
![Learn Git and Github](https://i.imgur.com/bk9Cvuv.png)

---
---

# On this lesson you’ll learn how to:

*   Create an issue.
*   Some Git commands that would help you start your first repository. (git init, git status, git commit and git log )

---
---

# 0x1.1 : Create an issue

For a majority of your assignments you will create issues on GitHub.

So, the first step is to learn how create one, to do that you can follow the steps below :

Go to the repository you want to create an issue on it.

-   1 ![](https://i.imgur.com/IGTpRPX.png) ![](https://i.imgur.com/kDU7m5T.png)

-   2 - Once you have created a new issue, you will be greeted by the screen below. Here you will provide : 

    - A title for your issue
    - A body for your issue to write a response or upload a screenshot
    - A submission button

    ![](https://i.imgur.com/mM7NMdn.png)
-   3 - Your issue is created sucessfully.
    ![](https://i.imgur.com/yKhCA16.png)

<h3><b>Congatulations you have created an issue.</b></h3>

---
---

# 0x1.2 : Git Basics pt. 1

As you have seen on the lesson [0x0](lessons/0x0-HelloWorld/HelloWorld.md) on how to create a repository.

Today you will learn how to initialize and use some basic Git commands on a repository.

To do that, Open a terminal and follow these steps : 

-   1 - Make a directory by the name of your repository. 
    ```
    mkdir MyNewRepository
    ```

    2 - enter the folder and initialize it.
    ```
    git init
    ```
    >   so you can use this command to initialize your repository.
    ![](https://i.imgur.com/ex1ku4J.png)

    3 - Create a file named `Readme.md`
    ```
    touch Readme.md
    ```
    4 - get the status of your repository
    ```
    git status
    ```
    > As you can see here, git status will give you the status of your commits, tracked, and untracked files
    -   Commit = a changed file that you sent to the staging area.
    -   Tracked = a file that is waiting for commits.
    -   Untracked = a changed file that wasn't sent to the staging area yet.

    5 - Add the `Readme.md` file to the staging area.
    ```
    git add Readme.md
    ```
    6 - Commit that staged file, and add a comment to it.
    ```
    git commit -m "Adding Readme File"
    ```
    -   -m "The comment you want to give to that comment".
        -   Do a git status to check if the commit was done.
        ![](https://i.imgur.com/Dl3OC0Z.png)

    7 - Use git log, to get the logs and check whaat was changed
    ```
    git log
    ```
    ![](https://i.imgur.com/XUVOe74.png)

<h3><b><i> And that is it 😀 for the git basics part 1</b></i></h3>

***
***
# 0x1 Assignements : 
***
***
-   1 - Create an issue :
    
    Create an issue on the repository created on your Github Classroom,its body :

    ``` 
    Let's make Algeria great again and start that by learning Open Source.
    ```

-   2 - Share a screenshot of your work ( on the same issue):
    - [ ] Create a directory using the command `mkdir`
    - [ ] In the directory you created initialize Git using `git init`
    - [ ] Create a README.md file in your directory using the `touch` command
    - [ ] Make sure README.md is in your _Working Directory_ by checking your status with `git status`
    - [ ] Move README.md from the _Working Directory_ to the _Staging Area_ by using `git add`
    - [ ] Make sure README.md is in your _Staging Area_ by checking your status with `git status`
    - [ ] Commit README.md to your repository using `git commit`
    - [ ] Make sure your _Working Directory_ and _Staging Area_ are clean with `git status`
    - [ ] Make sure your commit has been logged into your repository by using `git log`

    Once you have completed these steps, take a screenshot of your command line, with the steps above, and upload your screenshot to a new Issue titled `0x1 Assignements - Part 1`

© 2020 - DzCode - Sofiane Hamlaooui - Making the world a better place 🌎 

