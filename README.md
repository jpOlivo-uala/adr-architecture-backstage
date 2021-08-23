# Architecture Decision Records (ADR)


## Summary
This repository aims to gather the more significant architecture decisions. All decisions inside of this repo is based on the Nygard ADRs template.

## Tools

We use [adr-tools](https://github.com/npryce/adr-tools) and [adr-log](https://adr.github.io/adr-log) in order to manage the ADRs


## How to register a new Architecture Decision?

1. Generate a new record

```console
foo@bar:~$ adr new my new decision
```

2. Add the record to log
```console
foo@bar:~$ adr-log -i
```

3. Check that the record is published
```console
foo@bar:~$ open https://jpolivo-uala.github.io/adr-architecture/
```


## Links

- [adr-tools](https://github.com/npryce/adr-tools)
- [adr-log](https://adr.github.io/adr-log)
- [Nygard format](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions.html)
- [When should I write an ADR](https://engineering.atspotify.com/2020/04/14/when-should-i-write-an-architecture-decision-record/)
- [ADR Github organization](https://adr.github.io/)