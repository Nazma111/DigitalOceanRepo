# DigitalOceanRepo
Containerizing application  


Phase 1: Application Containerization - Birthday-Reminder-APP

Choose Birthday-Reminder-APP Application:

You can either use the provided birthday reminder template (Node.js) or a simple application you're familiar with (Python/Flask, static HTML). For simplicity in this guide, let's assume you'll use the Node.js birthday reminder template.
   
   
   


phase 2 :Download or Clone the Template:

Go to the provided GitHub link: https://www.digitalocean.com/community/tutorials/automating-birthday-reminders-with-triggers





Phase 3:Application Details for reference

Take a moment to look at the application files (app.js, package.json, etc.) to understand its basic functionality.


phase 4: Next step is to Create a Dockerfile

In the root directory of your application, create a file named Dockerfile







phase 5:Build the Docker Image 

 directory containing the Dockerfile





























Step 7: In Digital ocean Dashboard Deploying to DigitalOcean Kubernetes (DOKS)

Create a DOKS Cluster:

In your DigitalOcean control panel, navigate to "Kubernetes" and create a new cluster.
Choose a region, Kubernetes version, and the number and size of your nodes.
For this assignment, a small cluster with 2-3 nodes should sufficent.
Configure kubectl to Access Your Cluster:

Once your cluster is created, DigitalOcean will provide instructions on how to download your cluster's configuration file (kubeconfig).

 Follow these instructions:
 
 1.download a YAML file and then use the doctl command-line tool (DigitalOcean's CLI) to set your kubectl context.

2.Verify your kubectl configuration:
   kubectl get nodes

3.Create Kubernetes Deployment and Service YAML Files

4.Access Your Application , then add Loadbalancer and AutoScale application.

5.Horizontal Pod Autoscaling : last step to moniter the no of pods created to scale the application.


Thank you 
