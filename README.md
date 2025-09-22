# Github-learning
My practice repo for learning Git and GitHub basics
<br>
Author-Thanushree Nair
<br>
While learning git and github i am using a dummy website of coffee shop menu (made with html and css)
<br>
1.Install git bash - https://git-scm.com/downloads (I have installed for windows)<br> version 2.51.0.windows.1
2.Basic commands:<br>pwd-current directory<br>ls-all directories in system <br>clear -clears the screen.<br>
3.Git configuration:(which account we will be using to make the changes)<br>
like if we want to use git to make any chnages in git hub which email_id and name do we want to assosciate 
<br>
i)git config --global user.name "My name"  configuration can be global and local since we are using just one github id to make the changes we use global if we want multiple email_ids to make changes in the repo we will use local.
ii)open gitbash (we are in the root folder of our system denoted by "~" )<br>git config --global user.name "ThanushreeNair"(my github profile name)<br>git config --global user.email "thanushreenair@gmail.com"(email_id i have used for my github profile)<br>git config --list(This shows your user name user email and a credential helper (where the username and email i.e our credentials are stored)
4.Open Vscode ,open the dummy folder, check if powershell is able to identify git if not vhage the environmental settings add<br> C:\Program Files\Git\bin
<br>C:\Program Files\Git\cmd<br> to the path in system variables

# Git Basic commands :<br>
1)Clone-Cloning repository to local machine (laptop)<br>
i.e to duplicate a github repository in our local system (personal laptop ,PC)<br>
git clone <project link><br>
project link -got repsoitory click code https there is a link below
