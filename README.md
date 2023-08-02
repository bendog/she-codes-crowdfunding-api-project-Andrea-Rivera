
# LaunchPage Crowd by {Andrea Rivera}

She Codes crowdfunding project - DRF Backend.

## About
LaunchMyBusiness is created for Small businesses that need presence online and do not have time to create a static website that displays their products. 
Developers can help to adjust the existing templates according to their needs. In exchange, an amount 
of money can be donated to reach our goal as an incentive to keep helping small businesses to grow as well as our skills sets as developers.


## Features

* [] A user can login and see the template projects
* [] A user can pre-order a template and make comments to add his/her own functionalities 
 with the comment feature
* [] Developers will see the comment and approve the changes.
* [] Users can make comments to the projects to improve its functionality.
* [] Developers can make a plegde to help in the design and functionality of the webpage
* [] Each project will have 

### Stretch Goals
{{ Outline three features that will be your stretch goals if you finish your MVP }}

* [] Online Payments
* [] Users can see the projects by categories

## API Specification

| HTTP Method | Url | Purpose | Request Body | Successful Response Code | Authentication|Authorization
<br /> 
| GET | projects/ | Return all projects | N/A | 200 | N/A |
<br /> 
| POST | projects/ | Create a new project | project object | 201 | User must be logged in. |
<br /> 

## Database Schema
{{ Insert your database schema }}
![database schema](crowdfounding/crowdfounding/static/images/DRF.png)

## Wireframes
{{ Insert your wireframes }}
![login](crowdfounding/crowdfounding/static/images/login.png)
![about](crowdfounding/crowdfounding/static/images/about.png)
![project](crowdfounding/crowdfounding/static/images/project.png)

## Colour Scheme
{{ #264653, #2a9d8f,#e9c46a,#f4a261,#e76f51 }}
{{https://coolors.co/palettes/trending}}

![Colour Scheme](crowdfounding/crowdfounding/static/images/colour_scheme.png)

## Fonts
{{ outline your heading & body font(s) }}


## Submission Documentation
{{ Fill this section out for submission }}

Deployed Project: [Deployed website](http://linkhere.com/)

### How To Run
{{ What steps to take to run this code }}

### Updated Database Schema
{{ Updated schema }}

![image info goes here](./docs/image.png)

### Updated Wireframes
{{  Updated wireframes }}

![image info goes here](./docs/image.png)

### How To Register a New User
{{ Step by step instructions for how to register a new user and create a new project (i.e. endpoints and body data). }}

### Screenshots
* [] A screenshot of Insomnia, demonstrating a successful GET method for any endpoint.
![image info goes here](./docs/image.png)

* [] A screenshot of Insomnia, demonstrating a successful POST method for any endpoint.
![image info goes here](./docs/image.png)

* [] A screenshot of Insomnia, demonstrating a token being returned.
![image info goes here](./docs/image.png)
