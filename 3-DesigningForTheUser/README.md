# Designing for a User

> **_NOTE:_**  This content is based off of [lecture 4](http://faculty.washington.edu/wlloyd/courses/tcss360/tcss360_lecture_4.pdf).

Software developers develop software to solve a problem for users, customers,
and stakeholders. This means that the most important consideration when
developing software is to make sure that the needs of the users are met through
the application. This leads us to behavior driven design; what does the user
expect the software to do? how will the user use the software? what is intuitive
for a user when using the software? During development, software developers
should continuously ask these questions and refine the requirements of the
software to match the user's preferences.

## User Stories

User stories is a method for software developers to organize their application
requirements based on the user's needs. They describe how the application is
expected to be used and take place during the plan and document phase of
developing the application. User stories help plan and prioritize the features
for software development. As such, user stories must be testable in the scope of
the application and be small enough to implement in one agile process iteration.
User stories must also add value to the application.

The concept came from the human computer interaction (HCI) community and
originally were written on index cards. They are 1 to 3 sentences that captures
the who, what, and why a feature is requested. The user stories are written in
non-technical language so that customers or developers can write it.

An example:
> examples pulled from the lecture
```
Feature name: [descriptive name]
  As a [kind of stakeholder],
  So that [I can achieve some goal],
  I want to [do some task].
```

```
Feature name: Add a movie to RottenPotatoes
  As a movie fan,
  So that I can share a movie with other movie fans,
  I want to add a movie to the RottenPotatoes database.
```

```
Feature: Add movie tickets to shopping cart
  As a patron,
  So that I can attend a showing of a movie,
  I want to add tickets to my order.
```

Stakeholders can include almost anyone that is relevent to the usage of the
application. User stories are derived from the application's "use-cases".

## Use Cases

Use cases characterizes a scenario for using a system. The goal of use cases is
for the developers to design the system from a user's perspective. This would
mean the developer will want to consider how the system behavior is described in
the user's point of view and what the user can perceive externally.

A good use case will start with a request from an actor to the system (Note:
that actors can be something other than a human user that uses the system). The
use case will end with all of the answers to the requests and be defined by the
interaction of the requests. And, a good use case takes into account the actor's
point of view compared to the system.

>This is sort of like the difference between knowing the behavior of the system
in comparison to the implementation of the system. This is similar to the black
box learning method which you can learn more about through other sources.

Some other qualities
