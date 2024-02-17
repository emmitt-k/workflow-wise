# WorkFlowWise : Job Submission & Internal Workflow Management

WorkFlowWise is a comprehensive web-based application designed to streamline and enhance the internal part inspection and workflow management process within the organization. This application leverages a range of technologies to offer a user-friendly and efficient platform for managing job submissions, tracking, and communication between supervisors and technicians.

## Features

The "Job Submission & Internal Workflow Management" application offers a comprehensive set of features designed to optimize internal part inspection and workflow management processes within the organization:

1. **Efficient Job Submission**: Streamline the submission of internal part inspection requests using a user-friendly in-app form. Each submission is assigned a unique job tracking number, facilitating efficient tracking and management.

<img src="https://github-emmitt-markdown.s3.ap-southeast-1.amazonaws.com/WorkflowWise/2.jpg" width="400">

2. **Printable Request Details**: Generate printable request details, complete with QR codes, for easy attachment to inspection part containments. This feature ensures seamless tracking and reference.

3. **QR Code Integration**: Accept incoming inspection parts into the laboratory with ease by scanning QR codes. This simplifies the tracking process and enhances accuracy.

<img src="https://github-emmitt-markdown.s3.ap-southeast-1.amazonaws.com/WorkflowWise/4.jpg" width="400">

4. **Real-time Job Monitoring**: Empower lab technicians with the ability to monitor ongoing inspection jobs in real-time. The application automatically updates job statuses, ensuring transparency and accountability.

<img src="https://github-emmitt-markdown.s3.ap-southeast-1.amazonaws.com/WorkflowWise/3.jpg" width="400">

5. **Assignment and Communication**: Supervisors can assign inspection jobs to technicians using an intuitive in-app form. This creates comprehensive job documents with specific details. Additionally, a collaborative communication space, reminiscent of social media, allows supervisors and technicians to interact within the same platform, facilitating easy follow-up and updates.

6. **Job Timer**: Keep track of the time spent on each inspection job by each technician. Initiate time tracking with the click of a button and mark job completion when finished. The application automatically calculates time usage and Turnaround Time (TAT), promoting efficient workflow management.

<img src="https://github-emmitt-markdown.s3.ap-southeast-1.amazonaws.com/WorkflowWise/5.jpg" width="400">

7. **Notification System**: Stay informed and up-to-date with an in-app notification system and email notifications. Receive timely updates and important messages related to the inspection process.

<img src="https://github-emmitt-markdown.s3.ap-southeast-1.amazonaws.com/WorkflowWise/6.jpg" width="400">

These features collectively enhance the efficiency, transparency, and communication within the organization's internal part inspection and workflow management.


## Tech Stack

### Frontend
![Framework - Vue.js](https://img.shields.io/badge/Framework-Vue.js-2ea44f) [![Library - Vuex](https://img.shields.io/badge/Library-Vuex-2ea44f)](https://) [![Build Tool - Vite](https://img.shields.io/badge/Build_Tool-Vite-2ea44f)](https://) [![Library - Axios](https://img.shields.io/badge/Library-Axios-2ea44f)](https://) [![Library - Vue Router](https://img.shields.io/badge/Library-Vue_Router-2ea44f)](https://) [![QR Code Generation - qrcode.vue](https://img.shields.io/badge/QR_Code_Generation-qrcode.vue-2ea44f)](https://) [![PDF Generation - pdfmake](https://img.shields.io/badge/PDF_Generation-pdfmake-2ea44f)](https://) [![File Upload - filepond](https://img.shields.io/badge/File_Upload-filepond-2ea44f)](https://) [![Form Validation - vuelidate](https://img.shields.io/badge/Form_Validation-vuelidate-2ea44f)](https://) [![UI Component Library - PrimeVue](https://img.shields.io/badge/UI_Component_Library-PrimeVue-2ea44f)](https://) [![HTML/CSS/JS](https://img.shields.io/badge/HTML/CSS/JS-2ea44f)](https://)

- **Vue.js**: The core framework of the application, providing a dynamic and responsive user interface.

- **Vuex**: Used for state management to ensure data consistency and synchronization across components.

- **Vite**: The build tool chosen for its speed and efficiency in development.

- **Axios**: For making HTTP requests to the backend, offering a simple and intuitive way to handle asynchronous operations.

- **Vue Router**: Facilitating frontend page navigation and creating a seamless user experience.

- **qrcode.vue**: Utilized for generating QR codes for easy tracking and reference.

- **pdfmake**: Enables the generation of PDF documents for printable request details.

- **filepond**: Offers easy file upload capabilities within the application.

- **vuelidate**: Used for form validation, ensuring data integrity and reliability.

- **PrimeVue**: Provides a variety of pre-designed UI components for a polished user interface.

- **HTML/CSS/JS**: Standard web technologies used for front-end development.

### Backend
![Language - PHP](https://img.shields.io/badge/Language-PHP-eb4034) [![Framework - Laravel](https://img.shields.io/badge/Framework-Laravel-eb4034)](https://) [![Web Server - Apache](https://img.shields.io/badge/Web_Server-Apache-eb4034)](https://) [![Database - MySQL](https://img.shields.io/badge/Database-MySQL-346beb)](https://) [![Storage - MinIO](https://img.shields.io/badge/Storage-MinIO-ff7391)](https://)

- **PHP**: The backend of the application is built using PHP, known for its robustness and ease of use.

- **Laravel**: Laravel is used as the PHP framework, providing structure for handling API requests, data management, and user authentication.

- **Apache Web Server**: The Apache web server is used to serve the PHP application.

- **MySQL**: MySQL is the database management system of choice, ensuring data integrity, reliability, and efficient data retrieval.

- **MinIO**: MinIO, a high-performance object storage server, is integrated into the application to serve as the repository for various files, enabling easy storage and retrieval.

## License

This project is the proprietary code of Seagate Technology LLC. and is not open-source. Only README.md is provided here solely for the purpose of showcasing developer skills and project capabilities. Unauthorized use, reproduction, or distribution of this code is prohibited.

**© 2023 Seagate Technology LLC. All rights reserved.**
