# Getting Started and Installing Dependencies

You're at the first step towards downloading the Rosetta Utility. Find support for the appropriate Operating System below.  

As of now, the utility can only be installed by cloning the GitHub Repository onto a local system. Make sure that your GitHub account is up and running. If you're looking at this on the GitHub page, skip the rest of this paragraph and pick at the 'Installation' section. 
If not, look up 'Shikhar-Srivastava-16/Rosetta' on GitHub, or visit [this link](https://github.com/Shikhar-Srivastava-16/Rosetta "Rosetta's GitHub Page"). You should now be on a Git Repository Page.

To properly run this code, may need to install certain applications on which it is dependent. This fist of these is Python, which can be installed by following the instructions [here](https://www.python.org/downloads/). 
If you want to view code (and even if you just want to run the program), you may want to use of an IDE, or _Integrated Develpment Environment_. I like Visual Studio Code (VSCode) and recommend using it. 
It can be downloaded [here](https://code.visualstudio.com/ "VSCode Install Page"). You would also need these libraries/packages: <br> 
<br>
    numpy<br>
    detectron-2<br>
    pandas<br>
    PyTorch<br>
<br>
This list may change. In case you get an error while running the code, it will tell you if certain modules are used but haven't been installed. Additionally, if you are using vscode, it should tell you if there are any such problems. 
All of them can be installed using pip, python's inbuilt package manager. You can do so with the following command in your terminal, be it Windows' Powershell app, 
CLI or a UNIX/POSIX-based terminal like those in Linux or macOS. 
  <br>

```shell
pip install numpy
pip install detectron-2
# and so on
```

<br>
You will also need to have git installed on your computer to make this work. While it may already be installed, it is a good idea to double-check. If you are unsure as to whether it is installed on your PC or know that it isn't,
you can find easy to follow installation instructions on the Git Project website [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git "Installing Git"). If you already have Git, or any of the aforementioned libraries 
installed but didn't know and followed this process anyway, there is no reason to be worried. Your OS will be able to deal with this automagically without breaking anything! 
<br><br>

# Installation
If you have done everything right, you should be at a GitHub Repostory Page that looks something like this:

![An Image of ](resources\git-page-example.png "")

Hit the *<> Code* button: Green background and white text. You should see a popup that looks something like below 

![An Image of ](resources\code-highlight.png "")

You should be able to copy the URL hghlighted. Save this, you will need it later. 

Here's where the steps diverge depending upon your OS. 

## Windows 10/11

Windows is the standard Operating System that the majority of Laptops and Desktops ship with. This is the simplest cloning process. Go to the Rosetta Git Page and click the '<> code' button. It should give you a dropdown menu.
Click the _Local_ tab if you aren't already on it and then click _HTTPS_. Copy the URL and open Windows PowerShell. You can do this by hitting the Windows Button and typing _PowerShell_ into the search box. This should show you the Windows PowerShell system app.
Click on it to open the app.

The cloning process will start when you type 'git clone' followed by the URL into the command - line interface of Windows PowerShell. If the application prompts you to enter your login details, you should do so. It should not, however, be needed.
Once PowerShell has finished cloning the code here, enter 'cd Rosetta' into the prompt. If you are using VSCode, type the command _code ._ into the terminal to open VSCode. You should now be ready to use the program.

It's a good idea to run _git pull_ every once in a while with VSCode. This keeps your clone of the project up to date with the main project. 
