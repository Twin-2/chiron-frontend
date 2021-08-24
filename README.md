# Chiron - Fitness Exercise Finder

**Authors**: David Whitmore, Tray Alexzandar, Jesse Dills, Matt Cho

**Version**: 1.0

## Overview
This application allows you to build a unique library of exercises for yourself. Deployed on [Netlify](https://chiron-fitnesshelper.netlify.app/). Backend code on [this](https://github.com/Twin-2/chiron-backend) GitHub repo.

## Wireframe
![](./img/wireframe.png)

## User Stories
- As a user, I want to be able to login and see my profile with my favorite exercises.

- As a fitness enthusiast, I want to find exercises that work on specific areas of my body.

- As a health nut, I want to find lots of different exercises.

- As a frugal person, I want to find exercises that don’t require expensive gym equipment.

- As a kettlebell collector, I want to find exercises that include a kettlebell.

## Domain Model
![](./img/domainmodel.png)

## Database Schema

- User
  - Email (required/unique)
  - Exercise
    - Exercise Name
    - Exercise Description
    - Category (Muscle Group)
    - Equipment (Bench, Dumbells, etc.)
