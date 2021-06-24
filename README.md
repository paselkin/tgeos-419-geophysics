## TGEOS 419 Geophysics - Data and Notebooks

# What is this?

This is the site where we will keep all of the data files, data analysis scripts, and simulations for the TGEOS 419 course. It's called a _repository_. To learn more about Git and GitHub, check out the [Version Control with Git tutorial](https://swcarpentry.github.io/git-novice/) on Software Carpentry. To learn more about Python, check out [A Whirlwind Tour of Python](https://jakevdp.github.io/WhirlwindTourOfPython/) by Jake Vanderplas.

# Getting this repository

To copy all of the files on here to your computer, use the command (in Terminal on a Mac or PowerShell on a Windows PC):

	`git clone https://github.com/paselkin/tgeos-419-geophysics.git _folder-path_/tgeos-419-geophysics`

Where _folder-path_ is the path to the folder where you want to save the data for this class (like ~/Desktop or C:\Users\pasel\Dropbox\Teaching\TGEOS 419\2021_SU)
To update the files so that they match the latest versions on here, use the command:

	`git pull origin master`

in the tgeos-419-geophysics folder.

# What Python modules are required?

This tutorial requires you to have the standard modules that are installed with Anaconda Python, plus a few extras:

* [Fatiando a terra](https://www.fatiando.org/v0.3/install.html): This geophysical modeling package (add-in) for Python is a little tricky to install. You'll need to install a few Python packages and (if you are on a PC) another program to run it. The installation instructions are good, though.
* [Altair](): This data visualization package makes plotting graphs and maps really easy. If you've used R, it's analogous to ggplot. Really, all you need to install it is 
	`conda install -c conda-forge altair vega_datasets`
