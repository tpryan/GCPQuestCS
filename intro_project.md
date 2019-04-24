# Cloud Journey Project Quickstart
![Cloud Journey](title.png "Cloud Journey Tutorial")

<walkthrough-tutorial-url 
url="https://cloud.google.com/compute/docs/gcpquest/intro_project">
 </walkthrough-tutorial-url>

## Introduction

<walkthrough-tutorial-duration duration="10"></walkthrough-tutorial-duration>

Before you can can play the game, you have to make sure that you have a Google
Cloud account ready and a project to run the game. You may have already 
selected a project in a previews tutorial, if it is in the box below, and it is the one you want to use for this game, then you are all set. If, not continue 
on.  
\
&nbsp; \
**If you are already a Google Cloud user, you are strongly
urged to create a new project to play the game.**   
\
&nbsp; \
If you would like to create a new project for the game do the follow below. 
Please note: Limit project names to **30 characters** or less. This is a 
limitation of the engine behind Cloud Journey, and not of GCP.   
\
&nbsp; \
<walkthrough-project-billing-setup></walkthrough-project-billing-setup>

## Record Project ID
**Please *Copy the ID* of the project you created. You will need this 
in the game**  
\
&nbsp; \
You can see it by clicking the [Project Selector][spotlight-purview-switcher]


## Install Game Helper Application
The game uses an App Engine application to make various progress checks. You
must install this to progress in the game.  


Open Cloud Shell by clicking
<walkthrough-cloud-shell-icon></walkthrough-cloud-shell-icon> in the navigation
bar at the top of the console.

&nbsp;

A Cloud Shell session opens inside a new frame at the bottom of the console and displays a command-line prompt. It can take a few seconds for the shell session 
to be initialized.
\
&nbsp; \
When Cloud Shell is ready type:
```bash
git clone https://github.com/tpryan/GCPQuest-Companion.git
```

Then type the following:
```bash
cd GCPQuest-Companion && make
```
Once App Engine application is installed you should see a success message.
&nbsp;

## Conclusion

<walkthrough-conclusion-trophy></walkthrough-conclusion-trophy>

You're done!

Go back to the game, and keep questing.


[spotlight-purview-switcher]: walkthrough://spotlight-pointer?spotlightId=purview-switcher