<p align="center">
  <img src="img/logo.png">
</p>

<p align="center">
    A collection of useful books, articles and other resources
</p>

***

## Table of Contents

- [Fundamentals](#fundamentals)
  - [Computer Science](#computer-science)
  - [Algorithms & Data structures](#algorithms--data-structures)
  - [Architecture](#architecture)
  - [Other](#other)
- [Databases](#databases)
  - [MSSQL](#mssql)
  - [PostgreSQL](#postgresql)
- [.NET](#net)
  - [C\#](#c-1)
- [Frontend](#frontend)
  - [JavaScript](#javascript)
  - [TypeScript](#typescript)
  - [React](#react)
  - [Redux](#redux)
- [Web](#web)
- [Security](#security)
- [Snippets](#snippets)
  - [cron](#cron)
- [Health](#health)
  - [Mental Health](#mental-health)

## Fundamentals

### Computer Science

- :book: Abelson H. - Structure and Interpretation of Computer Programs

### Algorithms & Data structures

- :book: Bhargava A. - Grokking Algorithms. An Illustrated Guide For Programmers and Other Curious People
- :book: Sedgewick R. - Algorithms
- :book: Cormen T. - Introduction to Algorithms
- :book: Freeman E. - Head First Design Patterns
- :book: GoF - Design Patterns: Elements of Reusable Object-Oriented Software

### Architecture

- :book: Avram A., Marinescu F. - DDD Quickly
- [Event Sourcing](https://arkwright.github.io/event-sourcing.html) - an introduction to event sourcing by arkwright

### Other

- [Semantic Versioning](https://semver.org/)
- [The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets (No Excuses!)](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/)

## Databases
* [How does a relational database work](http://coding-geek.com/how-databases-work/)<br>
* [Let's Build a Simple Database](https://cstack.github.io/db_tutorial/)

### MSSQL
* [SQL Server Tutorial](http://www.sqlservertutorial.net/)

### PostgreSQL
* [PostgreSQL Tutorial](http://www.postgresqltutorial.com/)
* [Cybertec PostgreSQL Configurator](http://pgconfigurator.cybertec.at/)

## .NET

### C\#

* Albahari J., Albahari B. - C# 7.0 in a Nutshell: The Definitive Reference
* Skeet J. - C# in Depth
* Richter J. - CLR via C#
* Seemann M. - Dependency Injection in .NET
* Osherove R. - The Art of Unit Testing

## Frontend
### JavaScript
* [Kyle Simpson - You Don't Know JS](https://github.com/getify/You-Dont-Know-JS)<br>
* [JavaScript Coercions Grid](https://getify.github.io/coercions-grid/) :see_no_evil:

### TypeScript
* [TypeScript](https://www.typescriptlang.org/docs/home.html) - official docs
* [Design patterns in typescript](http://torokmark.github.io/design_patterns_in_typescript/)

### React
* [React](https://reactjs.org/docs/getting-started.html) - official docs
* [React Router](https://reacttraining.com/react-router/web/guides/quick-start) - official tutorial

### Redux
* [Redux](https://redux.js.org/introduction/getting-started) - official docs
* [Redux Saga](https://redux-saga.js.org/) - official docs

## Web
* [HTTP codes](https://www.w3.org/Protocols/rfc2616/rfc2616-sec10.html)

## Security
* [Everything you should know about certificates and PKI but are too afraid to ask](https://smallstep.com/blog/everything-pki.html)

## Snippets
### cron
Run crontab tasks manually:
```shell
crontab -l | grep -v '^#' | cut -f 6- -d ' ' | while read CMD; do eval $CMD; done
```

## Health
* [The Science of How to Build Muscle](https://www.julian.com/guide/muscle/intro)

### Mental Health
* [How I cured my tech fatigue by ditching feeds](https://techcrunch.com/2017/10/28/how-i-cured-my-tech-fatigue-by-ditching-feeds/) [[HN](https://news.ycombinator.com/item?id=15578019)]
