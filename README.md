## Amazon Recording System Helper
> Development of a platform that records the voice and screen of call center agents with a video storage that supervisors and administrators can access.
> About the project [here](https://drive.google.com/file/d/1IXOJk660n73o6-zI0VxidVyq16ES7kq3/view?usp=sharing).
## Table of Contents
* [Product vision](#product-vision)
* [Project goals](#project-goals)
* [Main functionalities](#main-functionalities)
   * [Agent](#agent)
   * [Supervisor](#supervisor)
   * [Manager](#manager)
* [Pre requirements](#pre-requirements)
* [Download project](#download-project)
* [Techdeck](#techdeck)
   * [Database](#database)
   * [Backend](#backend)
## Product vision
What we are looking for with this project is to give organizations a better insight about their call center activity to improve their processes, while also helping them to reduce time and cost spent on their regular operations and in training new agents. Offerening insights about their daily operations will help them find areas of opportunity inside their organizations. In addition, we expect to create a registry of common problems in order for the agents to solve them faster with future clients. We will provide general statistics where supervisors can monitor their agent’s performance, this functionality will provide an advantage to Amazon Connect given that it offers something none of its competitors currently has. Finally, with better training for new agents, organizations can reduce the time it takes for the agents to solve the client’s issues which enhances the user experience.
## Project goals
| Business Goal/Objective | Description |
| ------------- | ------------- |
| More efficient answers and solutions  | The project seeks to find and perfect solutions about common issues providing a reply with better results in a short time thanks to the recordings that allow keeping a profile of the customers and their frequent requests.  |
| Better customer service  | Identification of frequent requests and customer profile will allow providing an answer in less time and with better results each time it’s implemented.  |
| Information bank  | The set of call recordings will generate an information bank in which the agents will be able to obtain information that will allow them to generate better solutions for the customers. This information will also allow generating metrics related to the agent's performance and the quality of their calls with the customers.  |
| Faster training  | The data bank of previous recordings will be able to serve as training material on realistic sceneries, aiming for a faster and more realistic training.  |
## Main functionalities
### Agent
### Supervisor
### Manager
## Pre requirements
- Docker
- IntelliJ
## Download project
If this is your first time working on the code, follow these steps:
1. Create a folder where the project will be saved and open the path in a **CMD**.
2. **Clone** the project.
```bash
git clone git@github.com:TC3005B-562/azul-backend.git
```
3. Open the **folder** azul-backend in IntelliJ.
4. Go to the folder src → main → java → com.itesm.AmazonRSH.Team4DB → Team4DbApplication.
5. Right click **run**.
## Techdeck
### Database
#### Services and resources from AWS
- Dynamo DB: noSQL database service.
- EC2: offers users to rent virtual computers on which they can run their own applications.
- ECR: is an managed container image registry service that is secure, scalable, and reliable.
- ECS: s a highly scalable, high performance container management service.
- S3: offers object storage through a web service interface.
#### Resources to deploy locally
- Docker DynamoDB Local Image.
- Springboot with Intellij.
- NoSQL Workbench.
- Java.
#### Resources to deploy in cloud
- ECR.
- ECS.
- EC2.
- DynamoDB.
- Amplify.
- S3.
- Jenkins.
- Github.
#### Used libraries
| Library | Description |
| ------------- | ------------- |
| spring-boot-starter-parent  | Parent pom providing dependency and plugin management for applications built with Maven |
| spring-boot-starter-web  | Starter for building web, including RESTful, applications using Spring MVC. Uses Tomcat as the default embedded container.
Used in back for expose endpoints database connection with front |
| aws-java-sdk-core  | The AWS SDK for Java - Core module holds the classes that are used by the individual service clients to interact with Amazon Web Services. Users need to depend on aws-java-sdk artifact for accessing individual client classes. 
For database connectivity. |
| aws-java-sdk-dynamodb  | The AWS Java SDK for Amazon DynamoDB module holds the client classes that are used for communicating with Amazon DynamoDB Service. |
| spring-data-dynamodb  | The primary goal of the Spring Data project is to make it easier to build Spring-powered applications that use data access technologies. This module deals with enhanced support for a data access layer built on AWS DynamoDB. |
| dynamodb-enhanced  | Used to manipulate models form the database, do queries as crud (create, read, update, delete) |
### Backend
hola
