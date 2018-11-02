# Create an Image!

## Create a Image!
You've been asked by your TL to create a snapshot for your VM.  This tutorial
will walk you through it, have no fear. 

## Point at your project
First set your project to the correct one to use for this tutorial:  
```bash
gcloud config set project gcpquest-2019
```

## Create the Image
Then to create the necessary image you can just copy and paste this command:  

```bash
gcloud compute images create instance-2-image --source-disk instance-2 --source-disk-zone=us-centra
l1-c --force
``` 
This could take 20-30 seconds to execute. Don't worry, it's working. 


## Conclusion
You're all done! Close the window to go back to the game.