# java-cli-maven-pmd-spock-jacoco-test-hello-world

## Description
A POC for maven app using spock framework.
Jacoco and pmd plugins used for reporting.

## Tech stack
- java
- groovy
- maven
  - Jacoco
  - spock
  - pmd

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- pmd report found at bin/target/site

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept](https://www.petrikainulainen.net/programming/testing/writing-unit-tests-with-spock-framework-creating-a-maven-project/)
- [Code build model](https://github.com/christoph-frick/spock-test-logging)
