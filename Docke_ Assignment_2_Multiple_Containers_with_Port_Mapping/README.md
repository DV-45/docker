\# Docker Assignment 2 – Multiple Containers with Port Mapping



This assignment demonstrates building a custom Docker image from Apache Tomcat, serving a simple `index.html` page, running multiple containers with different host ports, verifying browser access, and optionally pushing the image to Docker Hub.



\---



\## Objective

\- Build a custom image based on Tomcat

\- Serve a custom `index.html` page

\- Run multiple containers with different host port mappings

\- Verify access via browser

\- Push image to Docker Hub (optional)



\---



\## Prerequisites

\- Docker installed and running

\- EC2 instance or local Docker host

\- Inbound TCP ports `8081–8083` allowed in security group

\- Docker Hub account (optional for push/pull)



\---



\## Step 1: Create Project and HTML Page

```bash

mkdir -p \~/docker-tomcat

cd \~/docker-tomcat



cat > index.html << 'EOF'

<!DOCTYPE html>

<html>

<head><title>Docker Day 6</title></head>

<body style="font-family: Arial; text-align: center;">

&#x20; <h1>Welcome to Docker Day 6!</h1>

&#x20; <h2>Apache Tomcat Container</h2>

&#x20; <p>My custom HTML page is running inside Docker.</p>

</body>

</html>

EOF



