prerequisites:
- installed Jenkins
- installed docker
- installed Java and Maven

running the project:
1. go to Jenkins Dashboard --> new item and choose pipeline.
2. copy the content of the Jenkins file from the Github repo into the script section and save the changes.
3. copy the Dockerfile from the GitHub repo to the project source code folder.
4. run the Jenkins pipeline.
5. can find the docker image saved on the collect artifacts of the Jenkins job.

*Note: the commands used on the Jenkins file script are for windows, if used in Linux os need to change the 'bat' command to 'sh'.
