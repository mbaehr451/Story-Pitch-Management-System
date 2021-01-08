# Story-Pitch-Management-System
### 1-7-2021

## Project Description

The goal of this project was to provide a platform for the submission and editorial approval of story pitches for a publishing company.
Constraints are placed on authors regarding the number of outstanding pitches they may have, which is dynamically dependent on the type of story they are pitching.
Editorial review is multi-staged with numerous checks to ensure the pitch is properly vetted at each stage of approval.

## Technologies Used

Java - version 1.8
JavaLin - version 3.10.1
Angular - version 9.1.13
npm - version 6.14.10
JUnit - version 5.7.0-M1
PostgreSQL - version 42.2.14
Mockito - version 3.0.0

## Features
A user can log in
An author can submit a story pitch
If an author does not have sufficient points the pitch will automatically be placed on hold
An editor can request more information from an author
An author can respond to information requests from editors
An editor can request changes to a story pitch
An author can change details of their story pitch
An assistant genre editor can approve a story pitch and send it for general editor approval
A general editor can approve a story pitch and send it for senior genre editor approval
A senior editor can change story pitch details
An author can accept or reject changes made by the senior genre editor
A senior editor can approve a story, sending it for genre comittee review
Genre editors can approve a story pitch, will require a varying number of editor approvals depending on story type

To-Do:
Pitches which were submitted more than two weeks ago will be labelled high priority
Assistant genre editors must approve or reject high prioirity pitches before moving to low priority ones
The draft will be only viewable by members of the genre comittee and the general editor who approved the pitch



## Getting Started

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.6.
This project was setup to utilize a local PostgreSQL database.
To run the application, first open Eclipse (or other Java IDE) and run the StoryPitchManagementSystemJavalin.java file, then open VS Code and run ng serve throught the Angular CLI
Navigate to http://localhost:4200 to view the application

## Contributor
Mark Baehr