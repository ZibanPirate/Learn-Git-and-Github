# Learn Git and Github
![Learn Git and Github](https://i.imgur.com/bk9Cvuv.png)

# On this lesson you’ll learn how to:

*   Start a new branch.
*   Make changes to a file.
*   Some Git commands that would help you start your first repository. (git log, git diff)


# 0x1.1 : Add a New branch

As you have seen on the lesson [0x0](lessons/0x0-HelloWorld/HelloWorld.md) on how to create a repository,and learned some cool new git commands on lesson [0x1 Chapter 2](lessons/0x1-Git-Basics/Git_Basics_pt1.md), you can now start using them.


If you do remember what we did on the last lesson, now you know how to create a folder, initialize it and create your first file.

After doing that, create a file add it to the staging area and commit it.

### Now Follow these steps : 

-   1 - Do some changings to that file, open the file with any editor you want, and add the following text : 

    ```
    Coding with DzCode, let's start the Algerian Open Source Community Together.
    ```
    ![](https://i.imgur.com/fOtIZFh.png)


-   2 - add your file to the staging area and commit it again :

    ![](https://i.imgur.com/CqHDK5A.png)


-   3 - now type `git log`

    - This command will inform you with all the commit istory, more simpley it will show you the previous commits that you have done each with its own comment that you used.
    
    > We have used this command on the previous chapter but I didn't really expplain it. 

    ![](https://i.imgur.com/lb9Scop.png)

    And as expected, here you can see 2 different commits, with their <b>commit ID</b>, <b>Name of the contributor</b> and <b>the date.</b>

-   4 - Now modify the file again, by adding what ever text you want. After doing that type `git diff`

    - This command will show you all the modifications and changes you did or your team did on that file, by showing what was added, removed or modified. 

        In other words! it will show the differences between your working directory and the staging area.

        ![](https://i.imgur.com/YRvLcg8.png)

        OH! Did just Git gave you the exact text you added ?
        That's right!

<h3><b><i> And that is it 😀 for the git basics part 2</b></i></h3>

***
***
# 0x1 Assignements : 
***
***

- [ ] Create a file called `Dzcode.txt`.
- [ ] Add it to the staging area.
- [ ] Write "Hello DzCode!" in `Dzcode.txt` and save your changes.
- [ ] Show the differences between your _Working Directory_ and _Staging Area_
- [ ] Add `Dzcode.txt` to your _Staging Area_
- [ ] Show the differences between your _Staging Area_ and your _Repository_
- [ ] Commit `Dzcode.txt` to your repoository

Once you have completed these steps, take a screenshot of your command line, with the steps above, 
and upload your screenshot to a new Issue titled `0x1 Assignements - Part 2`

© 2020 - DzCode - Sofiane Hamlaooui - Making the world a better place 🌎 