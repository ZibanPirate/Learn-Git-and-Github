# Installing Git on your Machine | Windows,OSX and Linux
This Tutorial will show you how to install Git depending on the Operation System you are using.

## Windows : 
* Method 1 : 

    ### Downloading : 
    To download git on Windows, follow this link : [Git for Windows](https://git-scm.com/download/win)

    ![Downloading](https://i.imgur.com/p74Q7cp.png)

    ### Installing :
    After downloading Git, you can now install it like any other Windows Executable Software, Just click on that `.exe` file and let the magic happen.

    ![Setup](https://i.imgur.com/d8Guv18.png)

    ## Checking : 
    After the installation, you have to check if everything went perfectly and Git is successfully installed.

    to do that, open a Git CMD (Win + 'Git cmd')
    
    ![ow To](http://167.172.168.122/gv.gif)

    and type : 
    
    ``` 
    git --version
    ```
    and you should have something like this :

    ![Git V](https://i.imgur.com/xFfoRgr.png)


* Method 2 (Recommanded) : 

    With this method, you will just do the 3 steps in 1 step.
    You can do that by downloading an application called [Cmder](https://cmder.net/).
    This app is a Console Emulator for Windows that comes with Git on it's Full Version.

    ![Cmder](https://i.imgur.com/o2drvH3.png)
    
    So, All you have to do is Downloading it, Extracting it to a folder, and just run the `cmder.exe` file.

    ![Extract Folder](https://i.imgur.com/dXJrHQz.png)
    
    ## Checking : 
    To check if Git is installed successfully, type 

    ``` 
    git --version
    ```
    and you should have something like this :

    ![GitV](https://i.imgur.com/QZlMHSU.png)

## Mac Os : 

### Downloading & Installing : 
You can install Git on MacOs by :
![MacOs Installation](https://i.imgur.com/55FTJuM.png)
*   Using [Homebrew](https://brew.sh/) (Recommended), with this command :

    ``` 
    brew install git
    ```
    ![Brew](https://i.imgur.com/QYAULO0.png)

*   Using the Git osx installer that you can download here : [OSX-Installer](https://sourceforge.net/projects/git-osx-installer/)

    ![OSx Installer](https://i.imgur.com/JYOmqKM.png)

### Checking : 
To check if Git is installed successfully, Open a terminal and type 

``` 
git --version
```
and you should have something like this :

![MacOs](https://i.imgur.com/iLZXul9.png)


## Linux :
### Downloading and Installing : 
To install Git on Linux, you will only need 1 command.
Of course this command will depend on your Linux Distribution.

*   Apt-Based (Like: Debian,Ubuntu ...) : 
    ```
    apt install git
    ```
*   Pacman-Based (Like: Arch,Menjaro ...) :
    ```
    pacman -S git
    ```
*   Yum or DNF Based ( Redhat, CentOs...) :
    ```
    dnf install git / yum install git
    ```
![Install](https://i.imgur.com/usD9NCK.png)


### Checking : 

To check if Git is installed successfully, Open a terminal and type 

``` 
git --version
```
and you should have something like this :

![Installa](https://i.imgur.com/90CkOaz.png)

© 2020 - DzCode - Sofiane Hamlaooui - Making the world a better place 🌎 
