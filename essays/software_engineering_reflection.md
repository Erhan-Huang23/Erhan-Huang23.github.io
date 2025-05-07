---
layout: essay
type: essay
title: "A Reflection on Software Engineering"
# All dates must be YYYY-MM-DD format!
date: 2025-05-06
published: true
labels:
  - sofeware Engineering
  - TypeScript
---

# Beyond the Browser: A Reflection on Software Engineering

When I first enrolled in ICS 314, I expected a course primarily focused on web application development—learning tools like React, MongoDB, and Meteor to build interactive websites. While I certainly developed those skills, I quickly realized that the deeper value of this class was in understanding core software engineering principles that extend far beyond front-end development. In this essay, I will reflect on three of these principles—Agile Project Management, Configuration Management, and Design P...

## Agile Project Management and Issue Driven Project Management

Agile Project Management is a methodology that emphasizes flexibility, collaboration, and iterative development. Instead of building an entire software system in one go, Agile breaks the process into manageable cycles called “sprints,” allowing teams to adapt to changing requirements and continuously integrate feedback. This style of management is particularly useful when the end goals are not fully defined at the start, or when the project is expected to evolve during development.

In ICS 314, we learned a specific style of Agile called *Issue Driven Project Management (IDPM)*. This approach revolves around GitHub Issues—each feature, bug fix, or task is tracked through a detailed issue that is assigned to a specific developer and linked to corresponding code through branches and pull requests. This made our team collaboration highly organized and traceable, with each person’s contributions clearly documented.

I can absolutely see myself using IDPM in projects outside of web development. For example, if I were part of a team building a mobile app or a machine learning model, using GitHub Issues to assign tasks, track progress, and document discussions would still be highly effective. The underlying principle—breaking work into focused, actionable tasks and aligning them with source control—applies universally to team-based software projects.

## Configuration Management

Before ICS 314, I had a vague understanding of how development environments could “break” depending on operating systems or software versions. This course made me realize that *configuration management* is the systematic process of handling changes to software environments to maintain consistency across development, testing, and production stages.

In practical terms, configuration management involves tools and practices that ensure that all team members are using compatible versions of libraries, runtime environments, and deployment settings. For instance, using `.env` files for sensitive data, committing `package-lock.json` to preserve dependency versions, and setting up project-wide ESLint configurations are all part of configuration management.

Beyond web development, configuration management is vital for large-scale projects like embedded systems, server-side applications, or DevOps pipelines. It ensures that the code that runs on a developer's laptop behaves the same way in staging and production environments. Without it, teams risk inconsistent behavior, security issues, and long debugging sessions due to “it works on my machine” problems.

## Design Patterns

Another major takeaway from this course was the concept of *design patterns*. A design pattern is a general, reusable solution to a common software design problem. It is not a finished design that can be turned into code directly, but rather a template that can be applied to various situations.

One design pattern we encountered was the *Observer Pattern*, commonly used in UI frameworks like React. In React, the component “observes” state, and when the state changes, the UI re-renders. This concept is not limited to React or front-end frameworks. In desktop applications, robotics software, or even game engines, you can use the Observer Pattern to ensure systems respond dynamically to state changes without tightly coupling components.

Learning about design patterns has given me a more structured way to think about building software systems. Rather than inventing new solutions from scratch, I now see the value in applying tested approaches to recurring challenges—whether I’m developing a chatbot, managing hardware interfaces, or designing microservices.

## Conclusion

ICS 314 provided me with much more than a set of tools for web application development. Through Agile Project Management, Configuration Management, and Design Patterns, I’ve learned principles that are foundational to software engineering as a whole. These practices promote scalable, maintainable, and collaborative software development, and I now feel better equipped to handle a wide range of technical challenges, no matter what the project domain may be.
