# Implementing the Clean Architecture

You have very likely heard of Hexagonal Architecture, Onion Architecture or the Clean Architecture.
While talk about this family of architectures is common, it can be hard to find good real-world examples.
In this presentation I tell you the story of how we, at Wikimedia Deutschland, wrote an application 
adhering to the Use Case approach of the Clean Architecture. This includes an introduction to the key
concepts of the Clean Architecture and an overview of the most important lessons we learned during
implementation. After the presentation you will be able to look at
[our code on GitHub](https://github.com/wmde/FundraisingFrontend) which is fully open source.

## Audience

This presentation is aimed at developers. A good grasp of design fundamentals is helpful, though novice
developers will also benefit from exposure to the included concepts.

The application is a PHP7 one, however the architecture principles and design techniques discussed are largely
language agnostic, and can therefore easily be applied in other OOP languages.

## Topic list

* Function of the application and reason for its creation
* Our analysis and planning phase (don't worry, it's not Big Design Up Front)
* The Clean Architecture
* High level organization
* Flow of control
* Lessons learned
* Bounded Contexts
