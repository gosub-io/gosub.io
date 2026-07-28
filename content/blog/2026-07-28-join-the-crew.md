---
title: "Join the crew"
metatitle: "Help us build an independent browser engine"
description: "Gosub is looking for developers, browser specialists, security researchers, designers, writers, and others who want to help build an independent browser engine."
date: 2026-07-28
author: "Joshua Thijssen"
---

Building a browser engine is a large undertaking.

It requires much more than implementing an HTML parser or drawing a page on the screen. A modern browser engine combines networking, parsing, styling, layout, rendering, scripting, accessibility, security, process isolation, developer tooling, documentation, and many other areas.

We cannot build all of that alone.

Gosub is an open-source project, and we are looking for people who want to help us build an independent browser engine.

## Who are we looking for?

### Experienced developers

We are looking for developers who are comfortable working on complex systems and taking ownership of a problem.

Experience with Rust is useful, but browser experience is not required. Knowledge of graphics, networking, compilers, operating systems, security, language runtimes, or user-interface development can all be valuable.

Some of the areas we work on include:

* HTML and CSS parsing
* Style calculation and layout
* Graphics and rendering
* Networking and protocols
* JavaScript integration
* Browser process architecture
* Sandboxing and process isolation
* Developer tools
* Accessibility
* Testing and web-platform compatibility

You do not need to understand the entire engine. Most contributors work on one particular part of the system.

### New and aspiring developers

You do not need to be a browser expert before contributing to Gosub.

However, building a browser engine involves difficult and sometimes poorly documented problems. Our ability to provide one-to-one mentoring is limited, so contributors should be comfortable researching problems, reading existing code, asking specific questions, and working independently.

We want to create suitable starter tasks and documentation for people who are still learning. These tasks should be meaningful without requiring a detailed understanding of the complete browser engine.

As the project grows, we hope to provide a clearer path from small introductory tasks to larger areas of responsibility.

### Browser specialists

People with experience in browsers, web standards, rendering engines, or web-platform tests can help us make better architectural decisions and avoid mistakes that have already been solved elsewhere.

You do not necessarily need to write code. Reviewing designs, explaining edge cases, identifying missing standards, or participating in technical discussions can be just as useful.

### Security researchers

A browser continuously processes hostile and untrusted input.

We need people who can help us reason about:

* Process isolation
* Sandboxing
* IPC boundaries
* Origin and site isolation
* Cookie and credential handling
* Network security
* Parser vulnerabilities
* Memory and resource limits
* Threat modelling
* Fuzzing and security testing

Security should not be something added after the engine works. It must influence the architecture from the beginning.

### Designers and user-experience specialists

An engine eventually needs a usable browser around it.

We need help thinking about browser interfaces, developer tools, accessibility, error pages, settings, debugging interfaces, and the many small interactions that make a browser pleasant to use.

### Writers, educators, and technical communicators

Browser engines are complicated, and explaining them clearly is valuable.

You can help by:

* Improving documentation
* Writing tutorials and technical articles
* Explaining architectural decisions
* Creating diagrams
* Recording demonstrations
* Helping new contributors find their way around the project

### Community, marketing, and social media

A project cannot attract contributors, users, or funding when nobody knows it exists.

We need people who can help spread the word about Gosub through social media, conferences, meetups, articles, videos, podcasts, and conversations with other open-source communities.

This is not traditional product marketing. It is about explaining why independent browser engines matter, showing what we are building, and helping the right people discover the project.

### Project and community organisers

There is also important work outside the codebase.

We need help organising discussions, coordinating contributors, preparing events, maintaining community spaces, finding funding opportunities, and building relationships with other organisations.

## Focus groups

Not everybody needs to follow every part of the project.

We want to establish small focus groups around specific areas of the browser engine. These groups can investigate problems, review designs, coordinate work, and develop longer-term plans for their area.

Possible focus groups include:

### Security and process isolation

Threat modelling, sandboxing, renderer isolation, IPC design, capabilities, sensitive data, and reducing the impact of compromised components.

### Rendering and graphics

Layout, painting, compositing, fonts, GPU acceleration, rendering backends, and visual correctness.

### HTML and CSS

Parsing, standards compliance, DOM behaviour, style calculation, selectors, and web-platform tests.

### Networking

HTTP, caching, cookies, certificates, proxies, DNS, content decoding, privacy, and network-process architecture.

### Scripting

JavaScript integration, event loops, DOM bindings, Web APIs, workers, and communication between the scripting environment and the rest of the engine.

### Testing and compatibility

Web-platform tests, regression testing, fuzzing, screenshot comparison, interoperability, performance testing, and test infrastructure.

### Community and outreach

Documentation, articles, talks, contributor onboarding, social media, demonstrations, and relationships with other projects.

These groups do not need to be formal committees. They can begin as small groups of interested people meeting periodically to discuss one area and decide what should happen next.

## How you can contribute

There are several ways to get involved:

* Work on an existing issue
* Investigate a browser-engine problem
* Review a design or pull request
* Improve tests or documentation
* Join a focus group
* Propose an experiment
* Help explain and promote the project
* Help organise the community
* Tell us what experience you have and where you would like to contribute

You do not need to make a large commitment immediately. A useful review, experiment, bug report, article, or technical discussion can already make a difference.

## Finding the right place

When introducing yourself, tell us a little about:

* Your background and interests
* The areas of Gosub that interest you
* Whether you want to write code, research, review, document, organise, or promote
* How much time you roughly expect to have
* Whether you are looking for a starter task or want to take ownership of a larger area

We can then help find a part of the project that fits your experience and interests.

## Join the crew

Building an independent browser engine is ambitious, but that is also what makes it interesting.

Whether you are an experienced systems developer, a browser specialist, a security researcher, a designer, a writer, or someone who can help build the community around Gosub, there is a place where your knowledge can make the project stronger.

Come and talk to us on [GitHub](https://github.com/gosub-io/gosub-engine) or in our [Zulip chat](https://chat.developer.gosub.io), meet the people already working on Gosub, and help us decide what the next part of the engine should look like.
