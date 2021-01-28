# EInnovator Startup Factory -- MVP and Samples Catalog

This is a catalog of MVPs and sample applications made available by **EInnovator** as part of the **Startup Factory** initiative. All projects listed in this catalog have a permisse open-source Apache license. They can be used by startups, established business of any size, independent developers, and the community at large, as a starting point to build business ready applications, to incorporte in larger systems and applications, pick random code snippets, self-learning, or whatever uses you may want to give to it.

## What is in here ?

The software required to enable and implement business ideas can be varied, of different types, and combinations.
We aim to cover this multiplicity of needs, by providing full-projects and component parts of different sorts. 
Web applications and backends take a central rolw, as they can be deployed and used standalone, or as part of a more complex architecture.
This may include other microservices, including reusable middleware microservice, web-front ends, mobile applications, and CLI Tools.

Following list summaries the categories of projects listed in this catalog:

- Web applications and backends
- REST API implementations (no UI)
- Client libraries (for the API and web backends)
- Utility libraries
- Web front-ends
- Android Mobile Apps
- iOS Mobile Apps
- CLI Tools


## Stacks

### Depoloyment


## Project Funding

An obvious question is how is the development and maintainance of projects listed in this catalog done. This is kind of a more general question that applies to many/most open-source projects. One way, is that trought self-funding and donations. EInnovator also offers commercial professional services (consulting and software development) to build MVPs and business solutons to startups and established business. Which is done be extending existing projects in this catalog, or by creating a complete new solution, or a mix.
Due to the permissive Apache license, other developers (independent, agencies, or consulting companies) are also allowed and encoraged to do the same.

## Contributing

If you are a developer and want to contribute projects to this catalog listing, do a pull request and/or email us at: startupfactory@einnovator.org.

## Web Backends


### Superheros (sample)

#### About

This is a simple sample app to implement a CRUD DB on Superheros.

#### Stack

- Backend: Java/SpringBoot
- Frontend/UX: Javascript, JQuery+Plugins, EInnovator JS Widgets
- DB: HSQLDB, MySql/MariaDB, MongoDB/RethinkDB (planned), Redis (planned)

#### Integration

- Runs Standlone
   - Unsecure access
   - Self implemented authentication
   - Social IAM provider (FB,Google,Github,Okata)
- (Optional) Integrates with an SSO Gateway -- for IAM single-sign-on:
   - EInnovator SSO
   - Keyclock (planned)
- (Optional) Integrates with a social comments/chat channel service:
  - EInnovator Social Hub 
  - Diskus (planned)
- (Optional) Integrates with file/document store service:
  - EInnovator Document Store 
  - Other (planned)
- (Optional) Integrates with user notification service:
  - EInnovator Notifications Hub 
  - Other (planned)

#### Resources

- [GitHub Repository](https://github.com/einnovator/einnovator-sample-superheros) 
- Docker Image Repository:
   - [DockerHub](https://hub.docker.com/r/einnovator/einnovator-sample-superheros)
   - [GCP](gcr.io/gcp-marketplace-302116/einnovator-sample-superheros)
- [Demo](https://superheros.nativex.cloud/)

#### DataModel

- Superhero (entity class)

### Movies (sample)

#### About
This is a simple sample app to implement a Movie and Actor DB.

#### Stack

- Backend: Java/SpringBoot
- Frontend/UX: Javascript, JQuery+Plugins, EInnovator JS Widgets
- DB: HSQLDB, MySql/MariaDB, MongoDB/RethinkDB (planned), Redis (planned)

#### Resources

- [GitHub Repository](https://github.com/einnovator/einnovator-sample-movies) 
- Docker Image Repository:
   - [DockerHub](https://hub.docker.com/r/einnovator/einnovator-sample-movies)
   - [GCP](gcr.io/gcp-marketplace-302116/einnovator-sample-movies)
- [Demo](https://movies.nativex.cloud/)

### E-Commerce Shop (MVP)

Upcomming...

### Hotel Booking (MVP)

Upcomming...

### Buy&Sell Marketplace (MVP)

Upcomming...

## REST API implementations (no UI)

Upcomming...

## Client libraries (for the API and web backends)

Upcomming...

## Utility libraries

Upcomming...

## Web front-ends

Upcomming...

## Android Mobile Apps

Upcomming...

## iOS Mobile Apps

Upcomming...

## CLI Tools

### EInnovator CLI

### About

A CLI tool for multi-cluster/multi-cloud Kubernetes devops and micro-services development.

Out-of-the-box, support integration with the following services:

-  devops --- Kubernetes Cloud Manager Devops operations
-  sso --- SSO operations
-  notifications --- Notifications Hub operations
-  documents --- Document Store operations
-  social ---- Social Hub operations
.  payments --- Payment Gateway operations

#### Stack

- Java/SpringBoot

#### Resources

- [GitHub Repository](https://github.com/einnovator/einnovator-cli) 
- Documentation:
  - Article/Tutorial @Medium: [GitHub Repository](https://github.com/einnovator/einnovator-cli) 
