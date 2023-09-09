# Technovate Workshop on OWASP

Welcome to the Technovate Workshop on OWASP (Open Web Application Security Project). In this workshop, we will delve into the fundamentals of OWASP attacks, focusing on understanding them from an attacker's perspective. Our workshop will encompass basic attacks across various domains, including Server Side, Client Side, Web Service, and Docker security.

## Prerequisites

Before you begin, please ensure you have the following prerequisites in place:

1. **Ubuntu VM with Docker Installed:**
   - You'll need an Ubuntu Virtual Machine (VM) for this workshop. If you haven't already set up an Ubuntu VM, follow the steps outlined below to install Docker on it.

## Setting Up an Ubuntu VM with Docker

Follow these steps to set up an Ubuntu VM with Docker:

1. **Create an Ubuntu Virtual Machine:**
   - Ensure you have an Ubuntu VM ready. If not, you can create one using your preferred virtualization platform (e.g., VirtualBox, VMware, Hyper-V, etc.)

2. **Install Docker:**
   - Once your Ubuntu VM is up and running, you'll need to install Docker. 
   ```
   sudo apt update
   sudo apt install apt-transport-https ca-certificates curl software-properties-common
   curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable"
   # Make sure you are about to install from the Docker repo instead of the default Ubuntu repo:
   apt-cache policy docker-ce
   ```

3. **Verify Docker Installation:**
   - After installing Docker, verify that it's correctly installed by running the following command in your terminal:
     ```
     docker --version
     ```

Now, you're all set with the necessary environment to participate in our OWASP workshop! If you encounter any issues during the setup process or have any questions, please don't hesitate to reach out to our workshop instructors for assistance.

We look forward to exploring the world of web application security with you during this workshop!
