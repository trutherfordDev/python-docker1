# python-docker1
##The Python getting started guide teaches you how to create a containerized Python application using Docker. In this guide, you’ll learn how to:

  Create a sample Python application
  Create a new Dockerfile which contains instructions required to build a Python image
  Build an image and run the newly built image as a container
  Set up volumes and networking
  Orchestrate containers using Compose
  Use containers for development
  Configure a CI/CD pipeline for your application using GitHub Actions
  Deploy your application to the cloud
  After completing the Python getting started modules, you should be able to containerize your own Python application based 
  on the examples and instructions provided in this guide.

Let’s get started!

##Build your Python image

  #Sample application
  The sample application uses the popular Flask framework.

Create a directory on your local machine named python-docker and follow the steps below to activate a Python virtual environment, install Flask as a dependency, and create a Python code file.

##Run your image as a container

#To run an image inside of a container, we use the docker run command. The docker run command requires one parameter which is the name of the image. 
Let’s start our image and make sure it is running correctly. Run the following command in your terminal.

##Use containers for development

#First, we’ll take a look at running a database in a container and how we use volumes and networking to persist our data and allow our application to talk with the database. Then we’ll pull everything together into a Compose file which allows us to setup and run a local development environment with one command.

#Instead of downloading MySQL, installing, configuring, and then running the MySQL database as a service, we can use the Docker Official Image for MySQL and run it in a container.

#Before we run MySQL in a container, we’ll create a couple of volumes that Docker can manage to store our persistent data and configuration. Let’s use the managed volumes feature that Docker provides instead of using bind mounts. 

##Configure CI/CD for your application

#Setting up and using Docker GitHub Actions for building Docker images, and pushing images to Docker Hub. You will complete the following steps:

  * Create a new repository on GitHub.
  * Define the GitHub Actions workflow.
  * Run the workflow.

##Deploy your app

#Now that we have configured a CI/CD pipeline, let’s look at how we can deploy the application. Docker supports deploying containers on Azure ACI and AWS ECS. You can also deploy your application to Kubernetes if you have enabled Kubernetes in Docker Desktop.




