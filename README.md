## Apache2-Web-Hosting-Ubuntu-EC2-Instance-with-HTTPS-and-Free-SSL-Certificate
This repository provides a comprehensive guide to:
✅ Setting up an Ubuntu EC2 instance for web hosting.
✅ Installing and configuring Apache2 to serve your web content.
✅ Securing your website with HTTPS using a free SSL certificate from Let’s Encrypt.
✅ Deploying a custom domain with professional configurations.

Designed as more than just a tutorial, this project serves as a complete toolkit for creating a secure, scalable, and reliable web server aligned with modern web standards. Whether you're new to web hosting or an experienced developer, this repository will enhance your skills and deepen your understanding of hosting and web security.

## Prerequisites
Before diving into this project, here’s what you need to know to ensure a smooth experience:

1.  🔧 Basic Linux Command Skills: Familiarity with essential Linux commands will help you navigate and manage the server effectively.
2.  ☁️ EC2 Instance Setup: You should understand how to launch an EC2 instance and configure security groups to allow HTTP and HTTPS traffic.
3.  💻 Development Environment: Tools like Git Bash or Visual Studio Code (VSCode) will be your companions for managing files and running commands.
With these basics in place, you’re all set to get started! 🚀

## Part 1: Launching the Ubuntu WebPage-01 Instance

1. Go to the AWS Console, click “Launch Instance,” and name the instance “webpage-01.”
2. Choose **Ubuntu** for the operating system.
3. Ensure the instance type is **free-tier eligible** to prevent extra charges.
4. Create a new key pair named **webpage-key-pair**.
5. Under the network settings, enable **HTTP** and **HTTPS** traffic from the internet.
6. Click **Launch Instance**, and your instance will be up and running.

## Part 2: Updating the Instance and Installing Apache2 Web Server

1. SSH into your instance using your preferred terminal, whether it’s **Gitbash**, **Visual Studio Code**, or **Termius**. Your instance should now be connected.
   
2. Run the following command to update your instance and install **Apache2**:

   ```bash
   sudo apt update -y
   sudo apt install apache2 -y

3. To check if Apache2 is running correctly, use the command below:

```bash
sudo systemctl status apache2





## Part 2: Updating the Instance and Installing Apache2 Web Server



























































