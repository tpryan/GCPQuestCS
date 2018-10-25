# Create a Snapshot!

## Create a Snapshot!
You've been asked by your TL to create a snapshot for your VM.  This tutorial
will walk you through it, have no fear. 

## Point at your project
First set your project to the correct one to use for this tutorial:  
```bash
gcloud config set project gcpquest-2019
```

## Create the snapshot
Then to create the necessary snapshot you can just copy and paste this command:  

```bash
gcloud compute disks snapshot instance-2 --zone=us-central1-c 
``` 
This could take 20-30 seconds to execute. Don't worry, it's working. 


## Conclusion
You're all done! Close the window to go back to the game.