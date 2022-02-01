# Logging into ieng6
## get VSCode
first you need to download vscode and download the version for your specific machine (mac, windows, linux.)

go to this website and click the right button

[vscode link](https://code.visualstudio.com/download)

![Image](pictures/first.png)

## open terminal in VSCode
now you'll want to get access to the terminal in VSCode. It's view > terminal, as seen in the picture.

![Image](pictures/second.png)

## try some commands
try out some of the cool commands linux has to offer.

![Image](Users/joey/Documents/aCommands.png)

## ssh into your account
use the ssh command and post your account@ieng6.ucsd.edu afterwards to log into your account. Then type in your password.

![Image](pictures/third.png)

## set up ssh-keys
ssh keys are helpful in that they make it so you don't have to type in a password everytime you want to do a command from your computer to ieng6. Follow the instructions at this link in the admin powershell. open it with windows+x menu.
[Link](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_keymanagement#user-key-generation)

powershell:
![Image](pictures/fifth.png)

## scp a file
you can secure copypaste a file from your computer to the ieng6 server by using the scp command. Take any file and do so. You should not be signed in while doing so. Since you already set up your ssh key the process is very easy.

![Image](pictures/fourth.png)

## Even cooler running
now scp a .java file. You can use semicolons to type multiple commands into the commandline at once, speeding up your remote coding. try compiling and running your scp'd program in one submission.

![Image](pictures/sixth.png)