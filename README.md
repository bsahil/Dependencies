# Ubuntu
Musthave in every Linux Installation.
1. Updates and Upgrades new installation
2. Installs
	* Git
	* snapd
	* Visual Studio Code
	* build-essential package
	* clipit(A Software to improve clipboard capabilities)
	* autojump
	* nightlight, gnome, gnome-tweak-tool, dash to dock and dconf-editor


## Permissions:

1 – can execute  
2 – can write  
4 – can read  

The octal number is the sum of those free permissions, i.e.  
3 (1+2) – can execute and write  
6 (2+4) – can write and read  

Position of the digit in value:  
1 – what owner can  
2 – what users in the file group(class) can  
3 – what users not in the file group(class) can  

Examples:  
chmod 600 file – owner can read and write  
chmod 700 file – owner can read, write and execute  
chmod 666 file – all can read and write  
chmod 777 file – all can read, write and execute  
	
## To execute follow the steps

1. autojump/jump to the folder where you have downloaded the file.
2. Type _sudo chmod 700 dependencies.sh_ in terminal.
3. run the command _./dependencies.sh_.

###Updates:
1. [Jan'19 2109] Added _-y_ tag to update and upgrade so as to pass all _yes/no_ permissions.

#### Disable password prompts and go take a shower while this file sets your ubuntu up. :p


