# Student Management Kiosk

Packages Installation:

<b>1.</b> npm install
<b>2.</b> cd client -> npm install

START cmd:
npm run dev

# Modules : 
<b>1. Login </b>
![Login Deployed](https://github.com/kishan9192/Automated-Student-kiosk-using-DevOps/blob/master/Images/Deployed%201.png)

<b>2. Attendance </b>
![Attendance Module Deployed](https://github.com/kishan9192/Automated-Student-kiosk-using-DevOps/blob/master/Images/attendance%20module.jpg)

<b>3. Time-Table</b>
![Time-Table Deployed](https://github.com/kishan9192/Automated-Student-kiosk-using-DevOps/blob/master/Images/time-table%20module.jpg)

<b>4. Support</b>
![Support Module Deployed](https://github.com/kishan9192/Automated-Student-kiosk-using-DevOps/blob/master/Images/support%20module.jpg)

The application is deployed at "http://jiitweb.herokuapp.com/"

Use Jenkins(a DevOps tool) for CI/CD i.e. Continuous Integration/Continuous Deployment. Everytime there's a commit in the master branch, the will start building. The overall process of DevOps is Build -> Deploy -> Test -> Release. The pipeline made in this project using Jenkins has 3 stages:

<b> 1. Build </b>
Build contains the command "npm install", which is responsible for copying and downloading all the dependencies that are required to run the project. This bridges the gap between development team and the operations team.

<b> 2. Test </b>
The modules that were written, are tested by writing the test scripts in Java, and using a tool Selenium.

<b> 3. Deploy </b>
Once all the changes are built and tested, they are deployed at "jiitweb.herokuapp.com" 

![Jenkins-Pipeline](https://github.com/kishan9192/Automated-Student-kiosk-using-DevOps/blob/master/Images/Jenkins%20pipeline2.png)


All of the above process takes 5-10 mins, once the changes are pushed and committed in the master branch.



