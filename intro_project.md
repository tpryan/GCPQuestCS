# Cloud Journey Project Quickstart
![Cloud Journey](title.png "Cloud Journey Tutorial")

<walkthrough-tutorial-url 
url="https://cloud.google.com/compute/docs/gcpquest/intro_project">
 </walkthrough-tutorial-url>

## Introduction

<walkthrough-tutorial-duration duration="10"></walkthrough-tutorial-duration>

Before you can can play the game, you have to make sure that you have a Google
Cloud account ready. If you are already a Google Cloud user, you are strongly
urged to **create a new project** to play the game.   

<walkthrough-project-billing-setup permissions="compute.instances.create"></walkthrough-project-billing-setup>
## Project Setup
Google Cloud Platform organizes resources into projects. This allows you to
collect all the related resources for a single application in one place. &nbsp;
\
&nbsp; \
*You may have already selected a project in a previews tutorial, if it is in the
box below, and it is the one you want to use for this game, then you are all 
set. If, not continue on.* &nbsp; 

## Confirm your account
If this is the first time you have ever logged into Google Cloud, you will have 
to agree to our Terms of Service. If you already have setup an account you can 
just continue to the next step.  
* Check the box that says "I agree to the Google Cloud Platform Terms of 
Service, and the terms of service of any applicable services and APIs."
* Click Agree and Continue

## Activate Free Trial
If you have already setup Billing for your GCP account you can just continue to 
the next step otherwise keep reading. 

This step will require you to input credit card information to Google Cloud. The
purpose of this is to validate your identity, as long as you are using the free 
trial you will not be charged for your usage of the game. 

At the top of the window should be an alert that says "Your free trial is 
waiting: activate now to get $300 credit to explore Google Cloud products."
* Click on "Activate" 

You will be sent to a new page. 
* Check the box that says "I have read and agree to the Google Cloud Platform 
Free Trial Terms of Service."
* Click Agree and Continue

You will be sent to a new page. 
* Choose Individual Account
* Fill in your name and address
* Fill In payment method
* Click Start Free Trial

## Create GCP Project
If this is your first time using GCP, you can use the new project that was 
created for you.  
* Click on [My First Project][spotlight-purview-switcher]
* Please **Copy the ID** of "My First Project." **You will need this 
in the game**.

If you would like to create a new project for the game do the follow below. 
Please note: Limit project names to **30 characters** or less. This is a 
limitation of the engine behind Cloud Journey, and not of GCP.   

* Click on the [Project Selector][spotlight-purview-switcher]
* Click on New Project
* Give your project a name
* Please **Copy the ID** of the project you created.  **You will need this 
in the game**. 


## Install Game Helper Application
* Click on Cloud Shell  <open-cloud-shell-button></open-cloud-shell-button>
* When Cloud Shell starts type:
    `git clone https://github.com/tpryan/GCPQuest-Companion.git`
* Type `cd GCPQuest-Companion`
* Type `make` 
* This make take a few minutes. 
* Once App Engine application is done installing type
* Congrats. Now close and go back to game. 
NOTE ADD CHECK TO GAME HERE. DON'T MAKE THEM CONTINUE AND THEN FAIL

tpryan.tester

## Conclusion

<walkthrough-conclusion-trophy></walkthrough-conclusion-trophy>

You're done!

Go back to the game, and keep questing.


[spotlight-purview-switcher]: walkthrough://spotlight-pointer?spotlightId=purview-switcher