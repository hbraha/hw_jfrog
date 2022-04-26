prerequisites:
install Jenkins
installed docker
installed Java and Maven

running the project:
go to Jenkins Dashboard --> new item and choose pipeline.
copy the content of the Jenkins file from the Github repo into the script section and save the changes.
copy the Dockerfile from the GitHub repo to the project source code folder.
run the Jenkins pipeline.
can find the docker image saved on the collect artifacts of the Jenkins job.

*Note: the commands used on the Jenkins file script are for windows, if used in Linux os need to change the 'bat' command to 'sh'.
