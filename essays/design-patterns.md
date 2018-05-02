---
layout: essay
type: essay
title: Design Patterns
# All dates must be YYYY-MM-DD format!
date: 2018-05-01
labels:
  - Code Standardization
  - Software Engineering
---

## Rondo vs. Sonata 

Almost all music composition today fits to one of many standard forms where certain melodies or themes repeat themselves in a particular order. The Rondo is one such form where the pattern of three discrete themes, A B and C are played in the order ABACA, or ABACADA. The Sonata Form is another where larger ideas take shape starting with the "Exposition" (A then B), a "Development" completely separate from the other themes, and "Recapitulation" (revisiting A and B). Both cases represent style patterns and rules for music composition, much like how in poetry a sonnet or a haiku have certain rules that achieve a desired effect. In the world of coding, design patterns achieve a similar effect. Design patterns are reusable solutions to a commonly occurring challenge or problem in software engineering. Just like a musical form doesn't write the composition itself, design patterns don't directly translate into code. Instead they are just a description of a way to solve the problem, often written in pseudocode.

## Learning Meteor.js

I recently learned how to use the Meteor.js framework with React.js using Philip Johnson's <a href='https://ics-software-engineering.github.io/meteor-application-template-react/'>meteor-application-template-react</a>. Upon examining his techniques on achieving certain features such as rendering a dynamic page, I developed certain design patterns of my own that I've used in my own projects. For example in one of my current projects, a stack-overflow style forum for my college's computer science department, I had to create a page that renders a course homepage grabbing its course details from a database. I sent the course `_id` in the url params to the course page and then used it to grab the info from the database. Eventually I figured I could do the same for each question page on the site as well. I eventually used this techniques in other projects such as a website for a talent management agency I work for where I render profile pages and categorized rosters the same way. This most basic design pattern illustrates an effective solution to a problem I come across a lot in my projects. Surely I could've implemented this a different way each time, but having a proven design pattern ensures success every time.

## Subconscious Design

Most of the time I find that I use design patterns unknowingly. When I see a similar problem over and over again I find that I slowly develop and refine a corresponding design pattern. In grade school, learning the process of doing long division is also a kind of design pattern. If design patterns occur naturally, are they worth identifying and writing down? I believe they are, because they can be shared. Sharing design patterns amongst each other and not having to "re-invent the wheel" allows the pattern to be improved upon again and again starting where another left off. This is where I find the most value in design patterns, portability.