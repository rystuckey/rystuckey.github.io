---
layout: essay
type: essay
title: "Effort Estimating for Final Project"
# All dates must be YYYY-MM-DD format!
date: 2026-05-04
published: true
labels:
  - Effort Estimation
---
<img width="300px" src="../img/clock.jpg">

## Effort Estimate Basis

For our ICS 314 final project, my team used issue-driven project management to divide our project into smaller tasks and estimate how much effort each task would take.  Our project, Manoa CourseWise, involved multiple features such as course pages, professor pages, user login and registration, database setup, course search, reviews, and deployment. Because of this, effort estimation was useful because it forced us to think about each issue as its own task instead of looking at the whole project as one large assignment.  My own work focused mostly on deployment, configuring pages, connecting parts of the application to real data, database population, and making certain courses reviewable. Some of the issues I worked on included deploying the application to Vercel, configuring the project landing page, configuring the login and registration page, creating and populating the database, giving course search and course detail pages read access to the database, populating the database with Math courses, fixing the landing page to use real data, and making Math classes reviewable. 

The estimates were made by looking at how complex each issue seemed and comparing it to similar work we had already done in class or earlier in the project.  For example, configuring the login and registration page was estimated at 60 minutes because it was a familiar type of page-building task.  On the other hand, populating the database from the Mānoa Course Catalog was estimated at 180 minutes because it involved more uncertainty, data handling, and checking that the course information worked correctly in the project.

Not every estimate was made by me directly.  Some estimates for my issues were created by teammates while I was focused on other parts of the project. However, the estimates generally reflected what the team thought the difficulty of each issue would be at the time. Page configuration tasks were usually estimated lower because we had already done similar frontend work in ICS 314. Database and deployment tasks were estimated higher because they had more unknowns and could lead to unexpected problems.

## Tracking Coding and Non-Coding Effort

One thing I noticed from the effort report is that software development requires much more than just coding. For the issues I implemented, my coding effort was about 270 minutes, while my non-coding effort was about 460 minutes. This may be because a lot of my tasks involved setup, research, testing, understanding the database structure, checking whether data appeared correctly, and making sure the application worked after changes were made.

This was shown in my tasks related to deployment and database creation and management. Deploying to Vercel, connecting pages to real data, and populating the database all required more non-coding effort. They required checking configuration, understanding how the application was structured, and testing whether the result worked correctly. In that way, tracking non-coding effort was useful because it showed that a large part of the project was spent on the supporting work around the code.

Our effort tracking was useful, but it was not perfect. Some time was easier to track because it happened directly while coding or working on a specific issue. Other time was harder to track because it involved thinking through the problem, checking project behavior, communicating with teammates, or coming back to an issue later. Because of that, I would describe our effort tracking as a reasonable approximation rather than a perfect measurement of every minute spent.

## Going Forward with Effort Estimation

Next time, I think it would be good to streamline our process for effort estimation rather than doing it all manually. I would use a tool like WakaTime for coding effort and a simple timer, spreadsheet, or issue comment log for non-coding effort. This would make the final data more accurate and make it easier to reflect on exactly how much time was spent on each part of the work.

Another thing I would change is separating coding and non-coding time more clearly while working. Sometimes research, debugging, testing, and coding blend together, especially when working on database or deployment issues. In the future, I would try to pause and record what kind of work I was doing so the final effort report would be more accurate.

## Reflection of AI Use

For this project, I used GitHub Copilot for AI assistance during this project.  For Coding Effort, I used it to help generate and refactor code to help with the overall creation and design of the project.  I would use it for creating specific areas of my project for me, using prompts such as "Add functionality to this link so that it takes you to X page" or "Style this page with our master style sheet and overall theme".  I would also use it for non coding effort such as setting up Primsa databases or Vercel deployment.  I would prompt it in ways such as giving it a list of data and say "populate the database with this data" or give it logs on why Vercel deployment is failing and have it diagnose the proble.

For this Essay, ChatGPT 5.5 was used for planning the essay, summarizing requirements, and generating ideas and sample content for a first draft, which was later edited and expanded upon.

