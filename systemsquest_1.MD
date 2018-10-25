First set your project:  
`gcloud config set project gcpquest-2019`

Then to create the necessary VM you can just copy and paste this command:  
`gcloud compute instances create instance-2 --zone=us-central1-c --machine-type=custom-8-43008  --boot-disk-size=200GB` 