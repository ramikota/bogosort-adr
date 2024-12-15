# Frontend Framework

* Status: Proposed
* Deciders: Rami Kotaiche, Habib Ullah, Casey Cheung
* Date: 2024-10-17

Technical Story: The frontend framework needs to support dynamic and responsive interfaces across multiple channels such as web, mobile, and in-branch.

## Context and Problem Statement

We need a strong frontend framework that provides a seamless user experience across all devices and supports interactive and dynamic features efficiently.

## Decision Drivers

* Familiarity of the use of the system throughout the team.

## Considered Options

* React
* Vue.js

## Decision Outcome

Chosen option: "React", because The team is already familiar with using react previously and so the learning curve isnt as great compared to vue.js.

### Positive Consequences

* Offers excellent flexibility with its component-based architecture.

### Negative Consequences

* Requires additional setup for advanced state management.

## Pros and Cons of the Options

### React

A popular JavaScript library for building user interfaces.

* Good, because Component-based, reusable structure simplifies complex UIs.
- It has a large library support.
- Cross-platform compatibility via React Native for mobile.
* Bad, because Relies on third-party tools for complete solutions (e.g., routing, state management).
- Learning curve for advanced features.

### Vue.js

A lightweight JavaScript framework focused on simplicity and ease of use.

* Good, because Simple to learn and use, ideal for small to medium projects.
- Flexible for integration into existing projects.
* Bad, because Smaller library ecosystem compared to React.
- Not as viable for large-scale applications.
