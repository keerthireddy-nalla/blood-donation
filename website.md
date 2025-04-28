# Blood Donation Website Documentation

## Abstract

This document provides comprehensive documentation for a Blood Donation website designed to facilitate and promote blood donation activities. The website serves as an informational and registration platform for potential blood donors, educating visitors about the importance of blood donation, eligibility criteria, and the donation process. Built with HTML and CSS, this static website is containerized using Docker and implemented with a CI/CD pipeline using Jenkins for automated deployment. The website aims to increase awareness about blood donation and provide a simple interface for users to register as donors, potentially saving lives through their contributions.

## 1. Introduction

### 1.1 Purpose
The Blood Donation website was created to:
- Raise awareness about the importance of blood donation
- Educate users about blood donation eligibility and processes
- Provide a platform for potential donors to register
- Connect donors with blood donation organizations

### 1.2 Target Audience
- Potential blood donors
- People seeking information about blood donation
- Blood donation organizations and healthcare professionals
- Community outreach coordinators

## 2. Website Structure

### 2.1 Pages Overview
The website consists of multiple interconnected pages:

| Page | Filename | Description |
|------|----------|-------------|
| Home | blood.html | Main landing page with donation form and navigation |
| Login | sign.html | User login interface |
| Registration | reg.html | New user registration page |
| Benefits of Donation | wspdb.html | Information about why people should donate blood |
| Eligibility | wcgb.html | Details about who can donate blood |
| Ineligibility | wsngb.html | Information about who should not donate blood |
| Contact | contact.html | Contact information and form |

### 2.2 Navigation System
The website features an intuitive navigation menu that allows users to access all main sections from the home page. The navigation links are clearly labeled and prominently displayed, ensuring easy access to all content.

## 3. Features and Functionality

### 3.1 Donor Registration
The website includes a registration form that collects essential information from potential donors:
- Personal details (name, gender, age)
- Location information (state)
- Blood group selection
- Submission functionality

### 3.2 Educational Content
The website provides comprehensive educational content about blood donation:
- Importance and benefits of blood donation
- Eligibility criteria for donors
- Restrictions and contraindications for blood donation
- Step-by-step explanation of the donation process

### 3.3 Multimedia Elements
The website incorporates multimedia elements to enhance user experience:
- Embedded instructional videos about blood donation
- Relevant images that illustrate the donation process
- Motivational content to encourage donation

### 3.4 User Authentication
The website includes basic authentication functionality:
- Login system for returning users
- Registration system for new users

## 4. Technical Implementation

### 4.1 Front-End Technologies
- HTML5: Used for structuring the website content
- CSS3: Used for styling and responsive design
- JavaScript: Used for interactive elements and form validation

### 4.2 Deployment Architecture
The website is deployed using a containerized approach:
- Docker: Used to containerize the static website with Nginx as the web server
- Docker Compose: Used to define and manage the application services
- Jenkins: Implements CI/CD pipeline for automated building and deployment

### 4.3 CI/CD Pipeline
The website implements a continuous integration and deployment pipeline using Jenkins:
- Source code management integration
- Automated Docker image building
- Automated deployment via Docker Compose

## 5. Maintenance and Updates

### 5.1 Content Updates
Content updates can be made by editing the HTML files. Major sections that may require periodic updates include:
- Eligibility criteria according to latest medical guidelines
- Educational content about blood donation
- Contact information

### 5.2 Technical Maintenance
Technical maintenance involves:
- Updating Docker configurations as needed
- Monitoring and maintaining the Jenkins pipeline
- Ensuring proper functioning of forms and navigation
- Updating dependencies and security patches

## 6. User Guide

### 6.1 Accessing the Website
Users can access the website at the URL provided by the deploying organization, typically at `http://<server_ip>:8081` as configured in the docker-compose.yml file.

### 6.2 Navigating the Website
1. Start at the home page (blood.html)
2. Use the navigation menu to access different sections
3. Fill out the donor registration form to register as a donor
4. Access educational content to learn more about blood donation
5. Use the login system for returning visitors

### 6.3 Donation Process
The website outlines the donation process in four simple steps:
1. Fill out the registration form
2. Complete a brief medical check-up (approximately 5 minutes)
3. Donate blood (approximately 8 minutes)
4. Take refreshments (approximately 10 minutes)

## 7. Conclusion

The Blood Donation website serves as an essential tool for promoting blood donation and connecting donors with donation opportunities. Its simple design, educational content, and registration capabilities make it an effective platform for blood donation campaigns. The implementation of Docker and Jenkins ensures reliable deployment and easy maintenance.

---

*Last updated: April 25, 2025*
