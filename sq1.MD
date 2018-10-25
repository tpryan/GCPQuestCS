# Create a VM

## Create a VM!
You've been tasked with creating a very specific VM for GCPQuest.  Don't worry!
Continue with this guide to get it done!

## Point at your project
First set your project to the correct one to use for this tutorial:  
```bash
gcloud config set project gcpquest-2019
```

## Create the VM
Then to create the necessary VM you can just copy and paste this command:  

```bash
gcloud compute instances create instance-2 --zone=us-central1-c --machine-type=custom-8-43008 --boot-disk-size=200GB
``` 
This could take 20-30 seconds to execute. Don't worry, it's working. 


## Conclusion
You're all done! Close the window to go back to the game.