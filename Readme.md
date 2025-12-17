Lamp-Ansible-Project
=
Introduction
=
This project demonstrates fully automated deployment of a LAMP stack (Linux, Apache, MariaDB, PHP) on Amazon Linux using Ansible. The stack includes Apache (httpd), MariaDB, and PHP (php-fpm) with a custom pink-themed PHP status page deployed automatically.

The goal of this project is to showcase hands-on DevOps automation skills and best practices for server provisioning.

Architecture
=
Flow:
=
✅User accesses the application via browser

✅Apache (httpd) handles HTTP requests

✅PHP processes dynamic content

✅MariaDB manages and stores application data

Technologies Used
=
● Ansible – Configuration management & automation

● Amazon Linux – Target operating system

● Apache (httpd) – Web server

● MariaDB – Database server

● PHP & PHP-FPM – Backend scripting

● AWS EC2 – Cloud compute

EC2 Instance
=
<img width="1881" height="876" alt="Screenshot 2025-12-16 165642" src="https://github.com/user-attachments/assets/bcc0f7d0-764c-4c66-a56c-4794361c7fa0" />

Ansible Playbook Highlights
=
● Installs required LAMP packages

● Starts and enables services automatically

● Deploys a custom pink-themed PHP status page

● Ensures idempotent and repeatable execution

How to Run the Project
=
````md
## 1. Clone the repository

```bash
git clone <your-repo-url>
````

## 2. Run the Ansible playbook

```bash
ansible-playbook lamp.yml
```

<img width="1898" height="574" alt="Screenshot 2025-12-16 165916" src="https://github.com/user-attachments/assets/fcf0f4c3-8d9e-4eaf-ab53-ffdce1db166a" />


3.Access the application in browser
=

     http://<EC2-PUBLIC-IP>/



Project Output
=

✅ Apache (httpd) running

✅ MariaDB service status

✅ PHP version

✅ Server hostname

✅ Server IP address

✅ Date & time


<img width="1530" height="937" alt="Screenshot 2025-12-16 170551" src="https://github.com/user-attachments/assets/f26b1ee7-204c-40c7-aeea-fc18ff4a39ff" />

Conclusion
=
This project successfully demonstrates the end-to-end automation of a LAMP stack on Amazon Linux using Ansible. By leveraging configuration management, the setup ensures consistency, repeatability, and reliability across deployments.


Through this implementation, core DevOps practices such as infrastructure automation, service orchestration, and application deployment are showcased. The custom pink-themed PHP status page provides a clear validation of Apache, PHP, and MariaDB services running together.




   







