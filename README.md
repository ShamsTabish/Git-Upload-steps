
############################### First Time Setup ###############################

Goto github.com

sign up 

sign in

create a new repository

give it a name, description click create

------------------------------------------------------------------------------

Under Your Repository on github locate HTTPS | SSH option 
Click on HTTPS 

Copy the URL given on the right hand side (it looks something like https://github.com/yourIdOnGithub/repositoryName.git)




_______________________________________________________________________________

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ On Your Machine ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Download and install git from https://git-scm.com/download/win

During Installation it will ask for Adjusting Path environment select "Use Git From Windows Command Prompt"
  and select the default option (already selected one's) for all the other options that the installation vizard ask for.
------------------------------------------------------------------------------------------

go to command prompt (open a new command window / cmd)

go to your project folder (using cd command on console)

type following command and press enter
git init

type following command and press enter
git add -A

type following command and press enter
git commit -m "Saving the project for 1st time on git"



type following command and press enter(https://github.com/ShamsTabish/test.git is the URL copied form the above step on github.com) 
git remote add origin https://github.com/ShamsTabish/test.git

type following command and press enter
git push -u origin master

It will prompt you for user name -> enter your user name created on GITHUB
It will then promt you for passwrod -> Enter your password for GITHUB account




