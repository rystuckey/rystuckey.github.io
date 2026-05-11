---
layout: essay
type: essay
title: "Software Engineering Beyond Web Application Development"
# All dates must be YYYY-MM-DD format!
date: 2026-05-09
published: true
labels:
  - Software Engineering
  - 
  - 
---
<img width="300px" src="../img/soft.jpg">

## More Than Building Web Pages

When I first started ICS 314, I thought that it was a course that taught us web development and front end development. A lot of the assignments we started with involved tools like React, Next.js, TypeScript, Bootstrap, etc.  These are all standard for web development.  Because of that, I first thought that the main goal of the course was just learning how to build web pages and deploy applications.  However, after working through the course and completing the final project, I realized that software engineering goes much further than just web development.

Software engineering is not only about writing code.  I learned that it focuses on building software in a way that can be understood, maintained, tested, improved, and worked on by multiple people.  In the final project, there was much more work than just writing code to make pages.  We had to organize issues, divide work among teammates, follow coding standards, connect the application to a database, deploy it, and make sure different features worked together.

The final project showed me that web development was one of the parts of software engineering. The specific tools we use vary, but the larger lessons from the course apply to many kinds of software projects. 

## Agile Project Management

One major software engineering concept I learned in ICS 314 was agile project management.  Agile project management is an approach where a team breaks a larger project into smaller tasks and works on them incrementally. Instead of trying to plan the entire project perfectly at the beginning, the team creates smaller issues, completes them, reviews progress, and adjusts as the project develops.

In ICS 314, we practiced this through Issue Driven Project Management.  For our final project, we used GitHub issues, milestones, and project boards to organize our work.  This helped us create structure and give us clear, smaller tasks that were easier to understand.  For example, instead of saying “finish the app,” we had specific issues such as Configure the Landing Page,  Populate the Prisma Database, or Add a Search Bar and its functionality.  This made it easier to divide up the work and focus on specific tasks.

This process was especially useful because our project had many moving parts.  I personally worked on features such as the landing page, the database and its population, rendering data from the database, deploying to vercel, and various fixes of other features.  Without a project management system, it would have been much harder to know what needed to be done, who was responsible for each task, and what still needed to be finished.  Agile project management applies beyond web development because almost any software project can become complicated when multiple people are working on it.  Breaking work into smaller tasks makes progress easier to track. It also makes communication better because the team has a shared understanding of what has been done and what still needs attention.

## Configuration Management and Development Environments

Another important concept from ICS 314 was configuration management.  Configuration management is the process of managing the tools, settings, dependencies, environment variables, and deployment setup that allow software to run correctly.  Before this class, my understanding was that the application should work if the code is written correctly without errors. After working on the final project, I realized that the environment around the code is just as important.

For our final project, we had to work with several parts of the development environment.  We used VS Code for code editing, GitHub for version control, next.js for our framework, Vercel for deployment, Prisma for our database, and many other tools.  Each of these tools had to be configured correctly for the project to work. For example, the application needed the correct database connection, the correct dependencies installed, and the correct deployment settings on Vercel.

One specific example of this from our project was setting up Vercel and connecting it with the Prisma database.  We had to troubleshoot this by going through logs and examining errors to find and address the problems, such as ensuring environment variables are set up correctly and connected to Vercel.  This issue showed me that configuration problems can be frustrating because they are not always caused by the visible code in the page or component.

This was an important lesson because real world applications need to work universally. It might work on the developer environment, but it also has to work for everyone else to be deployed in production.  Configuration management helps prevent problems where code works on one computer but not another.  It creates a more reliable development process because the team can better understand what the software needs in order to run.  Software engineering requires the skills to not only write code, but also to create an environment where the code can be run, tested, and maintained reliably.

## Design Patterns and Coding Standards

Another area that stood out to me was design patterns and coding standards.  Design patterns are reusable ways to organize code and solve common software design problems.  Coding standards are the rules and conventions a team follows so that the codebase stays consistent and readable.  Both concepts are important because software projects become harder to maintain when there is no uniform way to write code.  Design patterns and coding standards apply to almost every kind of software project.  They are important in web apps, mobile apps, games, backend systems, and data tools. These concepts matter because software usually changes over time.  Developers need to add features, fix bugs, and understand old code.  Patterns and standards make that easier because they give the codebase a structure that other people can follow.

In our final project, we used ideas that connect to design patterns even if we were not always thinking about them formally.  For example, our project had some separation between the user interface, application logic, and database layer.  This is an example of the Model-View-Controller design pattern because the database models, page views, and logic were not all written as one giant file.  

Coding standards were also important in our project. We used tools such as ESLint to keep the code more consistent. This mattered because our project was built by a team, not just one person. Consistent formatting and structure made it easier to read each other’s code and understand how different parts of the project worked.

## Conclusion

ICS 314 taught me that software engineering is much broader than web development.  We may have used tools such as React, Next.js, Bootstrap, Prisma, GitHub, and Vercel, but the main lessons were about how to build software in a structured and maintainable way.  The final project made this clear because creating a working application required more than writing pages. It required planning, teamwork, configuration, standards, and design decisions.

Topics such as agile project management, configuration management and development environments, and design patterns and coding standards are useful beyond web applications because every serious software project needs organization, reliable setup, and maintainable code.  I now know that software projects are not just isolated coding tasks, but they are systems that need to be planned, built, tested, deployed, and maintained over time.

AI Note: ChatGPT 5.5 was used for assistance in creating this essay, ranging from generating and suggesting structure, sample drafts and ideas on what to write, and what concepts should be discussed.
