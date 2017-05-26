## Setup

**Requirements:** Students must bring a laptop to class with a few specific software packages installed (listed below).

To participate in this class, you will need access to the software described below. In addition, you will need an up-to-date web browser.


# The Bash Shell

Bash is a commonly-used shell that gives you the power to do simple tasks more quickly.

### Windows

1. Download the Git for Windows installer [here]
(https://git-for-windows.github.io/) to use GitBash.
2. Run the installer and follow the steps bellow:
   1. Click on "Next".
   2. Click on "Next".
   3. Click on "Next".
   4. Click on "Next".
   5. Click on "Next".
   6. **Select "Use Git from the Windows Command Prompt" and click on "Next"**. If you forgot to do this programs that you need for the workshop will not work properly. If this happens rerun the installer and select the appropriate option.
   7. Click on "Next". **Keep "Checkout Windows-style, commit Unix-style line endings" selected**.
   8. **Select "Use Windows' default console window" and click on "Next"**.
   9. Click on "Next".
   10. Click on "Finish".

This will provide you with both Git and Bash in the Git Bash program.

### Mac OS X

The default shell in all versions of Mac OS X is bash, so no need to install anything. You access bash from the Terminal (found in `/Applications/Utilities`). You may want to keep Terminal in your dock for this workshop.

### Linux

The default shell is usually Bash, but if your machine is set up differently you can run it by opening a terminal and typing `bash`. There is no need to install anything.


# Git

Git is a version control system that lets you track who made changes to what when and has options for easily updating a shared or public version of your code on [github.com](github.com). You will need a [supported web browser](https://help.github.com/articles/supported-browsers/).

### Windows

Git should be installed on your computer as part of your Bash install (described above).

### Mac OS X

**For OS X 10.9 and higher**, install Git for Mac by downloading and running the most recent installer from [this list](https://sourceforge.net/projects/git-osx-installer/files/). After installing Git, there will not be anything in your `/Applications` folder, as Git is a command line program. For older versions of OS X (10.5-10.8) use the most recent available installer labelled "snow-leopard" available here.

### Linux

If Git is not already available on your machine you can try to install it via your distro's package manager. For Debian/Ubuntu run `sudo apt-get install git` and for Fedora run `sudo yum install git`.


# Text Editor

When you're writing code, it's nice to have a text editor that is optimized for writing code, with features like automatic color-coding of key words. The default text editor on Mac OS X and Linux is usually set to Vim, which is not famous for being intuitive. If you accidentally find yourself stuck in it, try typing the escape key, followed by `:q!` (colon, lower-case 'q', exclamation mark), then hitting Return to return to the shell.

### Windows

nano is a basic editor and the default that instructors use in the workshop. To install it, download the `SWCarepentryInstaller.exe` from [bCourses Files](https://bcourses.berkeley.edu/courses/1403581/files) and double click on the file to run it. **This installer requires an active internet connection.**

Others editors that you can use are [Notepad++](https://notepad-plus-plus.org/) or [Sublime Text](http://www.sublimetext.com/). Be aware that you must add its installation directory to your system path. Please ask your instructor to help you do this.

### Mac OS X

nano is a basic editor and the default that instructors use in the workshop. It should be pre-installed.

Others editors that you can use are [Text Wrangler](http://www.barebones.com/products/textwrangler/) or [Sublime Text](http://www.sublimetext.com/).

### Linux

nano is a basic editor and the default that instructors use in the workshop. It should be pre-installed.

Others editors that you can use are [Gedit](https://wiki.gnome.org/Apps/Gedit), [Kate](https://kate-editor.org/) or [Sublime Text](http://www.sublimetext.com/).


# Python

[Python](https://www.python.org/) is a popular language for scientific computing, and great for general-purpose programming as well. Installing all of its scientific packages individually can be a bit difficult, so we **recommend [Anaconda](https://www.continuum.io/why-anaconda), an all-in-one installer**.

Use Python 3 (note: many examples I use are still in Python 2)

We will teach Python using the IPython notebook, a programming environment that runs in a web browser. For this to work you will need a reasonably up-to-date browser. The current versions of the Chrome, Safari and Firefox browsers are all [supported](http://ipython.org/ipython-doc/2/install/install.html#browser-compatibility) (some older browsers, including Internet Explorer version 9 and below, are not).

### Windows

1. Open [http://continuum.io/downloads](http://continuum.io/downloads) with your web browser.
2. Download the Python 3 installer for Windows.
3. Install Python 3 using all of the defaults for installation *except* make sure to check **Make Anaconda the default Python.**

### Mac OS X

1. Open [http://continuum.io/downloads](http://continuum.io/downloads) with your web browser.
2. Download the Python 3 installer for OS X.
3. Install Python 3 using all of the defaults for installation.


### Linux

1. Open [http://continuum.io/downloads](http://continuum.io/downloads) with your web browser.
2. Download the Python 3 installer for  Linux.
3. Install Python 3 using all of the defaults for installation. (4. Installation requires using the shell. If you aren't comfortable doing the installation yourself stop here and request help at the workshop.)
5. Open a terminal window.
Type

 `bash Anaconda-`

and then press tab. The name of the file you just downloaded should appear.
6. Press enter. You will follow the text-only prompts. When there is a colon at the bottom of the screen press the down arrow to move down through the text. Type yes and press enter to approve the license. Press enter to approve the default location for the files. Type `yes` and press enter to prepend Anaconda to your `PATH` (this makes the Anaconda distribution the default Python).


# Doxygen

You can download the appropriate binaries for your operating system [here](https://www.stack.nl/~dimitri/doxygen/download.html). Note that it may be that this only gives you the GUI version.

For a non-GUI version, you can trying following the build from source directions. You can also try using a package manager. For **Mac OS X** I use [homebrew](https://brew.sh/). I think a good one for **Windows** is [Chocolatey](https://chocolatey.org/). 


# LaTeX

I think [this](https://latex-project.org/ftp.html) should get you all up and running... You can also try a package manager. For **Mac OS X** I personally use [TexShop](http://pages.uoregon.edu/koch/texshop/)

