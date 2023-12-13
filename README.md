# Final_Exam_Akila

Workflow :

1)Setting up EC2 Instance:
I started by creating an EC2 instance, which is like having my own virtual server in the cloud. It's where I plan to run my application.

2)Connecting via SSH:
After the instance was ready, I connected to it using SSH. SSH is like a secure tunnel that lets me interact with my virtual server as if it were my local machine.

3)Installing Docker:
Once connected, I installed Docker on the EC2 instance. Docker is a tool that helps me package my application and its dependencies into containers, making it easier to deploy and run consistently.

4)Creating Git Repository:
Next, I set up a Git repository to manage my project's code. Think of Git as a version control system – it helps me keep track of changes and collaborate with others.

5)Workflow and Secrets:
I established a workflow using GitHub Actions. It's like having a personal assistant for my code, automating tasks like building and deploying. I also added secrets, which are like secure keys or passwords, to make sure sensitive information is kept safe.

6)Adding Dockerfile:
To tell Docker how to build my application, I created a Dockerfile. It's like a recipe that Docker follows to set up the environment and run my app.

7)Adding Website Files:
I added the files for my website to the Git repository. This includes HTML, CSS, and any other files that make up my site.

8)Ready for Hosting:
Now that everything is set up and my code is in the Git repository, my application is ready to be hosted. The Dockerfile and website files will help Docker create a container for my app, making it easy to run on the EC2 instance.


