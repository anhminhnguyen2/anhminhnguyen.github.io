---
layout: essay
type: essay
title: "Good Timing"
# All dates must be YYYY-MM-DD format!
date: 2025-12-13
published: true
labels:
  - Learning
  - Reflection
  - Software Engineering
---

How did you make your effort estimates? Explain your basis and any historical data you used.

Even though your estimates were often off, did estimating in advance provide any benefit? Provide examples.

Was tracking actual effort useful? If so, how did it inform future estimates or project decisions?
How did you track your actual effort (tools, method)? How accurate do you believe your tracking was?
Reflection: what would you change about your estimation or tracking process next time?

Throughout the semester, time-tracking has became a part of my routine for classwork, the in-class WODs, homework, and now the final project. Since I already developed a habit of tracking my time for classwork from the beginning, having to track my progress and task during the final project was just a part of my routine.

## Estimation time

Usually I would want to over estimate my actual time for the issue, so that whenever I plan on working on the project, I would carve out a bigger chunk of time to avoid any other conflict it may have with my schedule or plans. Thankfully, I have been able to work on the issues at the end of the day or when I do not have anything planned to worry after. To me, estimation is a way for future me to plan ahead the time to work and focus on the project.

Overtime, my estimation got better, since I understand the issue, its requirements, and what I need to do for it. Since with the help with AI in the project, one mistake that I usually make is overestimate the time AI takes to help me, especially with GitHub Copilot. Before the project, I used ChatGPT to assist me during the WODs, so it took longer to think about prompting and giving it the context of my code (such as how different files are connected to each other in which ways), but with GitHub Copilot, the agent could iterate through my whole repo and give me direct answer without me needing to prompt much. 
 

------------------------------------

## Coding/Non-coding time

A really useful and important file in our website's program is the **dbAction.ts**. This acts like the "middle man" between the UI components and the database. This file provides a layer of protection and convinience when the components are trying to talk and fetch data from the database's tables. These components do not "know" if the website is using MongoDB or Prisma or PostgreSQL, the only know that they call a function, such as CreateUser for the Sign Up page. This means that if the group switches to another database later on, we only need to rewrite and adjust the dbAction.ts file, not all the UI elements on the pages, making these interface components reusable despite the changes in database. This extra layer of security can be also seen as the bridge between the two different aspect of the website, ensuring that these queries never run on the browser directly, only on the secure server of the group.

In the context of LEGO building, I see this pattern as the LEGO Friction Ridge that are usually seen and used in Mechanic and Technic sets as well as robots in Robotic Competition. This piece is the the "glue" of a set, where it helps connects different parts together. If one of the part needs adjustment, the builder can simply remove that single piece connected by the Friction Ridge without taking apart the entire model. In this same way, the dbAction.ts serves as the connection between the interface and the database, and if either of these change, developers/editors only need to change the "bridge".

<div class="text-center p-4">
  <img width="500px" src="../img/lego-technic-pin-with-short-friction-ridges-2780-61332-1762437.jpg" class="img-thumbnail" >
</div>

## Conclusion

Through the Manoa RoomieMatch project, I learned and understood that design patterns are reusable components and solutions to common issues or problem that usually come up in web development. By applying these patterns, the structure of the website is broken down to be more organized, easier to understood, adjusted, and maintained, especially when the project is shared among a group of people. Understanding and recognizing these patterns helped me to be more aware of the website's stucture and functionality, as this knowledge will help me to develop cleaner, more scalable, and better for future improvements of Manoa RoomieMatch.




