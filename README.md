# TGEOS 419 Geophysics - Data and Notebooks

## What is this?

This is the site where we will keep all of the data files, data analysis scripts, and simulations for the TGEOS 419 course. It's called a _repository_. To learn more about Git and GitHub, check out the [Version Control with Git tutorial](https://swcarpentry.github.io/git-novice/) on Software Carpentry. To learn more about Python, check out [A Whirlwind Tour of Python](https://jakevdp.github.io/WhirlwindTourOfPython/) by Jake Vanderplas.

## Computer skills required

To use Python and Git effectively, you'll need to be able to navigate around your computer's hard disk using the command line. This might seem old-school, but this way of navigating around really helps you keep track of where your files are - essential when we are sharing a set of data and notebooks that we assume are the sam on everyone's computer.

_On a Mac_, you access the command line by running the **Terminal** app.

_On a Windows PC_, you access the command line by running the **Windows PowerShell** app.

The following commands work the same way on both a Mac and a PC.

You can think of your Terminal or PowerShell window as your viewpoint as you navigate around your computer's hard disk (you have a "map" of the hard disk in your Mac **Finder** or Windows **Explorer** windows). In navigation, it's important to know where you are, and to be able to get from place to place. 

To see where you are in the Terminal or PowerShell, type:

	pwd

This stands for "print working directory". The terms "directory" and "folder" are synonyms. You might get something like:

	C:\Users\pasel\Dropbox\Teaching\TGEOS 419\2021_SU

on a PC, or:

	/Users/paselkin/Desktop

on a Mac. Note the differences: PCs use `\` to separate folder names, whereas Macs use `/`; PC folder names start with the hard drive letter, whereas Macs start with a `/`. The sequence of folder names that identify a particular folder is called a _path_ (so, for example, `C:\Users\pasel\Dropbox\Teaching\TGEOS 419\2021_SU` is the path to the folder where I put the work for this quarter's section of TGEOS 419).

To see what files (and other folders) are in the folder that you are in, type:

	ls
This stands for "list".

To change folders, type `cd` and the name of the folder you want to move to. The tilde symbol (`~`) stands for your home directory. So typing:

	cd ~

moves your "viewpoint" to your home folder - the folder that Finder or Explorer starts in when you start your computer fresh. 

Typing:

	cd ..

moves your viewpoint "up" one folder (e.g. from C:\Users\pasel\Dropbox\Teaching\TGEOS 419\2021_SU to C:\Users\pasel\Dropbox\Teaching\TGEOS 419) in your path.

To make a new folder, type:

	mkdir _name_

...where _name_ is the name of the folder you want to create.

## What Python modules are required for this class?

**Note: this will probably change as the quarter goes on.**

This repository requires you to have the standard modules that are installed with Anaconda Python, plus a few extras:

* **WAIT: don't install this yet!**[Fatiando a terra](https://www.fatiando.org/v0.3/install.html): This geophysical modeling package (add-in) for Python is a little tricky to install. You'll need to install a few Python packages and (if you are on a PC) another program to run it. The installation instructions are good, though. 
* [Altair](): This data visualization package makes plotting graphs and maps really easy. If you've used R, it's analogous to ggplot. Really, all you need to install it is 
	`conda install -c conda-forge altair vega_datasets`

## Getting and updating this repository

To copy all of the files on here to your computer, navigate to the folder where you want to put your course materials, and type the command (in Terminal on a Mac or PowerShell on a Windows PC):

	git clone https://github.com/paselkin/tgeos-419-geophysics.git 
 
Note that this creates a new folder called `tgeos-419-geophysics`. 

To update the files in that folder so that they match the latest versions on here, use the command:

	git pull origin main

in your tgeos-419-geophysics folder.

