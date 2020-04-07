# [the_one](https://www.youtube.com/watch?v=oC483DTjRXU)

This is meant to be a FullStack application that showcase my abilities with a
stack and get hired. It should:

## Requirements

1. Solves a complex business problem: it needs to be an app that an IT manager
   can recognize as being valuable to an Enterprise, or ideally one that solves
   a problem an enterprise already has, like the location centralization API for
   GrupoBioRitmo that you never even started.

2. Follows a design pattern: MVC, ReactApp w/ an API, NextJS server-side, etc.
   Pick a good one, follow it and make sure your code is clean and organized.

3. Looks good on web and mobile: People are visually biased, and will assume the
   code behind an application is great if the front is sexy. Use bootstrap with
   a theme/template and make it look sharp af, a professional UI.

- https://getbootstrap.com/
- https://startbootstrap.com/
- https://themes.getbootstrap.com/

4. Has and uses databases, with the right type of database for the job: General
   relational database for your model data, non-relational for notifications and
   such (Mongo) and a redis for queues and jobs. Implement these with an ORM or
   a Querybuilder accordingly.

5. Handles security, authentication and authorization: it must have a robust
   authentication system and ACL. Ideally an authentications that integrates
   with existing api (Google, Facebook, GitHub, etc.). A really cool tool that's
   becoming very popular and it's easy to integrate:

   - https://auth0.com/

## What to build

### A bug/issue tracker

Where tickets that ca be open, closed or categorized as under development. This
allows developers to organize their backlog and for IT managers to track the
problems and productivity. Kinda like TopDesk, Jira, ZenDesk, etc. What's cool
about it is that it can easily become a HelpDesk ticket system, notification
delivery system, field force automation, etc. Once you've got the general
structure you can make it do all sorts of things, and solve all sorts of problems.

Thing is we're already making this exact same thing at Digital House. For now I
should definitely focus on that and make it absolutely great, whilst following
these guidelines.

### Think of another project

That meets the requirements.

## How to build it

1. Write a Software Requirement Specification
   [SRS](https://en.wikipedia.org/wiki/Software_requirements_specification)
   that outlines all of the features and benefits you'd like for that project.

2. Divide those features into one week sprints, where for each sprint we try and
   implement one of those features. It's important to have deadlines for these
   things. All of these should be byte-size components.

3. Keep track of your progress and start checking off the completed features.
   This way you're constantly focusing on what you need to build and not in the
   obstacles and the things you gotta learn to build it. Focus implementing the
   feature for the sprint, not on building the entire thing all at once. Use
   this bug-tracker your building to track and manage your progress in building
   this bug-tracker.

4. Deploy it online and have it hosted for the world to see.
