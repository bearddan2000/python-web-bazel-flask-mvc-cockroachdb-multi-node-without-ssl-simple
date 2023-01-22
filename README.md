# python-web-bazel-flask-mvc-cockroachdb-multi-node-without-ssl-simple

## Description
Creates a mvc dataTable of `dog` for a flask project.

A python flask build, that connects to 3 node cluster
cockroach database without ssl.

If path is not found, will default to 404 error.

## Tech stack
- bazel
- python
  - flask
  - sqlalchemy
- bootstrap
- jquery
- dataTable
- cockroachdb

## Docker stack
- l.gcr.io/google/bazel:latest
- cockroachdb/cockroach:v19.2.4

## To run
`sudo ./install.sh -u`
- [web-bazel app](http://localhost)
- [Master node web-bazelui](http://localhost:8000)
- [Slave node 1 web-bazelui](http://localhost:8001)
- [Slave node 2 web-bazelui](http://localhost:8002)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Cockroach setup](https://github.com/s0rg/cockroach-compose)
- [Python flask with cockroachdb](https://www.cockroachlabs.com/blog/building-application-cockroachdb-sqlalchemy-2/)
