\# Docker Assignment 1 – Ubuntu Container with vim, git, and tree



This assignment demonstrates creating an Ubuntu container, installing essential tools (`vim`, `git`, and `tree`), verifying them, and managing the container lifecycle.



\---



\## Objective



\- Launch an Ubuntu container

\- Install `vim`, `git`, and `tree`

\- Verify installations

\- Exit and manage the container



\---



\## Step 1: Create and Enter the Container



Run on the EC2 host to create a container named `test` and log into it:



```bash

docker run -it --name test ubuntu bash



