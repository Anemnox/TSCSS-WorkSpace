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
to regulations. Regulations would require more standardization and planning to meet its requirements. Now,
a mixture of AGILE methodologies and plan and document are used to manage software projects.


## SAAS and SOA

Software as a service is the idea to provide functionalities through an exposed API. This was a benefit to
customers because data would be persistent on the server outside of the customer's responsibilities. This
also allowed developers to have a single truth as a source and worry only about one hardware and operating
system environment rather than worrying about compatibility. This would also have the effect of removing
the requirement of supporting multiple systems.

This is in comparison to the shrink wrapped software (SWS) model which includes Client-specific binaries
which would require frequent ugrades based on multiple hardware and operating system versions. SWS models
are difficult to maintain and require extensive compatiblity testing with each release since each environment
has its own implementation of the software.

Designing large SAAS systems became a complex architectual problem that which led to the microservice Architecture.
This would consequentially also make AGILE methodologies to be possible for large systems by dividing business
architecture into smaller services. Amazon was one of the companies that implemented this architecture in which
the focus of development became the externalization of services removing any coupling between microservices.
Each service would be provided specifically through its interface with no back-doors or shared-memory.

Some of the weaknesses of the SOA include the difficulty in debugging and tune the software. Although the services
may be decoupled from outside influences, many of the services are composed together which results in many services
still being reliant on each other and experience system failures even though only partial systems run into issues.

## Cloud Computing

Software as a Service demained 3 main aspects from its infrastructure: communication was required for users to be
able to access the service, it needed to be scalable to allow for the expansion of users, and finally, it needed
to be dependable so that it was available 24/7.

Services were deployed on a network of computers called clusters which were mostly commodity computers connected by
ethernet switches. This was much cheaper than buying specialized mainframes and could be scalable because all that
was necessary to scale this infrastructure was to add more computers to the network. This also meant that there was
a lot of redundancy in the system which could be automated by scripts and reduced the manpower needed to manage the
system.

Companies would set up many of the services through these networks of computers. With an increased use of services,
Amazon had extended its computational equipment to handle a larger capacity of customers. Though, this equipment
was not always used to its full capacity and many times, computers would be there just in case there was
a fluxuation in the demand.

EC2 was released as a service in 2007 which revolutionized the way that people were able to access computational
power. Utility computing allowed for individual developers to be provided with computational power at a much
cheaper cost with the flexibility of being able to scale the usage based on the users of the service. A big
customer of the utility computing service is netflix which generally hosts almost all of its streaming service
on AWS.

Though cloud computing only provides the physical infrastructure for SAAS. Scalibility needs to also be designed
into the software. 


## Legacy Code and Beautiful Code

Many of the software that needs to be maintained is legacy code. Legacy code is continuously required because it
continues to meet customer needs. An example would be the software used by the government which generally is
written in old technology and is continued to be maintained with its old foundations. On the other hand, software
engineers often strive to write beautiful code: code that properly performs its functionality while also being easy
to evolve. Agile techniques can make managing legacy code easier with its focus on embracing change; legacy code can also be beautiful code.

The quality of the software can be benchmarked with a few characteristics: functionality, reliability, usability,
maintainability, efficiency, and portability.



### Notes about Deploying SaaS Apps

- Apps should be either "mobile-friendly" or "Mobile-first"
- Responsive Designing while also considering interactions
- Look over for details on browsers and mobile: [video](https://www.youtube.com/watch?v=nYZ33A1V3Ms&list=PLeMMGxq3FPxjcFZVmvkuc5tW2HtTkqlgP&index=10)
