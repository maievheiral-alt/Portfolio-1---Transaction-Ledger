# Portfolio-1---Transaction-Ledger
A system that processes high-volume monetary transactions, categorizes them, handles balances, and prevents double-spending or data corruption through ACID compliance.

##  Tech Stack

*   **Language:** Java 25
*   **Framework:** Spring Boot 4.1.1
*   **Web Framework:** Spring Web MVC
*   **Persistance:** Hibernate via Spring Data JPA
*   **Database:** MySQL (Planned, not connected yet)
*   **Database Driver:** MySQL Connector/J
*   **Validation:** Spring Boot Validation
*   **Build Tool:** Apache Maven

##  Architecture & Data Integrity

The application follows a standard three-tier architecture split into API Controllers, Business Logic Services, and Data Repositories. Data integrity is treated as a first-class citizen in this project. The application is being designed to maintain transactional integrity with Spring-managed transactions and MySQL's InnoDB engine, in line with ACID principles.

##  ROADMAP
1) Planning and Architecture: Define MVP, Business Rules, Technology Choices, Architecture Diagram, and initial database ERD
2) Project Setup and First Integration: Initialize Spring Boot, configure MySQL, create entities and repositories, prove connection works
3) Core Implementation: Implement accounts and basic transaction operations, write tests alongside the functionality
4) Complete Business Logic: Implement transfers, balance validation, transaction boundaries, and error handling
5) Integration and Integrity Testing: Test concurrency, rollbacks, duplicates, database constraints, and component interactions
6) Troubleshooting and Optimization: Fix defects, validate performance, review security, and make application reproducable
7) Documentation and presentation: Write API documentation, refine the README, prepare diagrams, and create demonstrations
8) Final Release: Finish presentation materials, verify setup instructions, and publish a tagged release

##  PROJECT STATUS
*   **PHASE:** Initial Development
### 2026-10-18
    -Database schema designed
    -Spring Boot project initialized
    -Maven dependencies configured
    -Application build not yet verified
    -Database integration pending

