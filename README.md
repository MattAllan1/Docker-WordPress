# Build a WordPress dev environment with Docker

## Objective

- Install and setup Docker
- Create a Docker Compose file to scaffold out containers
- Enable HTTPS and keep MySQL data persistent
- Use the wp-cli tool without having to install it locally

### Skills Learned

By completing this lab, I will gain hands-on experience with:
Docker Installation and Setup: Learn how to install Docker on your system and set it up for managing containers efficiently.
Docker Compose: Understand how to utilize Docker Compose to define and manage multi-container Docker applications, simplifying the process of orchestrating complex environments.
Containerization Best Practices: Discover best practices for configuring Docker containers, including enabling HTTPS for secure communication and ensuring persistent storage for MySQL data.
WordPress Development: Learn how to leverage Docker for WordPress development, enabling rapid prototyping and testing in a consistent and isolated environment.
wp-cli Integration: Explore how to use the wp-cli tool within Docker containers, eliminating the need to install it locally and streamlining WordPress management tasks.

### Tools Used

- Linode - Cloud Hosting Platform
- Solar Putty - To connect to the platform
- Docker - To create the containers

## What is Docker

Docker is an open-source platform that automates the deployment, scaling, and management of applications inside containers. Containers are lightweight, portable, and self-sufficient units that encapsulate the application code, runtime, system tools, libraries, and settings required to run the application. Docker provides a standardized way to package and distribute applications, allowing developers to build, ship, and run their applications seamlessly across different environments, from development to production. With Docker, developers can create isolated environments for their applications, ensuring consistency and reliability across various infrastructure platforms, whether it's on-premises, in the cloud, or hybrid environments.

## What is Wordpress

WordPress is a popular open-source content management system (CMS) that allows users to create and manage websites easily. It started as a blogging platform in 2003 but has since evolved into a versatile tool for building various types of websites, including blogs, e-commerce stores, portfolios, forums, and more.
WordPress is built on PHP and uses a MySQL database. It provides a user-friendly interface, allowing users to add and edit content, customize the appearance of their sites using themes, and extend functionality with plugins.

## Step 1 - Installing Docker Desktop



## Step 2 - Downloading Wordpress
Recommend PHP 7.4 or greater and MySQL version 8.0 or MariaDB version 10.4 or greater.

```
docker pull alpine
docker run -d -t --name dockeralpine alpine
docker ps
docker exec -it dockeralpine sh
exit
```

Video of the above process | 'https://youtu.be/ef9156rysAY'
