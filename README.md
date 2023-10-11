# social-media
Collaborated with other developers to create a RESTful API using Spring Boot, JPA, and Postgresql that exposes operations for social media data that resembles the conceptual model of Twitter.
# My Contribution to a Twitter-like RESTful API Group Project

## Overview

In this collaborative effort, our team worked on implementing a RESTful API that draws inspiration from the conceptual model of Twitter. Leveraging tools such as Spring Boot, JPA, and PostgreSQL, we transformed the provided specifications into a working model. While the project required collective input, my specific contributions revolved around handling requests with Spring services and controllers, implementing validation and business logic, and managing data transformation between the API and database models.

## Utilizing the Provided Test Suite

Our team was provided with a comprehensive test suite to validate the correctness and robustness of our API. We integrated Postman's newman CLI, which I assisted in setting up via `npm install -g newman`. With everything in place, we diligently ran the tests using the `newman` command. Through our combined efforts, and iterative troubleshooting, we celebrated the moment when all 330 assertions successfully passed.

## Working with the Requirements

We were handed a thorough set of requirements that outlined the roadmap for our project. These requirements covered a wide range of topics, including RESTful Endpoint Methods and URLs, URL Variables, Types, and Object Properties, among others. While we did not author these guidelines, their depth and clarity were instrumental in shaping our approach and ensuring our API endpoints aligned with the expected structure and behavior.

## Entity Relationship Diagram (ERD)

Building on the provided ERD, our team got a clear visualization of the database's architecture. The collective focus was on three main classes: User, Tweet, and Hashtag, which we annotated with `@Entity`. I took on a pivotal role in shaping the Credentials and Profile classes, ensuring they were correctly annotated with `@Embeddable`. To maintain the uniqueness of these classes within the Java framework, while synchronizing with a unified database table, I spearheaded the integration of the `@Embedded` annotation within the User entity class. Furthermore, recognizing the reservation of the "user" keyword in PostgreSQL, I championed the use of the `@Table(name=<newName>)` annotation for the User entity.

## API Data Types

The predefined API data types played a central role in our development process. These definitions, while provided to us, acted as the blueprint for our API's operations. They often came into play during GET operations or when nested as auxiliary data in other objects. Collaborating closely with team members, I provided insights and support in leveraging these data types for creating new database records via POST operations.

## Personal Reflection

Being part of this group project was an enlightening journey. Navigating the challenges of collaborative development, leveraging provided resources, and converging on a unified solution was truly rewarding. This experience underscored the value of teamwork and offered me an opportunity to expand my backend development skillset within a dynamic and supportive environment.
