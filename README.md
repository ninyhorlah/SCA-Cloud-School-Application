##First Step
I created an account with jenkins and i'm able to run my server on port 8080.
On the github repo created, i connect jenkins with my repo by navigating to the settings, webhooks and i input my ipaddress:8080/webhook-github 
I opened the jenkins dashboard, click on new item, enter a project name, click on freestyle project and ok to continue
Check github project and input the github repo url in the space provided 
Click on git under source control management and input the github repo url
Under credentials, select jenkins and input username and password you want to use, click add to continue
Under build triggers, check github hook trigger with GITScm polling
Under build, select execute windows batch command and input what you have in the github repo e.g i used python so i have print('hello world)
click on save

###build
click on build now
After building, click on #1 to view the console output

###Login details
username: ninyhorlah
password: codegirl