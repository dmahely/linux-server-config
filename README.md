# Project Description
_This project is the sixth and final project in the curriculum of Udacity’s Full Stack Web Developer Nanodegree._
The Linux Server Configuration project requires using an instance of Ubuntu on Amazon Lightsail, configuring it, securing it and deploying a web application on it. The hosted web application is the [item catalog application](https://github.com/dmahely/item-catalog).

# Completed Tasks
1. Updated all currently installed packages.
2. Configured the local timezone to UTC.
3. Created a new user `grader` and gave them sudo access. 
4. Configured the SSH-key authorization for the `grader` user.
5. Enforced SSH-key login.
6. Prohibited remote root login.
7. Configured the Uncomplicated Firewall ufw.
8. Installed various packages such as pip and git.
9. Changed the default SSH port.
10. Installed and configured Apache and PostgreSQL.
11. Cloned the Item Catalog web application repository from GitHub. 
12. Installed the application's dependencies such as sqlalchemy, Flask and oauth2client.

# Before Running the Program
The IP address of the server is 52.66.195.248. The SSH port is 2200.

To login as the grader user: `$ ssh -i ~/.ssh/udacity_key.rsa -p 2200 grader@52.66.195.248`

# Running the Application
Visit [http://ec2-52-66-195-248.ap-south-1.compute.amazonaws.com](http://ec2-52-66-195-248.ap-south-1.compute.amazonaws.com) on your browser.

# After Running the Program
You should be seeing the homepage of the item catalog web application.
![Homepage of Item Catalog Application](img/homepage.png?raw=true)

# Acknowledgments
https://github.com/chuanqin3/udacity-linux-configuration

https://github.com/iliketomatoes/linux_server_configuration

https://github.com/davidduckwitz/udacity-linux-server-config

https://github.com/sagarchoudhary96/P8-Linux-Server-Configuration
