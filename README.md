# CMPG 323 Project 4 - User Acceptance Testing with UiPath
## Project Overview
In this project, I focused on automating the User Acceptance Testing (UAT) process for a web application using UiPath. UAT is an important phase in the development lifecycle where users verify that the solution provides the expected output based on their inputs. Since manual UAT can be repetitive and time-consuming, I used Robotic Process Automation (RPA) to streamline the testing process.

The web application I used for this project is the NWU Tech Trends Telemetry Portal, which allows the creation of new records. The repetitive nature of testing the input validation inspired me to automate the process with UiPath. The goal of my automation was to pull test data from an Excel sheet, input it into the application, validate the output, and record the test results automatically.

### Prerequisites
Before I began the project, I made sure the following were ready:

I created a UiPath Automation Cloud account.
I installed UiPath Studio Community Edition.
I ensured access to the NWU Tech Trends Telemetry Portal.
I prepared an Excel file containing test data for input.

### Implementation Process
#### GitHub Administration

- Create Repository: I set up a GitHub repository called CMPG 323 Project 4 - [My Student Number] to manage the project.
- ReadMe.md File: This file contains an explanation of the project and steps to use the developed bot.
- Version Control: Throughout the project, I regularly committed and pushed changes to the repository to track progress and updates.
  
#### Project Setup

- Clone Repository: I cloned the GitHub repository to my local machine.
- Install UiPath: I ensured that UiPath Studio was installed and set up for the automation process.
- Create New Process: I created a new process in UiPath Studio named NWU Tech Trends Telemetry Portal - User Acceptance Testing.

### User Acceptance Testing
#### Read Input Data:

I used UiPath to load the test data from an Excel sheet into a data table.
I verified that the data was readable and ensured it could be iterated over.

#### UI Automation:
For each record in the Excel sheet, I navigated to the NWU Tech Trends Telemetry Portal's web page and inputted the data into the required fields.
I automated the process of filling out the form using values from the data table.
After submitting the form, I checked if the new record was successfully created.

#### Project Close-out
- Deploy Solution: I published the UiPath automation to the UiPath Orchestrator, making it ready for use.
- Documentation: I ensured that this README file contains clear instructions on how to use the automation solution, and I included a reference list of resources used throughout the project.
