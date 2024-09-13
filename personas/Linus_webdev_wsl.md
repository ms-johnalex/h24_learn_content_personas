# Web Dev Persona

## Summary

“Linus” is a developer building web apps using NodeJS on a Windows device in a Linux environment with WSL.

## Bio

Linus is a developer who wants to create web apps using Node.js.

Linus wants to use a Linux environment because he knows that Linux often provides better performance for Node.js due to it’s efficient handling of system resources and lower overhead.

Linus also knows that many Node.js modules and dependencies are developed and tested primarily on Linux, ensuring better compatibility and fewer issues during development.

Linus wants to use a Docker container in his workflow because containers help him to ensure his apps run the same way in development, testing, and production environments, as well as simplifying dependency management by packaging all of the necessary libraries, tools, and dependencies required to run his app inside the container. This makes it easier for hime to manage and update dependencies without affecting the host operating system on his device or other projects that he is working on. Linus knows Linux is a preferred environment for developing in Docker containers, since Docker was originally developed for Linux and runs natively on Linux with fewer compatibility issues.

Linus also wants to deploy the web apps that he creates to a production server and he knows that most production servers run on Linux. Developing in a Linux environment ensures that the development and production environments that he is using are consistent, reducing the chances of environment-specific bugs. Deployment scripts and automation tools are often designed for Linux environments as well, making the dev process smoother and more reliable.

Linus works at a company that utilizes M365 products, hosting meetings on Microsoft Teams, email and calendars on Microsoft Outlook, and utilizing tools like Word, Excel, and PowerPoint, so Linus wants his primary work device to be a Windows machine, since it does a better job supporting those productivity tools.

Linus likes to use Visual Studio Code as his primary source-code editing tool and recently learned that Windows Subsystem for Linux (WSL) enables working in a Linux environment from a Windows device without all of the issues of dual-booting or the performance overhead of using a VM. However, Linus is new to using Windows Subsystem for Linux and doesn’t yet understand it very well.

## Scenarios

1. Install a Linux distribution and configure the file system with WSL.

    The first thing that Linus needs to learn is how to use WSL to install and configure different Linux distributions. He wants to start by installing Ubuntu, but he doesn't yet understand how file storage works when using WSL and whether he will need to spend additional time on configuration settings in order to use the multiple drives that he has mounted on his machine, as well as the USB drive where he has files stored. Linus has heard that there are two versions of WSL, WSL 1 and WSL 2, but doesn't know what the difference is or which would be better for him to use.

2. Set up a WSL development environment that uses a Docker container.

    The next thing that Linus needs to learn is how to work with the Visual Studio Code (VS Code) editor that he has running on his Windows device in the Ubuntu Linux environment that he just installed. He isn't sure if there are extensions that he needs to install in VS Code or settings that he will need to adjust. Additionally, Linus needs to learn how to build and set up a Docker container that runs in the Linux environment where he can store his web app projects code and dependencies.

3. Configure security settings to enable safe collaboration in an Enterprise business environment.

    Linus is also concerned about whether he will have trouble collaborating on these web apps with the other developers at his company because he is using WSL. The company uses Microsoft Defender for Endpoint with Intune and may be blocking access to Linux distributions installed with WSL for developers that don't have Admin-level permissions like Linus does. He needs to learn how to set the correct permissions for his company's enterprise environment that balance security with enabling more junior-level devs to collaborate with him and contribute to the apps. Some of these junior developers also work remotely, so Linus anticipates that he will need to manage some advanced networking controls related to the VPNs that they use for collaboration as well.

## Advanced scenarios

1. Use Azure Kubernetes for container orchestration to automate the deployment, scaling, and management of the containerized Node.js web apps that the development team has built.

    Linus anticipates his company's web apps to be very popular and have high traffic concerns during sales and other events. He needs to consider how to use Kubernetes to automatically scale the multiple Node.js apps owned by his team up or down based on demand to ensure optimal performance and resource utilization. He also must consider load balancing to distribute network traffic across multiple instances of the web applications to prevent a single instance from becoming a bottleneck. He wants kubernetes to automatically restart or replace failed containers to ensure that the web apps remain available if something happens (Self-healing). He also wants to enable rolling updates and rollbacks so that the team can deploy updates to the web apps without downtime, and if something goes wrong, can easily roll back to a previous version. Lastly, to help with configuration management so that senstive information like API keys and passwords are handled properly and remain secure.

2. Develop an AI workflow locally with Tensorflow.

    Linus wants his team and company to be on the cutting edge by incorporating AI features into their web apps. Linus wants the team to build and deploy their own machine learning models using the company's private customer data, but also understands that most of the developers on his team are new to working with AI. He chooses to use Tensorflow because of the multipe layers of abstraction it provides, allowing his team to choose the right one for their needs as beginners. Linus needs to know how to install TensorFlow within the Linux environment on his Windows machine. How to transfer his company's private customer data to the Linux environment so that it can be used to train the ML model with TensorFlow. Once the model is trained, he needs to know how to know the proper format for saving it so that it can be easily loaded and used later for predictions. He needs to know how to integrate the trained TensorFlow model into his Node.js web app, including loading the saved model and using it to make predictions based on input from the web app user. Lastly, he needs to know how to deploy the updated web app with his trained TensorFlow model so that it is hosted on the Azure cloud inside his web app container so that it can be accessed by the users of his web apps.