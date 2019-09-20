# Fun With Lambda

## Table of Contents
1. Lab 31: Lambda
2. Lab 32: Lambda Warmers and Triggers
3. Lab 33: 

---------------------------------------

### 1. Lab 31: Lambda

#### Feature Tasks Completed
- A user should be able to upload an image at any size, and have both the original size and a thumbnail size associated with the task in question.
- When an image is uploaded to your S3 bucket, it should trigger a Lambda function. (That Lambda function may be written in any language.)
- That function should create a 50x50 pixel thumbnail version of that image, and save it to another S3 bucket. It should do so with a predictable naming convention, so that your server and/or frontend know where that thumbnail image will be.

### Contributions
- Fabion Brooks
- Marisha Hoza
- Brandon Hurrington
- Steve Grant
- Nhu Trinh
- Padma Ganapathi
- Jackie
- Nicholas Paro
- Peter Lee

---------------------------------------

### 2. Lab 32: Lambda Warmers and Triggers

#### Feature Tasks Completed
- Create a lambda function, in Java, that can add a record to your Taskmaster table.
- Run this only in “Test” mode
- It should receive the same object that your API was handling earlier.
- Repeat for “PUT” / update functionality

### Contributions
- Fabion Brooks
- Marisha Hoza
- Brandon Hurrington
- Steve Grant
- Nhu Trinh
- Padma Ganapathi
- Jackie
- Nicholas Paro
- Peter Lee
---------------------------------------

### 3. Lambda API Gateway

#### Feature Tasks Completed
- Create a new (empty) Lambda function for each route in Taskmaster
  - Get all Tasks
  - Get tasks for a user
  - Create New Task
  - Delete Task
- Create a new API using AWS API Gateway
  - Create a new resource /tasks
  - Create a new Resource + Method to match the taskmaster functionality
  - For each resource, point them at the proper Lambda function
  ### Routes
- GET /tasks
- GET /tasks/{user}
- POST /tasks
- PUT /tasks/{id}/state
- PUT /tasks/{id}/assign/{assignee}

### Contributions
- Fabion Brooks
- Marisha Hoza
- Brandon Hurrington
- Steve Grant
- Nhu Trinh
- Padma Ganapathi
- Jackie
- Nicholas Paro
- Peter Lee
