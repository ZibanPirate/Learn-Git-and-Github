# Set up who you are

![Learn Git and Github](https://i.imgur.com/bk9Cvuv.png)

---

---

# On this lesson you’ll learn how to:

- Set up your Git credential.

---

---


## Why does Git need to know who I am?


Once you install git in your machine for the first time Git will ask you for your credentials (username, email).

Git will use this information to label every new commit it, meaning, it will put your name and email on every commit you make on that machine.

## But why?


You might not need to put your name on all commits you made to a project if you are working on the repo alone.

But you need to know which work is yours, and which work is done by others when you work on a repo with a team.

## How can I tell Git who I am?


You can set your name and email associated with your Git commits using the git config command.

The name you set will be visible in any future commits you to make. If you'd like to keep your real name private.

You can change this information anytime with the same command.

Changing the name associated with your Git commits using git config will only affect future commits and will not change the name used for past commits.

1.  Open Terminal.

2.  Set a Git username:

        $ git config --global user.name "Sherlock Holmes"

3.  Confirm that you have set the Git username correctly:

        $ git config --global user.name

    > Sherlock Holmes

4.  Set a Git email:

        $ git config --global user.email "sherlock@holmes.com"

5.  Confirm that you have set the Git username correctly:

        $ git config --global user.email

    > sherlock@holmes.com

## Authenticating to a remote repository


When you save your repository on a remote base you need to use a secure channel for the transfer of code between the repositories. There is two ways you can do that: **HTTPS** or **SSH**.

Both methods have a different way of authenticating. The method of authenticating is determined based on whether you choose an HTTPS or SSH URL when you set up the remote repository.

### HTTPS


When you use HTTPS as the protocol of communication Git will ask you to enter the username and password that you set up for your remote account. Which will be used to authenticate you and allows you to access the remote server.

Keep in mind that you will have to provide these every time you make a communication with the remote server unless you cache them with a credential helper.

### SSH


Another secure and recommended way you can use for your communications is the SSH protocol.

Using SSH requires you to generate an SSH public/private key pair on your local machine and add the public key to your remote account.

Although at first setting up the SSH is a bit of a hassle, you only need to do it once.



---

---

© 2020 - DzCode - Nour Tine - Making the world a better place 🌎
# Set up who you are

![Learn Git and Github](https://i.imgur.com/bk9Cvuv.png)

---

---

# On this lesson you’ll learn how to:

- Set up your Git credential.

---

---


## Why does Git need to know who I am?


Once you install git in your machine for the first time Git will ask you for your credentials (username, email).

Git will use this information to label every new commit it, meaning, it will put your name and email on every commit you make on that machine.

## But why?


You might not need to put your name on all commits you made to a project if you are working on the repo alone.

But you need to know which work is yours, and which work is done by others when you work on a repo with a team.

## How can I tell Git who I am?


You can set your name and email associated with your Git commits using the git config command.

The name you set will be visible in any future commits you to make. If you'd like to keep your real name private.

You can change this information anytime with the same command.

Changing the name associated with your Git commits using git config will only affect future commits and will not change the name used for past commits.

1.  Open Terminal.

2.  Set a Git username:

        $ git config --global user.name "Sherlock Holmes"

3.  Confirm that you have set the Git username correctly:

        $ git config --global user.name

    > Sherlock Holmes

4.  Set a Git email:

        $ git config --global user.email "sherlock@holmes.com"

5.  Confirm that you have set the Git username correctly:

        $ git config --global user.email

    > sherlock@holmes.com

## Authenticating to a remote repository


When you save your repository on a remote base you need to use a secure channel for the transfer of code between the repositories. There is two ways you can do that: **HTTPS** or **SSH**.

Both methods have a different way of authenticating. The method of authenticating is determined based on whether you choose an HTTPS or SSH URL when you set up the remote repository.

### HTTPS


When you use HTTPS as the protocol of communication Git will ask you to enter the username and password that you set up for your remote account. Which will be used to authenticate you and allows you to access the remote server.

Keep in mind that you will have to provide these every time you make a communication with the remote server unless you cache them with a credential helper.

### SSH


Another secure and recommended way you can use for your communications is the SSH protocol.

Using SSH requires you to generate an SSH public/private key pair on your local machine and add the public key to your remote account.

Although at first setting up the SSH is a bit of a hassle, you only need to do it once.



---

---

© 2020 - DzCode - Nour Tine - Making the world a better place 🌎
