---
title: "Reverse Engineering (RevEng) Project for SDL at Milwaukee School of Engineering"
date: 2026-05-15
category: "school"
tldr: "Replace Enterprise Architect with an internal reverse UML diagram generation tool from code."
tech: ["Java", "ANTLR", "PlantUML", "Gradle", "TestNG", "Mockkito", "Java Swing UI", "GitLab CI/CD", "GitLab Runner"]
link: "https://faculty-web.msoe.edu/hasker/reveng/"               # optional: repo or demo URL

---

This project was a yearlong agile scrum team for my `SWE3710-3720 - Software Development Lab I & II` course where we were to create a reverse engineering tool to generate UML diagrams from Java and C++ code. \
The application had three big main parts, the biggest was the Desktop application that had the most functionality and a GUI. We also developed a CLI tool that users could use with scripts to create an entire sections UML diagram by just pointing it to a folder with all the projects. The third piece was a plugin to IntelliJ and CLion that allowed users to generate UML diagrams from the IDE itself, with real time UML updates to see the UML as it changes. The application uses PlantUML to generate the UML diagrams and ANTLR to parse the Java and C++ code. The application was built with Java Swing for the GUI, Gradle for build automation, TestNG and Mockito for testing, and GitLab CI/CD for the runners.