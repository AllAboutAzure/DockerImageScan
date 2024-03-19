# DockerImageScan
This repository container workflow code by which you can ensure security for the images by prescanning them before pushing to your private hub

This repo container a sample docker image file with nginx server 

pipelines:
1. To Scan and securely deploy the images to ACR
2. Continous Assurance Scan for the images and send notification to teams channel.

I have used Azure/container-scan for scanning the images which internally uses trivy and dockle.

For more informations: 
- https://github.com/Azure/container-scan
- https://github.com/marketplace/actions/notify-microsoft-teams
