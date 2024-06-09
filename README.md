
# Monolithic and Microservice Architectures

## Introduction

This repository provides a brief overview and example setups for both Monolithic and Microservice architectures using AWS.

## Monolithic Architecture

In the Monolithic architecture, the entire application (WordPress and MySQL) runs on a single EC2 instance.

### Steps:
1. **Launch an EC2 Instance**: Use Amazon Linux 2 AMI.
2. **Install Apache, PHP, and MySQL**: Install and configure required software on the instance.
3. **Install WordPress**: Download and configure WordPress to connect to the local MySQL database.
4. **Complete WordPress Setup**: Access the WordPress setup via a web browser and follow the on-screen instructions.

## Microservice Architecture

In the Microservice architecture, WordPress and MySQL run on separate EC2 instances.

### Steps:

### MySQL Instance:
1. **Launch EC2 Instance**: Use Amazon Linux 2 AMI.
2. **Install and Configure MySQL**: Install MySQL, create a database and user, and allow remote access.

### WordPress Instance:
1. **Launch EC2 Instance**: Use Amazon Linux 2 AMI.
2. **Install Apache and PHP**: Install required software on the instance.
3. **Install WordPress**: Download and configure WordPress to connect to the remote MySQL instance.
4. **Complete WordPress Setup**: Access the WordPress setup via a web browser and follow the on-screen instructions.

## Conclusion

This guide provides a basic setup for both monolithic and microservice architectures using AWS EC2 instances. Each 

