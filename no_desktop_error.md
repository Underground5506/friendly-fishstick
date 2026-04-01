no_desktop_error
what os are affected 
windows 10 ,11 and most linux based OSes

fixes that I found
in windows :
if it is a blackscreen after you start the pc hold ctrl+alt+del for five seconds 
if it don't work :
If that doesn't work, you need to press the button to turn on the PC and then while Windows is loading, you need to force the PC to shut down several times until it says "Automatic repair in progress".
these are the only fixes that i have for windows 
for linux based os:
go to tty mode by pressing ctrl+alt+F2 or ctrl+alt+fn+f2 and then login with your identifiers like password and name if you added space in the username you need to write them as a - to make it work 
after you will need to do df -h if it shows the biggest drive is full 
do sudo apt autoremove it may free up some space or you can do rm -rf ~/download/* or change download by the folder you want to delete or for a specific file you can do this install ncdu by doing sudo apt install ncdu and opening it by doing ncdu~
