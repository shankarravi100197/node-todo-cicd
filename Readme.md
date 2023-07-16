we are going to set up a pipeline for a Django appplication

#Configuring Jenkins

1. Create a new item and choose aa free-style project
2. Provide Project description in the General setting
3. Go to Source code management to configure Github to Jenkins
4. Provide the GitHub URL where the code exists
5. Use secret text option to provide credentials to Jenkins
6. Go to Build Steps and choose the execute shell build option
7. Now you have already written the docker file to containerize the application
8. Provide the docker commands to build an image from the docker file and build the container.
9. Click on build now to execute project
10. Navigate to URL now.

    #Initiallising Webhook
1. Automate the build process with integration of webhook in Github
2. Go to code repository and navigate to the setting, provide the details in webhook
3. Go to jenkins and in Build Triggers and select Github hook trigger
4. Make changes in Github file for project and commit it
5. Monitor the build in jenkins that must have triggered automatically
6. Navigate to URL now. 
