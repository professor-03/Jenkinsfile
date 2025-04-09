# Jenkinsfile
This is the second task as an intern at elevate labs and here i need to deploy a web app with jenkins pipeline.

Here i am listing the steps that i did to make this task a good to go:
- It starts with creating an ec2 instance ans allowing all the traffice.
- jenkins requires installation of jdk before its installation so that was done.
- in the jenkins localhost server various credentials required for the successful operation was entered.
- the one problem that was encountered that the jenkins webhost link was limited to only my personal ip so i had to use ngrok to convert it into global ip (took some reference from copilot)
- then  i wrote the pipeline in the file called "jenkinsfile"
- after the successful linkage of both the jenkins pipeline and github account, i made a small change in the readme file and that was sufficient to trigger the jenkins pipeline. 

