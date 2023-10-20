

[![DOI](https://zenodo.org/badge/404911045.svg)](https://zenodo.org/badge/latestdoi/404911045)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Build Status](https://app.travis-ci.com/atharva1996/Simplii.svg?branch=main)](https://app.travis-ci.com/nisarg210/Simplii)
![Code Coverage](https://github.com/nisarg210/Simplii/blob/main/src/coverage.svg)
![github workflow](https://github.com/nisarg210/Simplii/actions/workflows/style_checker.yml/badge.svg)
![github workflow](https://github.com/nisarg210/Simplii/actions/workflows/syntax_checker.yml/badge.svg)
![github workflow](https://github.com/nisarg210/Simplii/actions/workflows/close_as_a_feature.yml/badge.svg)

## Link to Demonstration Video of the Project: 
https://drive.google.com/file/d/1rApSm9mfYJVBAC05cEsd61l3WbkrtomQ/view?usp=sharing

# SIMPLII

<h3>Having trouble in keeping track of your daily tasks and managing them? </h3>

Introducing to Simplii- an online task tracker that will assist you in keeping track of all your day-to-day activity so that you can manage your work efficiently. Task-tracking can be a tardy process and we have fixed this pain with the help of Simplii. Organize your work, track time, and update the status of your tasks simply with our easy-to-use application.

<p align="center">
<img width="614" alt="Screen Shot 2021-12-03 at 10 11 02 PM" src="https://user-images.githubusercontent.com/89509351/144695927-bf2e2524-5723-46d2-a946-4aab3bc6931e.png">
</p>


# Table of Contents  

- [Why use Simplii?](#why-use-simplii)
- [Built with:](#built-with)
- [Core Functionalities of the Application:](#core-functionalities-of-the-application)
  - [Register](#register)
  - [Login](#login)
  - [Adding tasks](#adding-tasks)
  - [Task Recommendation and Display](#task-recommendation-and-display)
  - [Modifying tasks Updating and Deleting](#modifying-tasks-updating-and-deleting)
- [Steps for Execution:](#steps-for-execution)
- [Source Code](#source-code)
- [Delta](#delta)
- [Future Scope](#future-scope)
- [Team Members](#team-members)
- [Contribution](#contribution)
- [License](#license)

## Why use Simplii?

-User can add tasks based on their difficulty levels- Physical or Intellectual work and then work on it depending on their priority.<br>
-User can keep a track of the upcoming tasks by checking their deadlines and then work towards it.<br>
-User can easily check the progress of his work by checking the status tab.<br>
-Tasks are recommended to the users based on their upcoming deadlines for the user's convenience.<br>

<p align= "center">
<img width="600" height ="500" src="https://user-images.githubusercontent.com/89509351/144696048-8968db92-e41a-44b1-a720-66a482e0ed4a.png"> 
</p>


 
 



## Built with:
<table border = "0px">
  <tr>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="40" height="40" /><b>Python</b></td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="40" height="40" /><b>JavaScript</b></td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="40" height="40"/><b>HTML5</b></td>
<td align="center"><img src ="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="40" height="40"/><b>CSS3</b></td>
<td align="center"><img src ="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" width="40" height="40"/><b>Bootstrap</b></td>
<td align="center"><img src ="https://raw.githubusercontent.com/devicons/devicon/v2.14.0/icons/flask/flask-original.svg" width="40" height="40"/><b>Flask</b></td>
<td align="center"><img src ="https://raw.githubusercontent.com/devicons/devicon/v2.14.0/icons/mongodb/mongodb-original.svg" width="40" height="40"/><b>MongoDB</b></td>  
  </tr>
</table>


## Core Functionalities of the Application:
 
 ## Register:
 

https://user-images.githubusercontent.com/89509351/144703691-aa8a10cd-db81-48f9-bc21-467f82a53378.mp4


 
 ## Login:
 https://user-images.githubusercontent.com/89509351/144703694-09252613-a2f7-4dff-a574-b4a20cb69fd4.mp4
 
 ## Adding Tasks:
 

https://user-images.githubusercontent.com/89509351/144703705-0628f2a2-8004-442c-8612-a5de40de92be.mp4


 
 ## Task Recommendation and Display:
 
 

https://user-images.githubusercontent.com/89509351/144703718-a2f478e3-b4ea-4fa2-a784-9a3b5c335a57.mp4
 
 
 ## Modifying the tasks - Updating and Deleting:
 

https://user-images.githubusercontent.com/89509351/144703727-e757e3e4-3776-470f-b08f-516593cb861e.mp4




## Steps for execution
 
 Step 1:
 Install MongoDB using the following link:
 
 https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows
 
 Step 2: 
  Git Clone the Repository 
  
    git clone https://github.com/nisarg210/Simplii.git
    
  (OR) Download the .zip file on your local machine
  
    https://github.com/nisarg210/Simplii.git
  
 Step 3:
   Install the required packages by running the following command in the terminal 
   
    pip install -r requirements.txt
    
 Step 4:
    Run the following command in the terminal
    
    python application.py
    
 Step 5:
    Open the URL in your browser:  
      http://127.0.0.1:5000/
      
## Source Code
  
  Link to the repository:
    https://github.com/nisarg210/Simplii
                                                                                                                                                  
 ## Delta
 
 <b> a) Task Tracking based on the type of work</b>
        <li>The earlier version of Simplii just used to add the category of task as text.
        <li>In our updated version of Simplii, the tasks can be tracked based on their types. We have two types Intellectual & Physical.
    
 <b>b) Email Remainder Sysytem (New Feature)</b>
    
 <b>c) Added critical information like credintials, DB connection strings in enviornment file. (Enhancement)</b>
        
 <b>d) Implement Reset Password (New Feature)</b>
  <b>e) Add description feild for task (New Feature)</b>
 <b>f) Fixed on wrong password system breakdown error. (Bug Fix)</b>
 <b>g) Fixed on data fetch in update page data in some feilds were missing. (Bug Fix)</b>
 <b>h) Added validations for input field of forms. (Bug Fix)</b>
        <li> Hours -> Interger, Task Name -> String</li><li>Start Date less than equal to DueDate</li>
    
        
  
   ## Future Scope
  
  The  following features can be implemented in the future scope of this application:
 
   1. Create a mobile application for the web version of the application.
   2. Make the website view port adaptable - the website should look good on phone, tablet and computer.
   3. Create chatbot for the web portal
   4. Recommend tasks.
   
   ## Team Members
   
  <table>
  <tr>
  <td align="center"><a href="https://github.com/kskheni"><img src="https://avatars.githubusercontent.com/u/49781516?v=4" width="100px;" alt=""/><br /><sub>       <b>Kaushal Kheni</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/nisarg210"><img src="https://avatars.githubusercontent.com/u/58519704?v=4" width="100px;" alt=""/><br /><sub>     <b>Nisarg Prajapati</b></sub></a></td>
    <td align="center"><a href="https://github.com/surya-sukumar"><img src="https://avatars.githubusercontent.com/u/79688972?v=4" width="100px;" alt=""/><br /><sub>       <b>Surya Sukumar</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/Mihir1310"><img src="https://avatars.githubusercontent.com/u/82660793?v=4" width="100px;" alt=""/><br /><sub>        <b>Mihir Bhanderi</b></sub></a><br /></td>
  </tr>
</table>

  ## Contribution
  
  Please refer the CONTRIBUTING.md file for instructions on how to contribute to our repository.

  ## License
  
  This project is licensed under the MIT License.
  
                                                                                                                                                   
                                                                                                                                                   
                                                                                                                                                   
                                                                                                                                                   
                                                                                                                                                   
                                                                                                                                                   
                                                                                                                                                   
                                                                                                                                                   
                                                                                                                                                   
                                                                                                                                                   
                                                                                                                                                   
                                                                                                                                                   
                                                                                                                                                   
                                                                                                                                                   
  
  


      
 
 
 
 
 
 
 
 
 
 
 
 


