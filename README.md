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

## MSSQL
* [SQL Server Tutorial](http://www.sqlservertutorial.net/)

### PostgreSQL
* [PostgreSQL Tutorial](http://www.postgresqltutorial.com/)
* [Cybertec PostgreSQL Configurator](http://pgconfigurator.cybertec.at/)

## Frontend
### JavaScript
* [Kyle Simpson - You Don't Know JS](https://github.com/getify/You-Dont-Know-JS)<br>
* [JavaScript Coercions Grid](https://getify.github.io/coercions-grid/) :see_no_evil:

### TypeScript
* [Design patterns in typescript](http://torokmark.github.io/design_patterns_in_typescript/)

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
