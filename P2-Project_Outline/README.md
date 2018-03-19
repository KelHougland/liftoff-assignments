# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide feedback and direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline, or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/assignments/project-outline/)

## Submission Instructions

### Overview
My project is a training schedule building app. The user will input their immovable scheduled events, such as employment and usual wake time. Once this has been established, they will input goals and how much time they want to spend on them, so they might list that they would like to spend 6 hours a week writing or 3 hours a week working out. The app would then sort through their current schedule and find the needed time in unscheduled areas until the desired time is spread out.

Each event would also be given a priority and descriptor. Events priority would determine if a new event unseated an older event in developing the schedule. The descriptor would influence the size of the chunks that they event is broken into. Something described as practice/development would be split into sections roughly an hour long and spread throughout the week, work/projects would be split into longer chunks.

Ideally, the app would incorporate locations and drive times to adjust for notification times to ensure that user gets to where they need to be from where they are. It should also record whether or not the user logged participation in the event to adjust for future scheduling to improve the likelihood that that they achieve their goals.

### Features
- user login - each user should have their own account and schedule
- notifications - the user should be notified at upcoming scheduled events
- event entry - user should be able to add goals and events into their calendar
- sync - user should be able upload or download events from their google calendar


### Technologies
- C#
- Google calendar API
- Google Maps API (for drive time)
- Something(s) else that I am unaware of and am hoping Ryan can recommend

### What I'll Have to Learn
I am going to have to learn how to incorporate multiple Google API's as well as how to send push notifications to the phone. I will also need to learn some basic weighting/recommendation algorithms to allow the program to adjust to the user's actual behavior.