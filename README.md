<p align="center">
    <img src="https://github.com/evgenyvaleev/librarium/blob/master/img/logo.png">
</p>

<p align="center">
    A collection of useful books, articles and other resources
</p>

***

## Fundamentals
### Algorithms & Data structures
* Aditya Y. Bhargava - Grokking Algorithms. An Illustrated Guide For Programmers and Other Curious People<br>
* Robert Sedgewick - Algorithms<br>
* Thomas H. Cormen - Introduction to Algorithms<br>
* Freeman E. - Head First Design Patterns<br>
* GoF - Design Patterns: Elements of Reusable Object-Oriented Software

## Databases
* [How does a relational database work](http://coding-geek.com/how-databases-work/)<br>
* [Let's Build a Simple Database](https://cstack.github.io/db_tutorial/)

### MSSQL
* [SQL Server Tutorial](http://www.sqlservertutorial.net/)

### PostgreSQL
* [PostgreSQL Tutorial](http://www.postgresqltutorial.com/)
* [Cybertec PostgreSQL Configurator](http://pgconfigurator.cybertec.at/)

## .NET
### C#
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
