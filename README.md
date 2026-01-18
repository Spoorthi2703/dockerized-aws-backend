Dockerized Backend in Secure AWS VPC
📌 Project Overview

This project demonstrates a secure two-tier architecture on AWS where a Dockerized backend service runs inside a private subnet and is accessed only through a public EC2 instance.

🛠 Technologies Used

AWS EC2

AWS VPC (Public & Private Subnets)

Docker

Linux


🏗 Architecture

Public EC2 acts as the entry point within a public subnet.

Backend application runs as a Docker container on a private EC2 instance.

Security Groups are used to restrict backend access only to the public EC2.

Backend service is not directly accessible from the internet.

🔐 Security Highlights

Backend EC2 has no public IP.

Network access is controlled using Security Group referencing.


🎯 Learning Outcome

Hands-on experience with AWS VPC networking

Practical Docker container deployment

Understanding secure backend isolation in cloud environments
