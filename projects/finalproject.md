---
layout: project
type: project
image: img/soft.jpg
title: "Manoa CourseWise"
date: 5/9/26
published: True
labels:
  - React
  - Next.js
summary: "Final Project for ICS 314."
---

<img style="width: 300px height: 300px object-fit: cover src="../img/soft.jpg>

# Manoa CourseWise

Manoa CourseWise is a course review application built for UH Manoa students. The goal of the project was to give students a more useful way to search for courses, view course and professor information, and read student feedback before deciding what classes to take. The application includes a landing page, course search, course detail pages, professor/course data, review metrics, tags, authentication, and a protected review submission page.

The app was built as a team project for ICS 314 using Next.js, React, TypeScript, Prisma, PostgreSQL, Bootstrap, GitHub, and Vercel. The project uses a database structure with users, courses, professors, reviews, and saved courses. Course pages display review data such as rating, difficulty, workload, clarity, common feedback tags, and written student reviews. Students can also submit their own reviews with course/professor selection, semester taken, difficulty, workload, clarity, written feedback, tags, and an anonymous posting option.

My main contributions focused on deployment, database work, and connecting the application to real data. I worked on deploying the application to Vercel, configuring the landing page, setting up the login and registration page, creating and populating the course/professor database, and connecting the course search and course detail pages to database-backed data. I also worked on adding Math courses to the database, making the landing page use real data, and supporting review functionality for Math classes. Later in the project, I also helped with review-related fixes, including supporting all departments in the submit review page and resolving a Vercel TypeScript/session typing issue.

One of the biggest things I learned from this project is that a working software application involves much more than just writing frontend pages. Some of the most important work happened around the code: database modeling, deployment configuration, authentication, testing whether pages used real data correctly, and making sure the app worked in production. For example, connecting a page to the database required understanding the Prisma schema, the API routes, the frontend component, and how the deployed environment handled the database connection.

This project also helped me understand team-based software engineering more clearly. Since multiple people were working on different features, we had to divide the project into GitHub issues, coordinate who was responsible for each part, and make sure our work fit together. The project made concepts like issue-driven project management, coding standards, configuration management, and deployment feel much more practical. By the end, I had a stronger understanding of how a full-stack web application is planned, implemented, deployed, and maintained.

Source code: https://github.com/manoa-coursewise/manoa-course-wise  
Deployed application: https://manoa-course-wise.vercel.app/
