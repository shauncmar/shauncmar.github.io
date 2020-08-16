## Welcome to Shaun Cmar's ePortfolio

### A brief background
As a part of my time at Southern New Hampshire University, and my professional career I have learned about the how to
best design software.  My time in the industry began in 2006 when I attended the University of New Hampshire, and worked
at a network testing lab.  After leaving the University of New Hampshire I spent some time working as a sales associate
at best buy to keep myself in the industry, and to expand my soft skills.  During my time at Best Buy I began to take
classes at NHTI in information technology, with a concentration in networking.  At the same time I began to work at
a software development company, Newforma, in Manchester, NH as a support technician for the cloud product that they produced.

While completing my Associates in Information Technology, I advanced my capabilities at Newforma, and began performing
Database Administration style work for them and worked very closely with a software engineer.  He recommended I shift out 
of Technical Support and move into a Development Support position.  In this position, I wrote tools that developers would 
use to make their day to day life easier.  These tools included a deployment pipeline which ran the developers code 
through unit tests, deployment into a cloud environment, and acceptance test the now deployed code. During my time in this 
role I learned a lot about the development process, from initial design, to coding, to code review.  

Today I work for Newforma as a Full Stack developer as well as finishing my Bachelors of Science in Computer Science from
Southern New Hampshire University though their online program.

### Professional Assessment

During this course, I have had to act as an engineering team presenting to and collaborating with a stakeholder.  In 
this instance the stakeholder, and collaborator has been my professor.  It started as a presentation of a code review.  
I presented the artifact I was intending on making changes to, and recorded a walk-through of the code, and the 
particular areas I intended on changing.  This type of walk through is critical to learning new best practices and 
teaching a team member about why you coded the way you did.  
	
Each week I had to give an update to my stakeholder which included the status of my ePrortfolio, if I had to make any 
changes on what my original plan was, and if I thought I was on track to complete the project in the allotted time.  
This is a critical part of the Software development process because a complete product does not simply come together 
over night.  Without these check ins, work would have likely been crunched together, and I would not have confidence 
that I was on the right path for completing the project. 
	
The first potion of my project was within the software engineering and design area.  Here I spent time converting a 
python codebase into a JavaScript codebase.  The ability to replicate functionality inside of a different language is a 
critical skill to possess as a computer scientist.   
	
The second potion of my project was within algorithms and data structures.  Here I spent time improving the quality of 
the code present.   I did this by improving the readability through comments, and improving the variable names provided.  
In addition to these changes, I also made error conditions clearer.  In the original artifact there was a lack of 
information within each error condition.  In order to troubleshoot errors, it is critical that error conditions can 
be differentiated, this will allow for faster troubleshooting.  At the same time, it is critical you do not give away 
too much information in an error as that could be a security risk.  For example, in a login if you gave information that 
the username was correct, but the password was not, it would be very easy to brute force crack that password.  
	
The final portion of my final project was around Databases.  For this I created a front-end system for a mongoDb.  
This is important because it exposed me to another language, html, and it is a real-world example.   No end user wants 
to have to use a command line interface to interact with a database.   Furthermore, no application developer wants to 
give unfettered access to a database.  Someone with that kind of access to a database could run whatever query’s they 
wanted against it, which would be a huge security loophole.  
	
The following artifacts, along with the justification of why they were included within my ePortfolio will show that I 
have grown as a developer since starting the program.  It will display my ability to convert a repo, as well as a new 
understanding of how to code for readability and sustainability.  In addition to this, it will show that I know how to 
protect a Database by applying a front end to it, which will perform canned queries instead of arbitrary queries.  


### Code Review
The Code review process is a useful tool which Software Developers use to learn new skills, or best practices as well as 
review the process.  I did an informal code review, using a [checklist](./CodeReview/SNHU_Code_Review_Checklist.pdf) 
provided in my Capstone Class, CS-499 at SNHU.  The artifact I reviewed can be found 
[within the project](./Original%20Artifact/finalProjectPythonFiles.zip)  During this code review I outline the changes 
I intend to make to the artifact, and how they relate to my time within the computer science program.  I recorded the 
code review and it may be found [on youtube.](https://youtu.be/GsANZLlW95w)

### Software Design/Engineering
The artifact is a RESTful CRUD API that was written initially in Python, and may be found 
[within the project](./Original%20Artifact/finalProjectPythonFiles.zip) but as apart of this course was converted the 
artifact to JavaScript.  It was initially created as apart of CS-340 a few semesters ago.  The new artifact can be found
[within the project.](./Software%20Design%20and%20Engineering/mongoDbAccessor.zip)

I choose this item because it represented a basic API which I worked on, and saw a lot of room for improvement.  I 
selected JavaScript because in my day to day job I work in TypeScript, which is just different enough from JavaScript to 
pose a real challenge, and I want to learn the under workings of TypeScript.  I was able to convert the artifact to 
JavaScript, and gained some exposure to a slightly different interface to MongoDb.  I also added comments before each 
method that was added so that it is more apparent as to what each method does. 

I learned that there are a large number of mongodb clients out there, and that setting up a REST CRUD API in JavaScript 
was as straightforward as in python.  I did have a few problems because my version of node was only version 6 on my 
laptop and I did not check my version until I after I started debugging.  I also found that working in JavaScript objects 
were handled a bit different than I expected.  

### Algorithms and Data structures
The artifact is a RESTful CRUD API that was written initially in Python, and may be found 
[within the project](./Original%20Artifact/finalProjectPythonFiles.zip) but as apart of this course was 
converted to the artifact into JavaScript.  It was initially created as apart of CS-340 a few semesters ago. 
This new artifact can be found [within the project.](./Algoritms%20and%20Data%20Structures/mongoDbAccessor.zip);

I choose this item because it represented a basic API which I worked on, and saw a lot of room for improvement.  I 
selected JavaScript because in my day to day job I work in TypeScript, which is just different enough from JavaScript 
to pose a real challenge, and I want to learn the under workings of TypeScript.  I was able to convert the artifact to 
JavaScript, and gained some exposure to a slightly different interface to MongoDb.  I also added comments before each 
method that was added so that it is more apparent as to what each method does. 

I learned that it is incredibly important to consider what the real requirements are of your system.  
Initially I was going to use JOI validation to make sure each JavaScript field was present. However, that was not 
necessary because these fields are all non-required fields, the only real required field is passed in in the URL 
parameters.  I also am learning how incredibly useful typing is, as at times it can be ambiguous about what is being 
passed around.

### Databases 
The artifact that I am including is a front end HTML/JavaScript for a mongoDb.  I created it this week for the final project.
This will be an interface for the mongoDb which was created as a part of CS340. This artifact can be found 
[within the project.](./Databases/frontend.zip)

I choose to include this artifact in my portfolio because it continues to show that I have the ability to adapt a previously 
created project, and add a front end onto it in order to best display the information to an end users.  

I have not interfaced with HTML/JavaScript in this manner before.  I found there to be a quite a bit of research in 
order to appropriately map variables (inputs/output) text boxes.  Furthermore, I got some insight on how much customization
HTML really has.  Having not used it before, I didn't realize how important design will be to a project.   The artifact 
that I produced is a white web page with a few text boxes on it.  There is a lot left to be desired as far as a web page 
that customers would pay to use. 