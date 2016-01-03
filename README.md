#waste

##waste – { Command Line Waste Basket Utility }
**waste** is a simple shell application that makes recovery of deleted items possible,
provided they have been deleted from the command line using this very same utility

###{ Program Options }
Usage: **waste [ -h | -E | -s | -w ] ||**  
&emsp;&emsp;&emsp;&ensp;**waste -h : shows the usage of this command and exits (This message)**  
&emsp;&emsp;&emsp;&ensp;**waste -E : empty waste (removes and recreates the $HOME/.waste directory)**  
&emsp;&emsp;&emsp;&ensp;**waste -s : show contents of the $HOME/.waste directory**  
&emsp;&emsp;&emsp;&ensp;**waste -w : show space on disk of the $HOME/.waste directory**  
&emsp;&emsp;&emsp;&ensp;**directory || filename = directory or file to move to $HOME/.waste**  
&emsp;&emsp;&emsp;&ensp;**(A timestamp suffix will be used if necessary)**  

###{ Program Setup }
This program is going to be installed by default in your **$HOME/bin** directory. If you have not set your **$HOME/bin** in the **$PATH**, see [this](http://istos.xyz/linux/include-homebin-in-any-desktop-environment/ "Include $HOME/bin in any Desktop Environment") or [this snippet](http://istos.xyz/linux/include-homebin-in-the-path-for-bash-shell "Setup your $HOME/bin in the $PATH") for details.

Download the tarball containing the waste utility from the link towards the bottom and do the following:

Move the downloaded tar file into your home directory

Expand the tar file in a terminal by issuing: tar xf waste_<version>.tar

Invoke the program from the terminal, running waste to see a message for the program usage
