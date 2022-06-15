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
####  Landing page
All employees will have access to a landing page once they log into the system. Agents will see a button that connects them to Amazon Connect CPP in order to be ready to receive incoming calls.
(![agent_homeview_](https://user-images.githubusercontent.com/53417886/173720636-d81615a0-a9d3-48fa-8c03-d1261ecda4c5.gif))
####  Survey
Once an agent has picked up the call and finished working on a ticket, if the manager has set it up this way, they will be presented with a survey regarding the call quality, client interaction or any important metric the manager has decided. Once the survey has been answered, the video will be stored in s3 and the survey answers and video’s metadata will be stored.
#### Shared videos
The agent can see all the videos that were shared to them, and filter them by date or tags.
![Alt Text](https://drive.google.com/file/d/1xWaGyfzkf_fJYYBzzxrZusLHoo4Vzn9S/view?usp=sharing)
### Manager
#### Agent’s visualization
The manager has the option to view all the agents registered in the system, and filter them by name or employee ID.
![Alt Text](https://drive.google.com/file/d/1qUY2tPgFA4euv9c_8Tl91lXLVtdrxjVp/view?usp=sharing)
#### Create new agents
The manager can add new agents to the system.
![Alt Text](https://drive.google.com/file/d/1QAPpSFZOfrmx4XUh5Rk6W6TH0px4sFCa/view?usp=sharing)
#### Assign agents to supervisor
The manager can assign agents to a supervisor and to a group.
![Alt Text](https://drive.google.com/file/d/1QAPpSFZOfrmx4XUh5Rk6W6TH0px4sFCa/view?usp=sharing)
#### Update/delete of agents
The manager can change the information of the agent, such as name, password or email. Also, he can delete them from the system.
![Alt Text](https://drive.google.com/file/d/1ESKW3Vg8RRlahOX04pOLCmf1YnCiAF-P/view?usp=sharing)
![Alt Text](https://drive.google.com/file/d/14h4PN824A7sXcrtUQEQCZAnKyNI6T5ia/view?usp=sharing)
#### Supervisor’s visualization
The manager can see all supervisors and search them by name or employee ID.
![Alt Text](https://drive.google.com/file/d/1MgiKgQ9CuOb4KGjnZHuG8uvEZvvXYzWH/view?usp=sharing)
#### Create new supervisors
The manager can add new supervisors to the system.
![Alt Text](https://drive.google.com/file/d/1YIpQuk1PngiVDWvouCxcsOL0qbUUljIU/view?usp=sharing)
#### Update/delete supervisors
The manager can change the information of the supervisors, such as name, password or email. Also, he can delete them from the system.
![Alt Text](https://drive.google.com/file/d/1vSDQMqkqLa8w3hT8NoPIvN3RiH3Vk6XB/view?usp=sharing)
![Alt Text](https://drive.google.com/file/d/1tO4vL4eiPrJx8egk6QxloBnxbmmjcdMC/view?usp=sharing)
#### Video’s visualization
The manager can see all the videos that were created by the agents, and filter them by date or tags.
![Alt Text](https://drive.google.com/file/d/12ntQ9LGr_dI9uvgRfpq2gnbJm-F_Ts3v/view?usp=sharing)
![Alt Text](https://drive.google.com/file/d/1iXYz5_H620DMKMuj18xMqmKEaOdWbs1p/view?usp=sharing)
#### Change Settings
The manager can change the minimum amount of time for a video to be saved, and the questions and answers that will need to be answered by the agents at the end of the call. 
![Alt Text](https://drive.google.com/file/d/1PFAiy4xhWEPKmHmRlsLYhtW66tWla7lb/view?usp=sharing)
### Supervisor
#### Agent’s visualization
The supervisor can see all the agents that were assigned to him and can be filtered by name or employee ID.
![Alt Text](https://drive.google.com/file/d/1SX9OUZbtXHhFuZ85zsd1VsTY40kiDz2n/view?usp=sharing)
#### Agent’s graphs visualization
The supervisor can see the individual graphs of the agents to see their performance. Also, the information of the agent can be filtered by a date range.
![Alt Text](https://drive.google.com/file/d/1ZvRzliT4zk2fQ7_gbhWtdRGTeMyHO17d/view?usp=sharing)
#### Video’s visualization
The supervisor can see all the videos that were made by his agents, and filter them by date or tags.
![Alt Text](https://drive.google.com/file/d/1AX1Zw5VX5pA90RwdWB14I-1Q1PcgKVRe/view?usp=sharing)
#### Video’s update
The supervisor can change the tags that the video contains.
![Alt Text](https://drive.google.com/file/d/1DwX4v5VfMBEFZIZ8SUdtezIp2TwbPqqq/view?usp=sharing)
#### Overall graphs
The supervisor can see global graphs from the data collected from his agents, and can be filtered by a date range. 
![Alt Text](https://drive.google.com/file/d/1HwASStEuGH9rtpCg48xa4eVCEG7ERFr7/view?usp=sharing)
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
## To deploy 
In order to deploy an new functionality for the system the next steps must be followed:
1. Clone the repository and create a new branch with the name feature for a new functionality or hotfix for a fix, followed by a slash (/) and a short description of the branch purpose.
2. Once the changes have been made, run unitary tests of the developed feature and integrations tests to ensure there are no regression errors
3. Once all tests have been run and passed, merge the branch to develop and test and make sure the system is working correctly with the new functionalities.
4. After everything has been tested, create a new pull request to branch main and wait for the assigned reviewers to review and merge your code.
5. If the branch has been merged, ask a developer with permissions to Jenkins to run the pipeline to deploy the new code.
6. In Jenkins, the pipeline is set up to fetch the code from the main branch, then it builds a maven package, creates a docker image and uploads it to ECR, and makes a deploy of the ECS instance in order to use the new image.
7. Currently, the project has only one instance of ECS so when a deploy is made, the server will experience some downtime while the new instance is deployed, however with more ECS instances, one of them would continue running while the other is set up to run the new image and the load balancer would redirect the requests to the running instance, so no downtime would be experienced. 
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
| spring-boot-starter-web  | Starter for building web, including RESTful, applications using Spring MVC. Uses Tomcat as the default embedded container. Used in back for expose endpoints database connection with front |
| aws-java-sdk-core  | The AWS SDK for Java - Core module holds the classes that are used by the individual service clients to interact with Amazon Web Services. Users need to depend on aws-java-sdk artifact for accessing individual client classes. For database connectivity. |
| aws-java-sdk-dynamodb  | The AWS Java SDK for Amazon DynamoDB module holds the client classes that are used for communicating with Amazon DynamoDB Service. |
| spring-data-dynamodb  | The primary goal of the Spring Data project is to make it easier to build Spring-powered applications that use data access technologies. This module deals with enhanced support for a data access layer built on AWS DynamoDB. |
| dynamodb-enhanced  | Used to manipulate models form the database, do queries as crud (create, read, update, delete) |
#### Used software versions
- IntelliJ IDEA 2021.3.3 (Community Edition)
- Docker 4.9.0
- Java Corretto-17.0.2.8.1
- NoSQL Workbench Versión 3.2.2
- Springboot v2.6.7
- Postman Version 9.20.3
#### Services’ configurations
- Springboot: port 8090
- DynamoDB: server east-1
- Jenkins: port 8080
### Backend
#### Software
- IntelliJ: It is used to work the backend part with programming in Java language. Version 2021.3.3
- Java: It is used to create the connection between the database and the front-end. version 11
- Docker: Used to test the DynamoDB database locally. Version v1.22.5
- Springboot: It is used to create the system environment. Version 2.7.0
- NoSQL Workbench: It is used to create and test unrelated databases locally. Version 3.2.2
- Postman: It is used to test the endpoints. Version 9.20.3
- Swagger: It is used to define the endpoints. Version 3.0.3
#### AWS Services
- DynamoDB: It is used to save the information of the database of our system.
- ECR: It is used to store the docker image of the system.
- ECS: Used to deploy the backend and database containers on EC2.
- EC2: It is used to deploy the application.
- S3: It is used to store the videos.
