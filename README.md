# EC2-Instance
The goal of this project is to create an AWS account, set up a Linux server on AWS EC2, and deploy a simple static website. This project helped me to gain hands-on experience with cloud computing, specifically with Amazon Web Services (AWS).

### Steps
- Launched an Ubuntu server in aws in t2.micro instance type.
- And Configured the Security group to allow inbound traffic on ports 22 (ssh) and 80 (http).
- After, connected to my instance using SSH.
- Then, updated the system packages and installed the nginx web server.
```bash
sudo apt update && sudo apt install nginx
```

- Furthermore, checked the nginx default site is up or not using the public ip of the instance.
- It's running. Then, removed the index.nginx-debian.html file in /var/www/html directory.
- Next, downloaded my static site from the git repository using git clone.
- Then, moved the index.html file and folders in /var/www/html directory.
- After, checked the static site is running or not using the public ip of the instance.
- The static site is running successfully.


![loading...](images/static-site.png)

### Project Description URL
https://roadmap.sh/projects/ec2-instance

