# ot-lab-sdlc-devsecops

The Java web application used as the scan target for a DevSecOps pipeline lab.
University coursework, 2022.

The exercise was integrating security tooling into a CI/CD pipeline — static
analysis, dependency scanning and a security gate between build and deploy —
against an application with a realistic surface to find issues in. This
repository holds that application: a Spring MVC stack with Spring Security,
Hibernate/JPA over MySQL, and JSP views.

## Stack

- Spring MVC, Spring Security
- Hibernate / Spring Data JPA, MySQL
- Maven build (`mvn clean package`)

## Scope

The application source is upstream sample code, kept here as the target under
test. The pipeline configuration and scanner setup lived in the CI server and
are not part of this repository — so this repo shows what was scanned, not how
the scanning was wired up.

## Notes

Coursework. The application is intended to have findings in it; do not deploy it.
