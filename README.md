# Heart Health Imaging & Recording System

A JavaFX desktop application for medical intake and risk-assessment workflows, simulating a real clinical data system as an academic project. Built with Java and Gradle.

## Demo

[Watch a walkthrough of the application](https://www.youtube.com/watch?v=xWfW3PEf78Y)

## Overview

This system models a clinical data-entry and review workflow across four distinct user roles, each with different permissions over patient data — built to explore role-based access control and maintainable object-oriented design in a domain with real-world data-sensitivity constraints.

## Key Features

- **Role-Based Access Control (RBAC)** — Login-gated access where each role sees only what they're authorized to:
  - **Intake staff** can only enter patient information
  - **Lab personnel** can only view data they've personally added
  - **Patients** can only view their own results
  - **Doctors** have full visibility, with their notes protected from edits by other roles
- **Structured, file-based persistence** for patient records, designed to keep data access consistent with the access-control model
- **UML-driven design** — system architecture modeled with class diagrams ahead of implementation to manage complexity as roles and workflows expanded

## Tech Stack

- Java
- JavaFX
- Gradle
- UML (Astah)

## Running the Project

```bash
./gradlew run
```

## Background

Originally developed as a project for SER 460 (Software Analysis and Design) at Arizona State University.