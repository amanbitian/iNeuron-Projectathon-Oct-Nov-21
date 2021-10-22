# iNeuron-Projectathon-Oct-Nov-21


## Problem Statement:
Design a web portal to automate the various operation performed in machine learning
projects to solve specific problem related to supervised or unsupervised use case.
Web portal must have the capabilities to perform below mentioned task:
1. Extract Transform Load:
a. Extract: Portal should provide the capabilities to configure any data source
example. Cloud Storage (AWS, Azure, GCP), Database (RDBMS, NoSQL,),
and real time streaming data to extract data into portal. (Allow feasibility to write
custom script if required to connect to any data source to extract data)
b. Transform: Portal should provide various inbuilt functions/components to apply
rich set of transformation to transform extracted data into desired format.
c. Load: Portal should be able to save data into any of the cloud storage after
extracted data transformed into desired format.
d. Allow user to write custom script in python if some of the functionality is not
present in the portal.
2. Exploratory Data Analysis:
Portal should allow users to perform exploratory data analysis.
3. Data Preparation: data wrangling, feature extraction and feature selection should
be automation with minimal user intervention.
4. Application must suggest appropriate machine learning algorithm which is best
suitable for the use case and perform best model search operation to automate
model development operation.
5. Application should provide feature to deploy model in any of the cloud and
application should create prediction API to predict new instances.
6. Application should log each and every detail so that each activity can be audited
in future to investigate any of the event.
7. Detail report should be generated for ETL, EDA, Data preparation and Model
development and deployment.
8. Create a dashboard to monitor model performance and create various alert
mechanism to notify appropriate user to take necessary precaution.
9. Create functionality to implement retraining for existing model if it is necessary.
10.Portal must be designed in such a way that it can be used by multiple
organization/user where each organization/user is isolated from other.
11.Portal should provide functionality to manage user. Similar to RBAC concept used
in Cloud. (It is not necessary to build so many role but design it in such a way that
it can add role in future so that newly created role can also be applied to users.)
Organization/User can have multiple user and each user will have specific role.
12.Portal should have a scheduler to schedule training or prediction task and
appropriate alert regarding to scheduled job should be notified to
subscriber/configured email id.
13.Implement watcher functionality to perform prediction as soon as file arrived at
input location.

## Approach:
1. Follow standard guild line to write quality solution for web portal.
2. Follow OOPS to design solution.
3. Implement REST API wherever possible.
4. Implement CI, CD pipeline with automated testing and dockerization. (Use
container or Kubernetes to deploy your dockerized application)
5. CI, CD pipeline should have different environment example ST, SST, Production.
Note: Feel free to use any of the technology to design your solution.

## Results:
You have to build a solution that should summarize the various news articles from
different reading categories.

## Project Evaluation metrics:
Code:
 You are supposed to write a code in a modular fashion
 Safe: It can be used without causing harm.
 Testable: It can be tested at the code level.
 Maintainable: It can be maintained, even as your codebase grows.
 Portable: It works the same in every environment (operating system)
 You have to maintain your code on GitHub.
 You have to keep your GitHub repo public so that anyone can check your code.
 Proper readme file you have to maintain for any project development.
 You should include basic workflow and execution of the entire project in the readme

file on GitHub
 Follow the coding standards: https://www.python.org/dev/peps/pep-0008/

## Database: Based on development requirement feel free to choose any database (SQL,
NoSQL) or use multiple database.

## Cloud:
 You can use any cloud platform for this entire solution hosting like AWS, Azure or
GCP.

## API Details or User Interface:
1. Web portal should be designed like any cloud platform.
2. Model developed using web portal should have functionality to expose
API to test prediction.

## Logging:
 Logging is a must for every action performed by your code use the python logging
library for this.

## DevOps Pipeline:
Use source version control tool to implement CI, CD pipeline, e.g.: Azure
Devops, Github, Circle CI.

## Deployment:
 You can host your application in the cloud platform using automated CI, CD pipeline.

## Solutions Design:
 You have to submit complete solution design strategies in HLD and LLD document

## System Architecture:
 You have to submit a system architecture design in your wireframe document and
architecture document.

## Latency for model response:
 You have to measure the response time of your model for a particular input of a
dataset.

## Optimization of solutions:
Try to optimize your solution on code level, architecture level and mention all of
these things in your final submission.
 Mention your test cases for your project.

Submission requirements:

## High-level Document:
You have to create a high-level document design for your project. You can reference the
HLD form below the link.


## Low-level document:
You have to create a Low-level document design for your project; you can refer to the LLD
from the below link.

## Architecture: You have to create an Architecture document design for your project;
you can refer to the Architecture from the below link.

## Wireframe: You have to create a Wireframe document design for your project; refer to
the Wireframe from the below link.

## Project code:
You have to submit your code GitHub repo in your dashboard when the final submission
of your project.

## Detail project report:
You have to create a detailed project report and submit that document as per the given
sample.


## Project demo video:
You have to record a project demo video for at least 5 Minutes and submit that link as per
the given demo.

## The project LinkedIn a post:
You have to post your project detail on LinkedIn and submit that post link in your
dashboard in your respective field.

