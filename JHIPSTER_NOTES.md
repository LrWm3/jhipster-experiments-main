# deer learns jhipster

I learn jhipster.

## Goals

- [ ] Experiment with JDL.
- [ ] Try and figure out how to update a project once its made.
- [ ] Try and figure out the pattern for injecting business logic.
- [ ] GraphQL would be fun.
- [ ] Postgresql database would be fun.
- [ ] Docker-compose integrations would be fun.

## Notes

~~None, I haven't done anything yet.~~

I installed the Jhipster JDL vscode plugin.

I began by copying the default example in [JDL Studio](https://start.jhipster.tech/jdl-studio/).

The linter had issue with some of the DL syntax, so I cleaned it up a bit.

By looking at the [JHipster CLI](https://www.jhipster.tech/creating-an-app/#-command-line-options) and
[JDL Applications](https://www.jhipster.tech/jdl/applications) pages I was able to create an application definition.

I ran `jhipster import-jdl jh/app.jh` in my vscode terminal. vscode crashed before it completed though.

It also overwrote my README.md, so I moved the files down into the `deerDash` directory to try again.

## Woah moments

It can [build Docker images](https://www.jhipster.tech/docker-compose/).
