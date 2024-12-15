# Database

* Status: Proposed
* Deciders: Name1, Name2, Name3
* Date: 2024-10-14

Technical Story: A relational database system is needed to handle structured data for user accounts, media inventory, borrowed media and subscription history.

## Context and Problem Statement

The database must efficiently store and manage structured data while ensuring data integrity and supporting complex queries.

## Considered Options

* MongoDB
* MySQL

## Decision Outcome

Chosen option: "MySQL", because Why did we choose option

### Positive Consequences

* Easy to use with strong support for relational operations.

### Negative Consequences

* May face performance bottlenecks for larger-scale deployments.

## Pros and Cons of the Options

### MongoDB

A NoSQL database designed for unstructured and semi-structured data.

* Good, because High performance for document-based queries.
- Schema-less design allows flexibility.
* Bad, because Lacks robust support for relational operations.
- Additional complexity when handling transactions.

### MySQL

A relational database management system.

* Good, because Large community and support base.
- Well-structured for multiple models.
* Bad, because Not as flexible with data types like JSON.
- Limited functionality for modern NoSQL-like operations.
