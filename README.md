# Offline Install Of Python Modules

Sometimes you can't get to the Internet but you still want to automate things. The batch scripts in this repository install specific modules that are needed to run the necessary modules. 

Many modules, such as Paramiko, have multiple pre-requisites. Some of those pre-requisites have pre-requisites. You still have to download the modules, but with this script you can take the modules and group them together as the script installer specifies and then just run the cmd file to install the modules.

You're smart, you can figure out the minor details. My goal here was to save somebody the time of reading through all the pre-requisites for modules that I used. 

Sure, you can use virtualenv. But whats the fun in that ;(
