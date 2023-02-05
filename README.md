# java-cli-bazel-hibernate-ssl-postgres-simple

## Description
Creates a small database table
called `dog` and populates with
hql.

Uses self-sign ssl.

## Tech stack
- java
- bazel
  - hibernate
  - hql
  - log4j
  - postgres driver

## Docker stack
- alpine:edge
- l.gcr.io/google/bazel:latest
- postgres:alpine

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`
## For help
`sudo ./install.sh -h`

## Credit
- [ResultTransformer code based on](https://thorben-janssen.com/hibernate-resulttransformer/)
- [HQL code based on](https://www.journaldev.com/2954/hibernate-query-language-hql-example-tutorial)
- [Hibernate config based on](https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/An-example-hibernatecfgxml-for-MySQL-8-and-Hibernate-5)
- [Hibernate code based on](https://github.com/lokeshgupta1981/hibernate/tree/master/hibernate-hello-world)
