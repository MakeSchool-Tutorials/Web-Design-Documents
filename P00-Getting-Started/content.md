---
title: "Web Design Documents"
slug: web-design-documents
---

A _Design Document_ (DD) is meant to detail the purpose, interface, technical requirements, and development milestones for your web app. It is a _living document_. You should be consistently updating your design document throughout development. If you are not updating your design document at least twice a week, then you are falling behind!

Having a completed design document makes it much easier to visualize your progress throughout development and keep track of what you have accomplished. It will help you make the correct decisions if you need to cut features because you are behind schedule, or add features because you are ahead of schedule. Whenever you decide to change some aspect of your web app's design or development schedule, make sure to update your design document!

# Your first design document

We will be writing a Design Document for our hackathon projects and personal projects to keep our development on track

> [action]
> Log into [GitHub](http://github.com) and create a new repository titled after the web app you are writing a design document for. You can use your completed web app repository if you have been using git/SourceTree/GitHub already!
>
> When viewing the new repository, there will be a link in the top bar that says "Wiki". Click on that and create a new page titled "Design Document"
>
> We're going to be editing our Design Document in Markdown format, which is a very simple format that looks good both in plain-text and rendered. You can read more about Markdown formatting [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).
>
> Copy and paste this into the new page:
>
```
# My Web App Name
[1-2 sentence description of the web app]
​
## Audience
[Who cares/uses it? why?]
​
## Experience
A user opens the web app... [complete this thought]
​
# Technical
## Models
[What data are we dealing with? What classes will we create for that data?]
​
## Views
[What custom views do we need to create? Include pictures of your prototypes/sketches!]
​
## Routes
[What routes will we need? What will they do?]
​
## Other
[Any other frameworks / things we will need? Helpers? Services?]
​
# Weekly Milestone
## Week 4 - Usable Build
[List of tasks needed to be complete before you can start user testing]
- task 1
- task 2
- task 3
- [...]
​
## Week 5 - Finish Features
[List of tasks to complete the implementation of features]
- task 1
- task 2
- task 3
- [...]
​
## Week 6 - Polish
[List of tasks needed to polish and launch on a live server]
- task 1
- task 2
- task 3
- [...]
```

Time to start writing your app design document!

# App Design Documents

We'll be breaking down how to fill out each section of your design document below. Use this as a basis for making your own. You can reference a completed Web Design Document [here](https://github.com/MakeSchool-Tutorials/Web-Design-Documents/wiki/Sample-Web-Design-Document).

## Introduction

Explain your app idea and purpose in 1-2 sentences.

## Audience

This is where you explain who you expect to use your web app. What age range, interests, background, etc characterize the users you expect? In what circumstances during the day will they use your web app? You want to answer the questions "Who cares?" and "Why?".

## Experience

Start by describing, almost like you are telling a story, how a typical user will interact with your web app. Why will they choose to open it? What will they do when it is open? What is the benefit or outcome of using it, and what should they feel when using it?

You can write these user stories following this format:
> A user opens the web app when `<they have some problem>`, and they `<do something to fix the problem>`.

Here's some examples from Snapchat:
> A user opens the web app when they want to share an experience, and they send direct "snaps" or post to their "stories" so they can share the experience with friends.

Some of your apps will have more complex features in addition to the core feature. In this case, you might have a second example in your Experience section.
> A power user opens the web app throughout the day, and they use it to keep up to date on what their friends are doing and keep in touch with others through a combination of "snaps" and "stories". Power users keep closer tabs on how their posts are doing, who and how many people watch their stories.

# Technical

This is where we start to break down the architecture of your web app.

## Models

Describe the data your web app creates and interacts with. What classes will you create for that data and what properties will those classes have? This is where you start to define the models for the data that gets stored in Mongo, or passed around the app as a user uses it.

This works best as a list with nested items to describe properties of the class.

## Views

List all the views you will need to create for your web app. Once you finish some design sketches showing how your web app will look, you should also upload them to this section.

## Routes

What routes will your web app need? In general, you are going to have one controller per view/screen the user sees.

## Other

What APIs or external services will you use when making your web app? List them and any alternatives you may need to check out here. What about custom helpers and services?

# Weekly Milestones

This is the section that should get updated the most often. You will be keeping track of what tasks you plan on completing each week. If you're new to projects this long, you will have to make best guesses as to how long things will take.

Before ordering your tasks on a week by week basis, first list every task on your plate. This should include everything you've listed in your web design document that will be in your MVP and all the non-technical work your web app requires.

For every task, you may want to estimate how many days it will take. If you think it will take less than half a day, round up to a half day.

Add all the days together. Multiply by 1.2 to give yourself buffer time for unexpected delays. If you end up with more than 15 days of estimated tasks, do not change your estimates. Unless you have significant experience with large projects you should almost never change your estimates to be more optimistic. It is a big red flag if your gut tells you a task will take `N` days but after thinking about it you decide it won't take as long. You're almost always wrong.

If you have more than 15 days of work left, cut features. If it doesn't hurt, you aren't cutting enough features. Revise your design document if necessary once you make significant changes to your web app's design.

Only once you have a list of tasks that fit in 15 days should you start dividing them up week by week. Your goal is to be at a user testable state by the end of week 4 (one week of development), finish implementing *ALL* of your features by the end of week 5 (two weeks of dev), and finish polish + launch to server by the end of week 6.

# Wrapping Up

Read your design document over to make sure everything makes sense. Check dependencies -- tasks should be in order of completion! Edit as necessary.

You should be keeping this up to date throughout the entire development process. Check it daily, update it at least twice a week. I like to check it before stand ups and update it on Monday's and Wednesday's.
