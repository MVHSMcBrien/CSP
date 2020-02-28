# Python Notes  
Here are some notes for getting started if you feel like you are lost.  
___
## The command line (Powershell)
there are many types of command line environments  I am suggesting you use <b>Powershell</b> in Windows.

When you start you probably will find the following  
`H:\`

This means you are in the H: drive which is a network drive.  I want you to work with the computers hard drive which is known as C:\ by default.

enter ` C:`  to change the drive

Now you can move around the directories by using the following command
`cd Users`  this will bring you to the Users directory (folder)

Next Try hitting `ls`

ls tells the computer to *list* all items in the directory.  Your name will be in there so move to that directory see below example

`cd homersimpson`

**task: Use cd to move to your documents folder**

Your screen will probably look something like This
`C:\Users\homersimpson\Documents>`

Other useful command line operations include
* <code>mv name_of_file new_name_of_file</code> renames the file or moves the file
*  `rm` removes the file

## Python Installs

You will need the matplotlib and pyplot libraries you will use the `pip` command to download and install them.

`py -3 -m pip install matplotlib --trusted-host files.pythonhosted.org --user`

`py -3 -m pip install numpy --trusted-host files.pythonhosted.org --user`

## Using Python  

`py  -3`  
Gets you to the command line environment

`py -3 yourfile.py`  
runs the yourfile.py python file

## Zip Files

if you see a file with the extension *.zip* this you need to *unzip* before you can use this file.  Most  of the source I give you is in a zipped file.
*Right Click on the zipped file > Unzip*

**This should be enough info to get you going with python**
___
**Practice makes perfect. Practice making simple python files and running them from the command line.  Remove them using rm and do something else.  Once you feel comfortable move on to an assignment.**
