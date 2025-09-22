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
project link -got repsoitory click code https there is a link below<br>
2.Status-what is the status of our code<br>
git status<br>
note:it shoud be upto date with main<br>
if me modify something in the readme file in vs code git status will show an error because the github readme and vscode readme are not same .<br>
therefore to commit the chagnes made in vscode in the github readme there is a two step process:<br>
1)ADD:adds new or changed files to your git staging area (i.e files are ready to commit ) git add <file-name>
<br> 
2)COMMIT:record of change git commit -m(type the commit name or message) 
<br>
Git status:1)untracked files(files that git doesnt track) 2)modified files(changes made in editor) 3)staged files are added ready for commit) 4)unmodified(no changes)
<br>
flow :<br>
file is either untracked or modified<br>
after add file becomes staged i.e ready to commit<br>
after commit (unmodified) i.e no changes remaining to commit up to date

<br>
Practice in your vscode github learning folder create a new html file use add and commit and then check git status .
<br>
note:you will notice that it mentions that your are 1 commit ahead of origin main means innvs code w ehave commited not on github.Therefore we cannot see the ne cahnges in the github repo .<br>
Push command : local repo (changes made in laptop is pushed onto remote (github))<br>
run git push origin main    -(vs code)
