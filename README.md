# Devil-s_Eye portfolio

# All about the devil’s vision 


![](images/devils_eye.gif)

- Before students used to attend classes physically attending the classes and lecturers used to manually teach them while keeping an eye on them. But, due to the era of new normal we are here using the advantage of the internet and attending classes through Zoom video conferencing. Where a student needs to join the class through a link and have to keep their Camera and microphone on during the class.
- But students will be students whatever the era it might be. Therefore, during the zoom sessions the student will switch off their camera and microphone and that is the new normal type of bunking the classes. Having said that, the mentor will be unaware of the status of the student. Finding if the student is attending the class or not is a tough task to do. -Therefore, to overcome this problem we are developing an application called “DEVIL’S EYE”, which keeps popping certain questions in periodical timings so as to make sure if the student is attentive during the class or not. If they are attentive then they will answer the right questions and get the attendance of that session. If not, they will miss their attendance.

# Sprint-1: Explored Electron Application

![](images/electronjs.jpeg)

- Devil’s eye is a desktop application. We have decided to design it in an electron app using Javascript . As I have little knowledge in react and javascript in order to design better I learned certain Javascript concepts which are useful to the project.
- As I started working on the project it has become tougher than it looked. I have faced the biggest challenge to integrate changes done in Java script to reflect in the main process where the electron apps can work.
- Inorder to get more understanding and grip on the project, I have referenced electron documentation and watched some youtube videos and had a firm knowledge on IPC main and renderer process and successfully the hello-world page is designed in electron.

# Sprint-2: Sign In process

![](images/login.jpeg)

- To start with the project, our team and I have decided to work on the Sign-In page first for our application.
- With which the students need to sign-in into the application with an MSIT email.
- For the Sign-in application, we used MongoDB for database collection where we stored all MSIT student’s details for instance, student name, email-Id etc in a collections database with their respective ID numbers.
- Whenever an user signs in into a devil’s eye application it will send an API which checks whether it is a valid email or not by checking in the database and returns a response.
- Based on the response i.e if the user is legitimate then the application starts loading to the next page where the mentors page will be loaded.
- If the user is not legitimate it will ask the user to try again with a valid e-mail ID then the page gets loaded from there.

# Sprint-3: Database in MongoDB

![](images/MongoDB-to-JSON.png)

- MongoDB is an open-source document database and leading NoSQL database. MongoDB is written in C++. This tutorial will give you great understanding on MongoDB concepts needed to create and deploy a highly scalable and performance-oriented database.
- Initially I faced difficulty while working on databases and how to fetch the data from the database on our local machines.
- After exploring, our team and I decided to use the AWS lambda function for response. We used an API key for response on local machines.
- Similarly, for the mentors list I have used stored IT and SOFT SKILLS Mentor details.
- After loading mentor details, I worked on DIALOG BOX POP UP which is the soul of the project. Initially dialog box pop up occurred not on the current window.
- Finally, after getting the whole understanding on the electron and how to get the popup box on the particular page which will be embedded in the electron application only.

# Sprint-4: Generate DialogBox at randon time

![](images/electron-showmessagebox.png)

- As a student, I want to start the session after selecting my respective session type and mentor name. So that, I can join the session.
- As a student, I want to get the dialog box at random time stating whether I am attentive in the session or not. So that, I can claim attendance by clicking “Yes that I am present in the session”.

