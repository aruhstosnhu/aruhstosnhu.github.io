# Angela Ruhstorfer ePortfolio for Southern New Hampshire University

## Table of Contents

1. Professional Self-Assessment
2. Code Review
3. Enhanced Artifact I: Agile Project Charter and SNHU Travel Webinar Application
4. Enhanced Artifact II: SNHU Zoo Monitoring System Application
5. Enhanced Artifact III: Animal Shelter SQL Database and Datamining

## Professional Self-Assessment

I started my journey in the computer science program at Southern New Hampshire University in May of 2018. While completing my degree, I've come to understand many industries and how they all play a part in the computer science realm. From creating applications in multiple programming languages and understanding operating systems and hardware components, to working through the software development life cycle and reverse engineering, I've truly been able to find my passion for this industry.

As a first generation computer science major, I aim to work in the cyber security field as a technical writer, trainer, and professional services engineer. My passion for documentation and deep understanding of this technology shines in my work, and I want to share this knowledge with others. My career goal is direct: to teach others (both internally in my company, as well as customers) on the fundamentals of the product I support, and how that product can improve their application's quality of life. Teaching my customers as well as fellow engineers best practices and to become self-suffcient in protecting their programs is what inspires me in my career path.

## Code Review

### Artifact I: Software Design and Engineering

<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/M4LQ0I3rGlU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>

### Artifact II: Algorithms and Data Structure

<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/1G0zmqa6UAo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>

### Artifact III: Databases

<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/aDng4rGg-mc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>

## Enhanced Artifact I: Agile Project Charter and SNHU Travel Webinar Application

### Both original and enhanced artifacts can be found in the GitHub Repo [aruhstosnhu/SNHUTravelWebinar](https://github.com/aruhstosnhu/SNHUTravelWebinar)

The artifact I decided to go with for Enhancement One is my “Top 5 Destinations SlideShow” Java application. I also chose to update the application’s project charter. It was originally created in my CS-250 course, Software Development Lifecycle,  in October of 2019. 

### Inclusion

The reason why I chose this artifact is because my enhanced charter will show that I truly understand how to not only create an SDLC program, but also carry it through to completion. I understand these design concepts and can work in a collaborative environment. I also selected this artifact because it had potential for improvement. In my CS-250 course originally, I was not able to successfully add images to my slides and successfully run the application as an executable JAR. The improvements I’ve made in my application show my advancement in my skills and abilities in my software development career.

### Enhancements

- Changed Title of window to be more relevant `setTitle("SNHU Travel Webinar");`
- Edited Text background variable to yellow so it is easier to read `textPane.setBackground(Color.YELLOW);`
- Added 2 additional slides with HTML markdown enhancements (Title and Marketing)
- Added images of actual destinations that display in each individual slide
- Added more in-depth comments within the code to explain the execution of each step in more-detail
- Edited naming of image files used to match the destinations displayed (vs “TestImage”)
- In Marketing slide, added link to Google Sheet that displays pricing chart
- Edited SDLC Charter to include Sales and Marketing team

<p align="center">
  <img width="900" height="400" src="https://user-images.githubusercontent.com/92700885/184548261-351a3273-0fd5-4fdf-9ef3-250fda8e6756.png">
</p>

### Course and Industry Objectives

Enhancement One meets the following CS-499 objectives, specifically:

1. **CS-499-01:**
  - *Does the student demonstrate the ability to provide contextual, in-code comments that result in easily readable and understandable code?*   
Yes, my code includes in-depth and improved comments throughout my application that details what each section does.
  - *Does the student demonstrate the ability to support decision making for software design stakeholders?*   
Yes, my improved project charter shows that I understand and incorporate all departments in decision making when creating software.
  - *Does the student demonstrate the ability to discuss experiences and best practices working in collaborative environments?*   
Yes, my improved project charter shows that I am able to discuss best practices when working in an SDLC SCRUM environment with multiple departments.

2. **CS-499-02:**
  - *Does the student demonstrate the ability to communicate appropriately to specific audiences and contexts?*   
Yes, both my improved code and project charter show that I am able to communicate to the targeted audience of the SNHU Travel Slideshow.
  - *Does the student demonstrate the ability to clearly convey his or her ideas and explain his or her thought process through written, visual, or oral communication?*   
Yes, my improved project charter shows that I understand every corner of the SDLC lifecycle, and how to communicate with non-technical departments.

3. **CS-499-04:**
  - *Does the student demonstrate the ability to use the software development life cycle to create realistic production schedules for software projects?*   
Yes, my updated project chart clearly demonstrates that I understand the SDLC production schedules and how to communicate with departments involved in the creation of an application.
  - *Does the student create more robust and efficient code to deliver value and accomplish industry-specific goals?*   
Yes, my updated code shows that I am able to create a more advanced slideshow with improved images, improved slides, improved background visuals, as well as the ability to connect to links outside of the application.

## Enhanced Artifact II: SNHU Zoo Monitoring System Application and PowerShell Scripting

### Both original and enhanced artifacts can be found in the GitHub Repo [aruhstosnhu/monitoringSystem](https://github.com/aruhstosnhu/monitoringSystem)

The artifact I decided to go with for Enhancement Two is my “Monitoring System” Java application. It was originally created in my IT-145 course, Foundation in Application Development, in March of 2019. 

### Inclusion

The reason why I chose this artifact is because adding the two new methods to convert and generate these CSV reports provides efficiency in reading the data from the Monitoring System. This also automates the task of creating these reports, where before, a Zookeeper would have had to create these reports manually. These methods also expand the complexity since we are providing two brand-new action options for the users to choose from in the Main Menu console.

### Enhancements

- Created two new PowerShell scripts to convert the habitats and animals TXT files into CSV reports:
  - `Generateanimalreport.ps1`
  - `Generatehabitatreport.ps1`
- Created two new Java class methods to execute the PowerShell scripts and print either success or fail:
  - `GenerateAnimalReport.java`
  - `GenerateHabitatReport.java`
- Called to these two methods in my main method to display as choices in the application:
  - `MonitoringSystem.java`
<p align="center">
  <img width="300" height="400" src="https://user-images.githubusercontent.com/92700885/184547527-9f579608-745a-4216-8844-2dad9ccf74be.png">
</p>

### Course and Industry Objectives

Enhancement Two meets the following CS-499 objectives, specifically:

1. **CS-499-01:**
  - *Does the student demonstrate the ability to provide contextual, in-code comments that result in easily readable and understandable code?*   
Yes, my code includes in-depth and improved comments throughout my application that details what each section does.
2. **CS-499-02:**
  - *Does the student demonstrate the ability to communicate appropriately to specific audiences and contexts?*   
Yes, both my improved code and code review video show that I am able to communicate to the targeted audience of the SNHU Zoo Monitoring System. 
  - *Does the student demonstrate the ability to clearly convey his or her ideas and explain his or her thought process through written, visual, or oral communication?*   
Yes, my code review shows that I understand the user’s point-of-view, and how to communicate with non-technical users.
3. **CS-499-03:**
  - *Does the student demonstrate the ability to program solutions to solve logic problems and implement them in software?*   
Yes, by viewing the application as a Zookeeper, I was able to identify the improvements that generating CSV reports would add to the Monitoring System.
4. **CS-499-04:**
  - *Does the student create more robust and efficient code to deliver value and accomplish industry-specific goals?*   
Yes, my updated code shows that I am able to create a more advanced application with improved brand new behavior by generating reports. This also shows I understand how to automate tasks for users to simplify their job requirements (by creating the animal and habitat reports from the PowerShell script).

## Enhanced Artifact III: Animal Shelter SQL Database and Datamining

### Both original and enhanced artifacts can be found in the GitHub Repo [aruhstosnhu/animalShelter](https://github.com/aruhstosnhu/animalShelter)

The artifact I decided to go with for Enhancement Three is creating and data mining my own MySQL database called “animalshelterdb”. This artifact and its supporting items are inspired by the knowledge I gained in my DAD-220 course, Introduction to SQL, and DAT-220 course, Fundamentals of Data Mining.  

### Inclusion

The reason why I chose this artifact is because creating a MySQL database from scratch and querying from it shows that I have mastered category three, databases. The reports I pulled using SOFAstats also show that I understand how to incorporate data mining methods into a database that I created. Lastly, adding the report results and security research document shows that I understand what needs be done from a security-perspective, in order to protect my database.

### Enhancements

- Created `animalshelterdb` MySQL database (provided SQL file)
- Ran multiple queries on `animalshelterdb` database (included in SQL file). For example:
![SQLQuery](https://user-images.githubusercontent.com/92700885/184547251-614f403e-5254-4bcd-9408-4850add61e77.png)
![QueryResults](https://user-images.githubusercontent.com/92700885/184547263-6271a266-bf61-4ec9-92f7-e2a0c43e2918.png)
- Created data mining charts and graphs pulled from the ‘animalshelterdb’ MySQL database using SOFAstats:
  - `ageVSadoption` report
  - `rabiesVSadoption` report
- Created results and research document on best practices regarding database security and maintenance


### Course and Industry Objectives


