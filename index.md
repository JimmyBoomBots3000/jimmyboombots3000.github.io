---
description: Java and Spring Boot software engineer building production services, full-stack applications, and enterprise integrations
---

## James Richmond

{% assign experience_years = site.time | date: '%Y%m' | minus: 202105 | divided_by: 100 %}
I'm a software engineer with {{ experience_years }} years of professional experience building Java services, full-stack applications, and enterprise integrations. I work primarily with Java, Spring Boot, SQL, and JavaFX, and own software from requirements through deployment and production support.

I like understanding the whole system: the business rules, the data, the interface, and what happens when something fails. My earlier work in electronics and avionics still shapes that approach: trace the signal, respect the edge cases, and keep asking what changed.

[Resume](/resume.html) · [GitHub](https://github.com/JimmyBoomBots3000) · [Email](mailto:james.b.richmond@gmail.com)

### Selected Professional Work

These projects are part of proprietary systems; the descriptions summarize my contributions.

#### Java services and legacy modernization

Built a Spring Boot REST service end to end, rewriting core business logic previously embedded in a legacy desktop application so new applications could use it. The service is used daily to support financial transmission rights (FTR) trading portfolios valued at hundreds of millions of dollars. Defined a common interface for credit-calculation rules with differing inputs and behavior.

#### Import performance and correctness

Stress testing exposed a bottleneck as an import workflow expanded beyond a few rows. Replaced repeated database queries with bulk queries and added request-scoped caches for repeated calculations, reducing an approximately 15,000-row CSV import from 10 minutes to 5 seconds. Collected and compared calculation outputs to validate the change.

#### Administration tools

Prototyped a JavaFX application to replace manual SQL queries for user and trading-desk administration. Management adopted it, and I expanded it to reports and authentication certificates. Built the application end to end, including its backend services and database integration, along with a reusable JavaFX library.

#### Enterprise integrations and full-stack development

At Justifacts, developed and maintained a Java/JSP web application and background-screening integrations with more than 20 ATS and HRIS platforms, including Workday, Oracle Taleo, SAP SuccessFactors, iCIMS, Greenhouse, and ADP. Built web interfaces using JavaScript, HTML, CSS, and Bootstrap.

### Open Source

#### FontAwesomeFX

Modernized an existing JavaFX icon library with a Maven build, updated Font Awesome catalogs, automated source generation, and a searchable icon viewer, preserving historical icon names. This is an independent fork of FontAwesomeFX by Jens Deters, with original attribution retained.

[View FontAwesomeFX](https://github.com/JimmyBoomBots3000/fontawesomefx)

#### FontAwesomeSwing

Created a native Swing/AWT adaptation of FontAwesomeFX, replacing JavaFX dependencies with Swing icons and components. Includes layered icons, a searchable viewer, and headless tests.

[View FontAwesomeSwing](https://github.com/JimmyBoomBots3000/fontawesomeswing)

#### ControlsFX

I contribute fixes and enhancements to **ControlsFX**, a JavaFX controls library. My pull requests provide public examples of how I work within an existing codebase.

[View my ControlsFX pull requests](https://github.com/controlsfx/controlsfx/pulls?q=is%3Apr+author%3AJimmyBoomBots3000)

### Background

I earned my B.S. in Computer Science from Southern New Hampshire University in 2021, summa cum laude. Before software engineering, I worked in electronics, avionics, quality inspection, and technical management, and served in the U.S. Navy.

My [academic archive](/academic.html) contains coursework in reverse engineering, data structures, and database-backed applications.

### Outside work

Outside work, I coach youth basketball and tinker with electronics. I enjoy figuring out how things work, whether that means tracing a software bug or troubleshooting a circuit.

### Contact

[james.b.richmond@gmail.com](mailto:james.b.richmond@gmail.com)
