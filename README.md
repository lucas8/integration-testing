# integration-testing

This repository is just an example how to do integration testing in Golang with a real Database. For this repostiory case, I use MySQL and Redis.
An explanation about this repository could be found in my Medium post [Integration Testing With Databse In Golang](https://hackernoon.com/integration-test-with-database-in-golang-355dc123fdc9)


## How To Run The Test

Prerequisite:
- Docker (docker-compose)
- go 1.11+
- Unix environment 

Locally:

```shell

$ make integration-test
# Will run the integration testing of this projects. Wait until finished.

$ make clear
# After finished, clear all the testing dependencies
```
