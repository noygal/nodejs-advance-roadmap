### Fullstack Node.js

#### Node.js in the wild

---
@title[Introduction]

### State of affaires

In the last few years Node.js matured and became the "goto" platform Fromm startups to enterprises everyone want to use and adopt this new(?) technology.

Note:
Examples: ADP - Lifion, Pepper, microsoft chakra engine.

+++

Open source and the [the unix philosophy](https://en.wikipedia.org/wiki/Unix_philosophy) - do one thing and do it well, are the pillars of Node.js and its ecosystem.

Note:
Stdio stream as communication channels, Node.js vs io.js

+++

The amount and availability of free and open source code, frameworks, tools and addon for Node.js ecosystem is unparalleled to any development platform that came before.

+++

A good Node.js developer knows how to choose the right solution from the wide array of existing solutions, a smart developer knows how to write his own solution from scratch, and the wise knows when to not to use Node.js at all...

Note:
Examples: Picking the right frameworks/libraries long lasting impact, using Node.js or nginx for proxy, "half a day of work" vs adding dependencies, how to use Node.js with other platforms (cli, node-gyp binding, etc')

+++

<a href="http://www.azquotes.com/quote/267248" title="William Shakespeare quote"><img src="http://www.azquotes.com/picture-quotes/quote-a-fool-thinks-himself-to-be-wise-but-a-wise-man-knows-himself-to-be-a-fool-william-shakespeare-26-72-48.jpg" alt="A fool thinks himself to be wise, but a wise man knows himself to be a fool. - William Shakespeare"></a>

Always keep on learning.

---

@title[TOC]

### Fullstack Skills

@ul

- Large scale code design
- High level system architecture
- Knowledge of leading JS libraries and frameworks
- SaaS solutions - pros and cons
- Devops tools and workflows

@ulend

---

@title[Code design]

### Code design

Javascript was developed in 1995 by Netscape under two week to serve as a "glue language" embedded inside HTML pages. It had many engines and conflicting standards in its early days, the missing parts were filled by polyfills or other intermediate languages, the best ones found there way back to the language (Promises, coffeescript, async/await, etc').

+++

As a multi-paradigm language, JavaScript supports event-driven, functional, and imperative (including object-oriented and prototype-based) programming styles [*](https://en.wikipedia.org/wiki/JavaScript).

+++

The true power of javascript is the ability to write multi-paradigm code effortlessly, taking the best part of each paradigm would lead to better code, ALWAYS choose the simpler solution NOT the "correct" one!

+++

Code styles/paradigms comes and goes, in the long run it is better to try out new approaches some will stick.

+++

And remember even if you don't like code style/paradigm you still need to know how to read and use it.

+++

<a href="http://www.azquotes.com/quote/765126" title="Alan Perlis quote"><img src="http://www.azquotes.com/picture-quotes/quote-a-language-that-doesn-t-affect-the-way-you-think-about-programming-is-not-worth-knowing-alan-perlis-76-51-26.jpg" alt="A language that doesn't affect the way you think about programming is not worth knowing. - Alan Perlis"></a>

+++

### Code maintenance

<a href="http://www.azquotes.com/quote/803741" title="Douglas Crockford quote"><img src="http://www.azquotes.com/picture-quotes/quote-javascript-is-the-only-language-that-i-m-aware-of-that-people-feel-they-don-t-need-to-douglas-crockford-80-37-41.jpg" alt="JavaScript is the only language that I'm aware of that people feel they don't need to learn before they start using it. - Douglas Crockford"></a> 

---

@title[Architecture]

### Software Architecture

Architecture Characteristics - [definitions](https://en.wikipedia.org/wiki/Software_architecture#Characteristics)

@ul

- Multitude of stakeholders
- Separation of concerns
- Quality-driven
- Recurring styles
- Conceptual integrity - [Conway's law](https://en.wikipedia.org/wiki/Conway%27s_law

@ulend

Note:
Example stakeholders: security team, dev teams, qa team, backoffice(analytics)

+++

Most modern solutions implement to some extent SOA [(Service-oriented architecture)](https://en.wikipedia.org/wiki/Service-oriented_architecture), so the system level design mandatory for seniority.

Note:
In monolithic design SOA problems become software problems

+++

Software Architecture is hard to master, learned mainly by mistakes - but you don't have to make them yourself 😁

---

### Architecture - Components

@ul

- RESTful domain/business service/microservice
- Messaging/Queue - RabbitMQ, kafka, activeMQ
- DB -  MongoDB, Redis, PostgreSQL, Elasticsearch
- load balancer - nginx, HAProxy, Amazon ELB
- Big data - Hadoop/Hive/Presto
- Gateway / backend for frontend

@ulend

Note:
Services Examples: auth services, discovery service, entities services, backoffice service.

---

<!-- ### Architecture - Patterns

Onion architecture
Clean Architecture

---

### Best practices

@ul

- Centralize dependencies - it would make for easier updates.
- Domain driven design - works grate with event-driven system.
- Automation - build, test, deploy from day one - it force proper dependencies management.
- Good practices - pick code style guide, linter, tests, git branches from day one.

@ulend -->

### Living with npm dependencies

The open source jungle making picking packages from npm hard - there is no *go to* package for every problem. For long lasting project picking the right dependencies is crucial

Note:
Example: compond.js, apigee sale to google, dead swagger projects

+++

### Evaluation

@ul

- npm - downloads, dependencies, updates
- Github - stars, PR, docs, issues, general activities
- Age, popularity, docs
- Source code review
- External tools: [npmcompare](https://npmcompare.com/)

@ulend

Note:
Compare costs to develop inhouse, Binaries dependencies, code commit frequencies

+++

### Frameworks

Personally I would advise against, even though it seems like it solves a lot of problems, it actually denial you from the agile development that Node.js known for.

Note:
Examples: mean, meteor, sail.js - mongodb update problem, reverse engineer workflows

---

### SaaS solutions

If you got a software need most likely there a SaaS solution for that - from all-in-one solutions like firebase, to highly specialized ones.

Note:
Examples SaaS: perion project, brance.io

+++

### Impact

@ul

- Costs
- Performance
- Data synchronization/ownership
- Security

@ulend

---

### Devops

In the last few years the border between dev and ops has been fading, most backend developer will have to use or at least understand devops tools and workflows

+++

### Devops tools

@ul

- Docker - mandatory for backend development
- CI/CD - selfhost: jenkins, teamcity; SaaS: CircleCI, Travis, code fresh
- AWS
- Linux - terminal, ssh, monitoring

@ulend

Note:
kubernetes/docker-compose

<!-- ### Devops Workflows -->
