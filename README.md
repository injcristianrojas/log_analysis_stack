# Log analysis stack

This repo tries to dockerize [@mdiazcl](https://github.com/mdiazcl)'s [virtualized environment for a Security
log analysis workshop](https://mdiazlira.com/Talleres/TallerAnalisisDeLogs/prelab.html).

## Setup

For the stack to work you will need:

1. 8 GB of memory.
1. Docker version 1.13.0 or better.
1. Docker Compose.
1. More virtual memory: Follow the instructions on
https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html#docker-cli-run-prod-mode
depending on your OS.

## Launch

Create a logs folder:

```shell
mkdir logs
```

Put some CSV data in the `logs` folder, and then launch the stack using:

```shell
docker-compose up
```

Now, go to http://localhost:5601 and have fun.
