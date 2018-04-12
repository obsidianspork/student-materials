
# Collabwith.me

## Executive Summary

This document intends to outline the objective, background, scope, functional and personnel requirements, delivery schedule, and other ancillary requirments associated with the project.

In reading this business requirements summary, you will gain an understanding of the objective to create a social network for students to connect with one another, and collaborate on project ideas.

## Business Objectives

The objectives of this project are:

* Create a social network to allow students to collaborate on project ideas
* Drive team collaboration and idea sharing
* Follow-up on student successes and opportunities

## Background

Often times, students are equipped with the skills to develop an application, however they lack an idea to launch off the ground and begin developing. This project aims to help close the gap of idea stagnation, connect the students with one another, and allow them to collaborate and hone their skills.

## Scope

This project will include the follow items:

* The ability to login with an email and password
* The ability to authenticate with social providers (Facebook, GitHub, etc.)

This project does not include:

* An internal, private messaging system

## Functional requirements

The technology stack is as follows:

#### Backend

* Node.js > v8.0
* Express >= v4.0
* MongoDB >= v3.4
* Mongoose >= v4.5

#### Frontend

* React >= v15.0

## Personnel requirements

The personnel requirements are below:

Project Manager - the project manager will lead the project and will coordinate between the various teams, providing weekly check-ins and email updates on the progress of the project.

Lead Developer - this individual will perform code review on major releases and approve those code commits.

Development team - this team of individuals will be responsible for implementing required features and clean the code of any bugs.

Quality Assuarance - this team will perform automated testing and analysis of the codebase, to ensure the application passes integration tests, and pass back to the development team in the event a bug is discovered.

## Delivery schedule

Plase One - During phase one, the minimum viable product (MVP) will roll out, providing students the ability to signup and post their idea.

Phase Two - During phase two, the ability to "follow" a fellow student will be implemented 

Phase Three - During phase three, students will be able to post accomplishments and their own milestones during the project.

## Other requirements

This web application must be able to support all major browsers (Firefox, Chrome, Safari), as well mobile browsers (Android and iOS).

## Assumptions

This project will be reliant on a number of APIs, which at anytime could cause a partial or full disruption in service for students. The APIs are as follows:

* Facebook
* GitHub
* Twitter
* Google+

## Limitations

* Funding 
* Full time employees (time to train, support the MVP, etc.)
* Bugs that arise in production/testing that will require development time to correctly diagnose and repair
* Support for application after initial release

## Risks

* Scope creep
* Resiliency - Third-party APIs may encounter a service interruption, causing issues for systems to operate within nominal limits.
