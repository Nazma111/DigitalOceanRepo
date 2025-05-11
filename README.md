# DigitalOceanRepo
Containerizing application  


Phase 1: Application Containerization

Choose Your Application:

You can either use the provided birthday reminder template (Node.js) or a simple application you're familiar with (Python/Flask, static HTML). For simplicity in this guide, let's assume you'll use the Node.js birthday reminder template.
   
   
   
phase 2 :Download or Clone the Template:

Go to the provided GitHub link: https://www.digitalocean.com/community/tutorials/automating-birthday-reminders-with-triggers


Phase 3: understand the Application:

Take a moment to look at the application files (app.js, package.json, etc.) to understand its basic functionality.


phase 4: Create a Dockerfile:

In the root directory of your application, create a file named Dockerfile



phase 5:Build the Docker Image:

Open your terminal, navigate to the directory containing the Dockerfile



Deploying to DigitalOcean Kubernetes (DOKS)

Create a DOKS Cluster:

In your DigitalOcean control panel, navigate to "Kubernetes" and create a new cluster.
Choose a region, Kubernetes version, and the number and size of your nodes. For this assignment, a small cluster with 2-3 nodes should suffice.
Configure kubectl to Access Your Cluster:

Once your cluster is created, DigitalOcean will provide instructions on how to download your cluster's configuration file (kubeconfig). Follow these instructions.
