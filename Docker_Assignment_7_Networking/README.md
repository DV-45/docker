\# Docker Assignment 7 – Networking



\## Objective

Demonstrate Docker networking using:

\- Default bridge (`bridge`)

\- Custom bridge (`mybridge` with subnet `10.10.0.0/16`, gateway `10.10.0.1`)

\- Verify container communication and isolation

\- Connect a container to multiple networks



\---



\## Steps



\### 1. Verify Docker \& Networks

```bash

docker --version

docker network ls



