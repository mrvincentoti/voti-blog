## DEPLOY A NODEJS APPLICATION TO ELASTIC BEANSTALK USING EB CLI

###### This is a step by step guide on how to deliver the applications you develop for a cloud platform (AWS)

#### Instruction

##### A. Create an RDS database

1. Create a free AWS account [AWS](https://aws.amazon.com/free)
2. Login to the management console and search for RDS
3. On the RDS dashboard click create database
4. Select postgreSQL
5. Fill in the details
6. In the Network & Security section select yes under public accessibility
7. Click on create
   ** Take note of the RDS endpoint, the database username, passsword, and database name**

##### B. Clone and install project

1. clone this reposiroty with `git clone`
2. install project dependencies `npm install`
