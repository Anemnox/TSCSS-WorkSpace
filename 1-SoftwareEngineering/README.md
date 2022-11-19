# What is Software Engineering?

> **_NOTE:_**  This content comes from these [slides](http://faculty.washington.edu/wlloyd/courses/tcss360/tcss360_lecture_1.pdf). Much of the content is paraphrased from the lecture.

There is a difference between a software engineer and a programmer. A software engineer
has more thorough understanding of designing, creating, and  maintaining software systems
while also understanding the concepts behind hardware in systems design. On the other hand,
a programmer has a lower bar to fulfill; they need to understand how to write instructions
on the computer to solve problems. Why is this difference important?

Developing software is more than typing in code into a computer; at scale, more people are
involved to create larger systems with extensive requirements. This led to standards in the
development process and different ideas in how software should be developed. There needed
to be a way to make software more predictable.

### The Waterfall Method

Software engineers looked for ways to make software development as predictable in quality, cost
and time as civil engineering. Software projects started with a plan and documenting phase where
the project manager would write detailed documentation on the architecture and requirements for
the project. One of the timelines for this process is known as the waterfall method; the project
was planned from start to finish with a timeline of around 6-18 months. The process would start with
an analysis of the requirements, the architecture would be planned, implementation/integration,
verification/testing, and finally operation and maintenance would be required.

### The Spiral Method

The spiral method was an alternative method to planning and documenting a software project. Each
milestone would be a working build for the software which would lead to another milestone in the
future that would be determined based on objectives and constraints for the software. This cycle
of determining objects to building a prototype and verifying it was the spiral method.

### Overview

The plan and document process depended on high-quality project managers for it to be possible. Project
managers needed to recruit the team, document the project plan, estimate logistics, and manage the team.
This had the pitfall of requiring experienced managers, extensive planning, and extensive documentation.
People started to look for a different strategy for software projects.

## The Agile Software Process

The Agile lifecycle originated from the AGILE manifesto which outlined a radical new way of developing
software projects. The core idea was to respond to changes rather than following a plan. This means that
it would value customer collaboration, working software, and individuals/interactions rather than contract
negotiations, comprehensive documentation, and processes/tools. The AGILE lifecycle embraced the idea of
continuous change (integration) vs phases. Developers would continuously refine working but incomplete
prototypes until the customer was happy with each iteration. This allowed for the continuous step by step
improvement of a product with feedback from the customer compared to resulting in a complete project that
may not be what the customer wanted. This addressed some of the problems with plan and document style of
development.

However, there were still some drawbacks to the AGILE Method such as when software development was subject
to regulations. So now, there is a mixture of AGILE methodologies and plan and document style of developing
code.

## SAAS and SOA

Software as a service is the idea to provide functionalities through an exposed API. This was a benefit to
customers because data would be persistent on the server outside of the customer's responsibilities. This
also allowed developers to worry only about one hardware and operating system environment rather than
worrying about compatibility. This would also have the effect of removing the requirement of upgrading
for multiple systems.
