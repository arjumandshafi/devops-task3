Task 3: Create a Docker Container using Terraform
==================================================

 Goal:

Use Terraform to create and run a Docker container on your local computer.

🧰 What You Need:

1. Docker (must be installed and running)
   - Download from: https://www.docker.com/products/docker-desktop

2. Terraform (must be installed)
   - Download from: https://developer.hashicorp.com/terraform/downloads

📁 Files in This Folder:

- main.tf        --> This is the Terraform configuration file.
- README.txt     --> This guide file.

📂 Step-by-Step Instructions:

1. Open your terminal or command prompt.

2. Go to the folder where this file and main.tf are located.
   Example:
   cd -NAVIAGTE TO THE TASK FOLDER

3. Make sure Docker is running.
   Open Docker Desktop or start the Docker service.

4. Run this command to initialize Terraform:
   terraform init

5. Run this command to see what Terraform plans to do:
   terraform plan

6. Run this command to create the Docker container:
   terraform apply

7. To check if the container is running, run:
   docker ps

   You should see your container listed.

🧹 How to Delete the Container:

To stop and remove the container, run:

   terraform destroy
