# artifact-repository-manager-with-nexus
Setup and configuration of Nexus artifact repo on DigitalOcean droplet.

## Project Overview
This project demonstrates setting up and configuring Nexus on a DigitalOcean Droplet as an artifact repository manager, creating a Linux user, and deploying artifacts using Java Gradle and Maven projects. It follows security best practices by creating and configuring a new user with relevant permissions.

## Technologies Used
- Nexus
- DigitalOcean
- Linux
- Java
- Gradle
- Maven

## Project Steps
1. **Setup and Configure Nexus**: Provision a DigitalOcean Droplet and set up the server environment.
2. **Create and Configure User**: Create a new user on Nexus with limited permissions as a security best practice.
3. **Build and Upload Artifacts**: Deploy Java Gradle and Maven projects to Nexus by building and uploading JAR files.
   
## Skills Demonstrated
- Cloud infrastructure setup
- Basic Linux server administration
- Nexus rep management
- Application deployment with Gradle and Maven
- Security best practices

## Instructions

### Step 1: Setup Nexus
Run the `setup-nexus.sh` script to install Nexus and configure server settings on the DigitalOcean Droplet.

### Step 2: Create and Configure User
Run the `create-nexus-user.sh` script to add a new user with limited permissions for artifact management.

### Step 3: Deploy Artifacts
Build the Java projects with Gradle and Maven and deploy the JAR files to Nexus using the `deploy-artifacts.sh` script.

## Scripts
- scripts/setup-nexus.sh: Configures Nexus on the server.
- scripts/create-nexus-user.sh: Creates and configures a new user in Nexus with relevant permissions.
- scripts/deploy-artifacts.sh: Builds JAR files with Gradle and Maven, then uploads them to Nexus.













