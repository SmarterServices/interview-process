# January 2015 Developer Interview Project (DRAFT)

If you have found this repository it is likely because you are going through the interview process.  

The purpose of this repository is to provide job candidates an avenue to showcase their skills by creating a very simple application based on the specifications outlined here.  

# House Keeping Notes
Please keep these things in mind prior to getting started:

1. To ensure your work cannot easily be copied by other candidates, please do not fork this repository.
2. If you are unsure how to proceed with this repository there is a high chance you do not meet the minimum requirements for this job.  
3. If you make it to the next stage of the interview process, you will be asked to provide a 15-20 presenation of the work completed on this project.  Please keep this in mind as you are putting together your solution.
4. We do not want this project to take up too much of your time so we purposfully made it straightforward.  We estimate this project to take between 4-6 hours of time.

# Project Specifications
For this project you will be constructing simple user interface that will display assessment results with the ability to drill in to look at details.  In addition to the user interface, you will need to create a REST API that will serve as a proxy to the SmarterMeasure MOCK API.  Once this project is completed you will have completed the following:

* An interface to display assessment results with associated detail view for each student.
* Added the ability for the user to find a student by their email address.

We have provided a visual below to clearify how the final product should be communicating with the SmarterMeasure Mock API.  

1. The user will load the user interface you create
2. Your user interface will communicate directly with the REST API you create.
3. Your REST API will communicate with the SmarterMeasure MOCK API.

```
                            ---------------          --------------------------
Your User Interface -----> | Your REST API | -----> | SmarterMeasure MOCK API  |
                            ---------------          --------------------------
```
**IMPORTANT: The user interface should never call the SmarterMeasure MOCK API directly.**


## Requirements

### User Interface
The user interface should use bootstrap for the styling as well as a front end framework such as AngularJS, ReactJS, JQueryUI, etc.  Please choose the framework you are most comfortable with and would choose if you were building a larger scale web application.

### Node.js Code
You are free to structure the Node.js code as you wish, however we will be looking for a solid understanding of architecting a node application.  You are welcome to choose a REST API framework if you wish and use any npm modules you feel are required to complete the task.

### Functionality

The application should have at minimum 2 views/pages.  One view will allow the user to view the assessment results, the other should display a single users results.  While not required, you are more than welcome to add any other pages to show off some of your skills - for example a page that outputs statistical information about the user results, etc.


### Installing the Deliverable
The deliverable should be easily installed by following an updated version of this README document in your repository.  To provide a standard place to add your project specific install notes, we have provided a section below titled "Candidate Install".

# Connecting to the SmarterMeasure API
For this project we have created a mock API that mimics the actual SmarterMeasure API.  Here are a few things to note about this API:

* To keep things simple, there is no authentication required.
* All the data that is returned is mock/dummy data.

The documentation for the SmarterMeasure API is located at [https://github.com/SmarterServices/2015-developer-interview-project/blob/master/API.md](https://github.com/SmarterServices/2015-developer-interview-project/blob/master/API.md)


# Candidate Install
Please edit this section providing any documention required to get your version of the install running.  This should include the following:

* How to install the app.
* How to run the unit tests.
* How to run the server, if different from the default method provided.
