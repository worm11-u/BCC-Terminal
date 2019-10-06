# BCC-Terminal
how to push projects in Windows with terminal to Github

First i need fingure out what Terminal is, where i can start. 
And then i found how to access Terminal in Windows below:
press "Win+R"，type "cmd" in the box
type command lines on the terminal black background window
but most command lines didn't work in Windows system, which was impossible to push projects to Github. 

Google "how to push projects in Windows with terminal to Github", found the solution below:

create account "worm11-u"
https://github.com/

Install git tool "Git for Windows"：
https://git-for-windows.github.io/

right key click the folder i tried to upload to Github
left key click to choose "Git Bash Here"
black git tool terminal window "MINGW64" popuped

In Github, copy "BCC-Terminal" url

In this "MINGW64" window:
git clone https://github.com/worm11-u/BCC-Terminal.git

In my local folder:
move "Countertop Display" folder into "BCC-Terminal" folder,which automatic created in my current folder on my laptop by git tool "Git for Windows"  

In "MINGW64" window:
cd BCC-Terminal

type command lines below one by one to add,commit and push all files in the folder:
git add .
git commit -m "*"
git push -u origin master

but failed
Github need identify this user and email address

*run
git config --global user.email "jfng11@gmail.com"
git config --global user.name "worm11-u"

identified
type command lines again
failed again
screen showed:
*GitHub's file size limit of 100.00 MB

reduce files size
type command lines again
done
https://github.com/worm11-u/BCC-Terminal
