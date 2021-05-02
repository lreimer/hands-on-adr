# Hands-on Architecture Decision Records

Demo repository for using Architecture Decision Records (ADR).

<!-- adrlog -->

* [ADR-0001](doc/adr/0001-record-architecture-decisions.md) - Record architecture decisions
* [ADR-0002](doc/adr/0002-java-as-primary-language-for-microservices.md) - Java as primary language for microservices
* [ADR-0003](doc/adr/0003-java-ee-as-framework-for-microservices.md) - Java EE as framework for microservices
* [ADR-0004](doc/adr/0004-a-template-adr.md) - A template ADR

<!-- adrlogstop -->

## Usage

```
$ adr init
$ adr new Java as primary language for microservices
$ adr new Java EE as framework for microservices
$ adr link 3 Amends 2 "Amended by"
$ adr new A template ADR

# generate the ADR table of contents using adr-log
$ adr-log -d doc/adr/ -i README.md
```

## Maintainer

M.-Leander Reimer (@lreimer), <mario-leander.reimer@qaware.de>

## License

This software is provided under the MIT open source license, read the `LICENSE` file for details.
