---
layout: post
title: Birthday party with Scala and Akka
speaker:
  - julian_dragos
  - jonas_boner
slideshare:
  - 6643956
  - 6636244
picasa: 5565055027211660977
---

![Logo Scala](/images/events/scala-logo.png){:align="right"}{:.margin-logo} Scala is a general purpose programming language designed to express common programming patterns in a concise, elegant, and type-safe way. It has established itself as one of the main alternative languages on the Java Virtual Machine, being used by companies like Twitter and LinkedIn. Scala fuses functional programming (from which it borrows higher-order functions and closures, generic typing and immutable data structures) and object-oriented programming programming (from which it takes inheritance and encapsulation). It interoperates fully with Java, allowing a smooth transition and access to all existing Java libraries.
Scala’s lightweight syntax makes it easy to extend the language through DSLs. In this talk we are going to have a quick overview of Scala’s main features (closures, higher-order functions, implicits), and collection classes in the standard library. We’ll see how a new concurrency model, such as actors, can be added to the language through a library.

![Logo Akka](/images/events/akka_logo.png){:align="left"}{:width="184"}{:height="100"}{:.margin-logo} We believe that writing correct concurrent, fault-tolerant and scalable applications is too hard. Most of    the time it’s because we are using the wrong tools and the wrong level of abstraction. Akka is here to change that. Akka is using the Actor Model together with Software Transactional Memory (STM) to raise the abstraction level and provide a better platform to build correct concurrent and scalable applications. For fault-tolerance it adopts the “Let it crash” model which have been used with great success in the Telecom industry to build applications that self-heals, systems that never stop. Akka’s Remote Actors, backed by a scalable non-blocking IO implementation, provides the abstraction for transparent distribution and the basis for truly scalable and fault-tolerant applications. In this talk you will learn what Akka is, how it can be used to solve hard problems and the ideas behind its design and implementation. Akka is available at [http://akkasource.org/](http://akkasource.org/)
