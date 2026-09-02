# Interview Guide

## 30-second explanation
Enterprise Service Operations & SLA Platform is a portfolio case study for Support teams need structured ticket lifecycles, SLA enforcement, escalation, permissions and auditable workflows. The system uses Java 17+, Spring Boot 3.2+, JPA/Hibernate, Flyway, REST, SQL, WebSockets. I use it to demonstrate how I understand layered architecture, business logic, persistence, APIs and software-engineering trade-offs.

## 60-second explanation
The core problem is: Support teams need structured ticket lifecycles, SLA enforcement, escalation, permissions and auditable workflows. The solution is: A Spring Boot service-management backend that models ticket handling, SLA policies, automated escalation, roles, audit logging, webhooks and real-time updates. Its high-level architecture is $(@{Repo=enterprise-service-operations-platform; Title=Enterprise Service Operations & SLA Platform; Source=https://github.com/escalated-dev/escalated-spring.git; Upstream=escalated-dev/escalated-spring; Stack=Java 17+, Spring Boot 3.2+, JPA/Hibernate, Flyway, REST, SQL, WebSockets; Problem=Support teams need structured ticket lifecycles, SLA enforcement, escalation, permissions and auditable workflows.; Solution=A Spring Boot service-management backend that models ticket handling, SLA policies, automated escalation, roles, audit logging, webhooks and real-time updates.; Arch=Client -> REST Controllers -> Services -> JPA Repositories -> Relational Database}.Arch). I adapted the repository for portfolio presentation and documented its architecture. The underlying open-source foundation is preserved and attributed, and I distinguish source functionality from my own later enhancements.

## Interview integrity
Be explicit about:
- upstream source functionality
- documentation you created
- code you personally changed
- planned but unimplemented work
