
=======
# Movie Booking System 


## Architecture Diagram

The architecture diagram provides a visual representation of the system's structure, showcasing the interaction between the client application, server, and external services such as the Stripe Payment gateway.

![Architecture Diagram](/images/movie_booking_system_architecture.png)

## Component Diagram

 component diagrams illustrates the components of the system and how they interact with one another, ensuring modularity and ease of maintenance.

![Server Component Diagram](/images/server_component.png)

![Client Component Diagram](/images/client_component.png)

## AWS Deployment Diagram

Deployed  application on AWS, utilizing services such as EC2, S3, and RDS to ensure scalability and reliability.

![AWS Deployment Diagram](/images/AWSDeploymentDiag.png)

## Cloud Deployment

- Deployed on AWS Cloud using EBS.
- Enabled Auto Scaling up to 3 instances and used ELB for load balancing.
- Added Alerts for status updates.

## Features

- **User Authentication:** Secure login and registration system for users.
- **Movie Browsing:** Users can browse currently showing and upcoming movies.
- **Ticket Booking:** A feature-rich booking system with support for selecting seats and applying discounts.
- **Membership Options:** Users can choose between Regular and Premium membership options.
- **Analytics Dashboard:** For theater employees to track occupancy and movie popularity.
- **Cloud Deployment:** Robust deployment on AWS for optimal performance and uptime.


## BurnDown Chart

![Burndown](/images/burndown.png)

## Getting Started

To run the project locally, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies for both the client and server.
3. Ensure that MongoDB is running on your local machine or use an external MongoDB service.
4. Start the server by running `npm start` in the server directory.
5. Start the client by running `npm start` in the client directory.

For detailed instructions, refer to the documentation provided within each directory.

## Documentation

Find all  project documentation,and more in the [documentation folder](/documentation/).

## Links
1. [Project Journal](/documentation/CMPE202-AGWIZ-JOURNAL.pdf)
2. [Project Board](/documentation/project_board/)
3. [UI Wireframes](/documentation/AGILEWIZARDS-WIREFRAMES.pdf)




