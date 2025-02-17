---
layout: page
title: Consultancy - Development
type: project
---

We will be using an Agile process during the development of this project. This will include:

* Working in short 3 or 4 day "Sprints"
* Using GitHub
* Setting up Continuous Integration and Continuous Deployment
* Using a project management tool such as Github Projects
* Conducting Story Grooming meetings
* Doing daily Stand Ups
* Demoing your project to your Project Manager
* Holding Team Retros


## Sprints

In Agile processes, a sprint is a single cycle of development. The most common length of a sprint is two weeks. During this cycle, teams will assign features, develop those features, demo their work, get feedback, and retro.



#### Sprint 1: User Interface and Database Planning Spike

- Begin: Monday of Week 4
- End: Thursday morning of Week 4

Day 1:
- Your group should split your team up to focus on each area of the project.
  - Front-end team
  - Back-end team
  - Documentation/Planning team
    - For teams of 6 this will be a team of two. The team of 5 will have one person on this.

- Each team will use a Miro board to brainstorm ideas
- Delegate people to set up a GitHub organization, add other members, and set up the initial repos

- Deliverables:
  - Wireframes of the User Interface
  - Rough implementation and testing of the front-end, mocking out responses from back-end; no authentication expected yet
  - Rough implementation and testing of back-end API, mocking requests from front-end
  - Initial structure of each Service (not necessarily working API calls)
  - Circle-CI and Deployment to Heroku for both FE/BE repositories

#### Sprint 2: Primary Development

- Begin: Thursday afternoon of Week 4
- End: Monday morning of Week 5

- Deliverables:
  - Frontend has Bootstrap in place, each wireframe is implemented in some amount, implements OAuth, can CRUD data with backend
  - Rails back-end can CRUD resources based on front-end requests
  - Services successfully implement their respective API calls

#### Sprint 3: Final Product

- Begin: Monday Afternoon Week 5
- End: Friday Week 5
- Deliverables:
  - Professional-looking front-end
  - MVP for each component is met
  - Fully working application stack is presentable

## Project Check Ins

In addition to the End of Sprint Demos, you will also have some project check ins

* Check In 1
    * Wednesday or Thursday of Week 4
    * During this meeting, you should be prepared to review the artifacts from your inception: MVP, wireframes, story board.
    * During this meeting, your team will draw out the architecture of your application

* Check In 2
    * Monday Week 5
    * During this check in, you will discuss with your project manager what the expectations are for your final demo on Friday
    * You can also use this check in as an opportunity to ask any questions and get help for the final few days of the project.

* Check In 3
    * Review of near-final work, check for MVP
    * Discuss presentation details

## git/GitHub

* Commit Frequently
* Decide on a [git workflow](https://www.atlassian.com/git/tutorials/comparing-workflows)
* Make branches and submit Pull Requests for each new feature.
    * DO NOT commit directly to main
    * Keep your PRs as small as possible (one feature / user story per PR)
    * Use screenshots and screencasts to demonstrate functionality.
    * Your PR should be reviewed by at least one team member before it is merged.
    * Tag your Project Manager if you have questions. DM your Project Manager letting them know you have tagged them.


## Continuous Integration

* Set up a [CI Server](https://backend.turing.edu/module3/archive/lessons/environments_and_ci)
* [CircleCI Docs](https://circleci.com/docs/2.0/)


## Continuous Deployment

* Set up Circle-CI in such a way that it automatically deploys its code to Heroku when 'main' branch code is passing

## Story Grooming

* You should be using a project management tool to keep track of your stories.
* When doing a "Story Grooming" you should:
    * Make sure that the project board is up to date
    * Look over the current backlog of stories and decide if you want to make any changes
        * Are there any stories that need to be updated?
        * Are there any stories that need to be added?
    * Assign stories to individual team members or pairs
        * Be clear on what it is that everyone should be doing
* You should be Story Grooming every 1-2 days.

## Daily Stand Ups

* A Stand Up is a very brief (hence, physically standing up) meeting for the development team to keep in touch about what everyone is doing.
* During the stand up, each member of the team will take 1 - 2 minutes to answer these questions:
    * What have you been working on?
    * What are you going to be working on?
    * Is anything blocking you?
* Every weekday you should send your PM a summary of the day's stand up.

## Retros

* **End of Week 1**
    * Students should discuss what went well, what didn't go well, and what they would like to change for the second half of the project. Students should use their DTR as a guideline for this discussion and be willing to reaffirm or change any expectations that weren't met in the first week.
* **End of Project**
    * Students should discuss what went well, what didn't go well, and what feedback they have for their team members using [this template](https://docs.google.com/spreadsheets/d/1MDybiSiZLVdbpbwEU-x_VPakyhhX0lD4HhcCjwuxtc4/edit#gid=0). Each group should make a copy of the template and submit to their instructors.
