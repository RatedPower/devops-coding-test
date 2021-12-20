# DevOps challenge

With this challenge we want to evaluate your skills as a DevOps expert. The solution should:
- Meet every requirement detailed in the Main objectives.
- Demonstrate your ability to produce high quality and well documented code.

To achieve these goals, you can use all the tools and libraries you want. Finally, there is one optional goal which, if achieved, will be positively considered.


## Required tools
To implement a solution, you should be familiar with these tools:

1. Any Linux environment
2. [Java 11](https://adoptopenjdk.net/)
3. [Docker](https://docs.docker.com/engine/install/)
## Objectives
The main goal is to create and run a Docker container with this Spring Boot application. You only have to implement the code in the three files that are in the scripts folder.
### Main
1. Implement the **build.sh** script, this script should compile the Spring Boot application and create the Docker image.
2. Implement the **Dockerfile**, add the necessary commands to assemble the image. This image should include the previously compiled code, and it should also execute it.
3. Implement the **run.sh** script, this script should run the Docker container.
### Optional
1. Create a new script called "deploy.sh" which uploads the previously created Docker image to an AWS Elastic Container Registry using AWS CLI.
**IMPORTANT:** You don't need a real AWS account, we are only going to evaluate the usage of the AWS command line interface.
