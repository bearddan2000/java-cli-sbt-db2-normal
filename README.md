# java-cli-sbt-db2-normal

## Description
Creates a small database table
called `dog`. This table, `dog`, has been normalized to 3NF.
All output normally
seen in a terminal will be in `java-srv/log` which will dump to the screen. The project may seem to hang but the logs from the container must be written to the project this can take up to 3 min.

## Tech stack
- docker-wait
- java
- sbt
  - log4j
  - db2 driver

## Docker stack
- hseeberger/scala-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10
- ibmcom/db2

## To run
`sudo ./install.sh -u`
Creates java-srv/log

## To stop
`sudo ./install.sh -d`
Removes java-srv/log

## For help
`sudo ./install.sh -h`
