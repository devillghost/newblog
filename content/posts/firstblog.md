---
author:
  name: "Kiran"
date: 2019-03-25
linktitle: Creating a New Theme
type:
- post 
- posts
title: 3 steps to analyze source code with SonarQube by using Docker
weight: 10
---

Recently I have tried to leverage SonarQube in order to do a static analysis of the java code. In this article, we’re going to be looking at static code analysis with SonarQube in 3 steps by using docker for beginners.

<h2> What is SonarQube? </h2>
SonarQube is an open-source platform for continuous inspection of code quality. Using static code analysis, it tries to detect bugs, code smells and security vulnerabilities on 20+ programming languages. SonarQube offers reports on duplicated code, coding standards, unit tests, code coverage, code complexity, comments, bugs, and security vulnerabilities.

Alright, let’s start…

To start with SonarQube first you should know about what is Sonar Server and Sonar Runner. Sonar Server where the engine that performs the analysis and stores the results, and the analysis must be invoked in some way, which can be done with a client called Sonar Runner aka SonarQube scanner or with a Maven plug-in. You can also integrate the analysis with the IDE that you are using, with a plugin called SonarLint.

I’ll start by assuming that you already have Docker installed, otherwise the process is quite simple and can be seen [here](https://docs.docker.com/v17.12/install/).

<h2> Below are the 3 steps we're going to be looking at <h2>
  
1) Setting up Sonar Server
2) Setting up Sonar Runner
3) Run SonarQube Runner

  
  
