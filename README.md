# Pet Store E-commerce Website

## Introduction

This project is an e-commerce platform built using the Django framework. It serves as a modern and user-friendly solution for pet owners to conveniently purchase pet supplies, accessories, and food online. The platform offers several advantages for the website owner, including:

- **Improved Customer Engagement**: Features such as personalized recommendations, order history tracking, and loyalty programs enhance customer satisfaction and encourage repeat purchases.
- **Efficient Operations**: Automated order processing, inventory management, and reporting tools streamline business operations and reduce manual workload.
- **Data-driven Insights**: Analytics and reporting functionalities provide valuable insights into customer behavior, product performance, and market trends, enabling informed business decisions and targeted marketing strategies.

Our Pet Store E-commerce Website aims to not only meet the needs of pet owners but also provide tangible benefits for the website owner, driving growth and success in the competitive e-commerce landscape.

The website is currently under development, in parallel with my studies in the university. The current template is temporary and intended only for development purposes. I am currently collaborating with a UI/UX designer for the final product, and I will build and integrate the design into the template.

- **Link**: https://monkfish-app-m4242.ondigitalocean.app/

## Background

This project emerged from the need to overcome limitations experienced by a pet store operating on the Joomla framework, particularly concerning customization. The Joomla-based website dealt with complexities due to its cluttered code structure, involving numerous plugins and extensions, leading to high expenses. Building the website with Django provided a solution, offering a more flexible and robust framework, which enhances user capabilities.

## Features

- **Product Catalog**: Explore a diverse range of pet products, encompassing categories, tags, attributes, and customizable options for items.

- **User Authentication and Authorization**: Enable secure account creation, login, and profile management for customers, including the option for authentication via Google accounts.

- **Prices**:  Implement flexible pricing policies per user, accommodating factors such as membership status, location, and custom parameters.

- **Shopping Cart**: Interactive cart functionality for adding, removing, and updating items before checkout.

- **Order Management**: Efficient order processing, status tracking, and order history management.

- **Payment Integration**: Seamless integration with popular payment gateways for secure online transactions.

- **Responsive Design**: Ensure optimal user experience across devices with a fully responsive design, leveraging AJAX technology for seamless and dynamic content loading, enhancing user interaction and performance.

## Technologies Used

- **Django**: High-level Python web framework for rapid development and clean, pragmatic design.
- **HTML/CSS/JavaScript**: Front-end technologies for UI design and interactivity, including jQuery for enhanced DOM manipulation and event handling.
- **Bootstrap**: Front-end framework for responsive web design.
- **SQLite/MySQL**: Database management systems for storing and retrieving data.
- **Git/GitHub**: Version control and collaboration platform.


## Deployment Process

Our deployment process involves:

1. **Code Deployment**: I am using Git and GitHub for version control and collaboration. Changes are pushed to the repository, and deployment is triggered automatically through Continuous Integration/Continuous Deployment (CI/CD) pipelines.

2. **DigitalOcean Droplets**: The Django application is deployed on DigitalOcean droplets, which are virtual private servers (VPS) running Linux. I utilize Docker containers for containerization and easier deployment management.

3. **Database Configuration**: Avian provides a connection string and credentials for my MySQL database. I configure the Django application to connect to the Avian database for data storage and retrieval.

4. **Static File Storage Configuration**: Static files are uploaded to AWS S3 buckets and configured in the Django settings to serve static assets from the S3 bucket URLs.

By leveraging these services and following best practices for deployment and infrastructure management, I ensure the reliability, scalability, and security of the Pet Store E-commerce Website in production.

