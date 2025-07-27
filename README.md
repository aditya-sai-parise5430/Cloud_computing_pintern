# Cloud_computing_pintern

# Cloud Computing Internship Projects - AWS

[cite_start]This repository contains the major projects completed during my **Cloud Computing Hybrid Internship** with **Worisgo (1stop.ai)** from May 1, 2025, to June 30, 2025[cite: 1210, 1156, 1158]. It showcases two distinct, real-world cloud applications that demonstrate my skills in serverless architecture, cloud security, and web application deployment.

---

## 1. Serverless To-Do List Application

[cite_start]This project involved designing and implementing a fully serverless backend for a to-do list application using core AWS services[cite: 25, 26].

[cite_start]The primary objective was to build a scalable, cost-effective backend that performs CRUD (Create, Read, Update, Delete) operations without managing any traditional server infrastructure[cite: 26, 52, 53]. [cite_start]The architecture intentionally avoided AWS API Gateway to demonstrate a deeper understanding of direct service interaction and testing using the AWS CLI and Postman[cite: 35, 38, 64].

#### Key Responsibilities & Features:
* [cite_start]**Serverless Compute:** Engineered backend logic using **AWS Lambda** functions written in **Node.js** to handle all API requests[cite: 28, 78, 89].
* [cite_start]**NoSQL Database:** Utilized **Amazon DynamoDB** for persistent, scalable, and low-latency data storage for the to-do items[cite: 31, 82].
* [cite_start]**Cloud Management & Automation:** Managed and deployed all cloud resources programmatically using the **AWS Command Line Interface (CLI)**[cite: 40, 56].
* [cite_start]**Monitoring & Debugging:** Used **Amazon CloudWatch** to monitor function executions, trace errors, and debug the application, which was critical for improving the development feedback loop[cite: 41, 68].
* [cite_start]**Security:** Adhered to cloud security best practices by configuring specific **IAM roles** for the Lambda function and securely managing all credentials[cite: 43, 60, 943].

---

## 2. Secure User Login System with AWS Cognito & Laravel

[cite_start]This project involved building a secure, scalable, and cloud-integrated user authentication system[cite: 1219, 1248].

[cite_start]The goal was to offload the complexities of user authentication (sign-up, sign-in, token management) to a managed service while integrating it with a traditional web application stack[cite: 1228, 1231]. [cite_start]The system leverages **AWS Cognito** for identity management and a **Laravel (PHP)** application as the backend, deployed on a **LAMP (Linux, Apache, MySQL, PHP)** stack on an **AWS EC2** instance[cite: 1229, 1233, 1237].

#### Key Responsibilities & Features:
* [cite_start]**Managed Identity Service:** Configured an **AWS Cognito User Pool** to manage the entire user lifecycle, including password policies, token-based authentication, and a secure Hosted UI for login[cite: 1230, 1254, 1316].
* [cite_start]**Web Framework Integration:** Developed a robust backend using the **Laravel** framework, integrating the **AWS SDK for PHP** to communicate securely with Cognito services[cite: 1233, 1263, 1453].
* [cite_start]**Secure Authentication Flow:** Implemented the **OAuth 2.0 Authorization Code Grant** flow to handle user redirection and the secure exchange of tokens between Cognito and the Laravel application[cite: 1630].
* [cite_start]**Infrastructure as a Service (IaaS):** Demonstrated proficiency in deploying a full-stack web application on an **AWS EC2** virtual server, showcasing understanding of traditional cloud hosting environments[cite: 1237, 1331].

---

## Technologies Used

| Category                | Technologies                                                                          |
| ----------------------- | ------------------------------------------------------------------------------------- |
| **Cloud Platform** | Amazon Web Services (AWS)                                                             |
| **AWS Services** | [cite_start]Lambda, DynamoDB, Cognito, EC2, CloudWatch, IAM [cite: 77, 81, 94, 943, 1229, 1330]        |
| **Backend & Frameworks** | [cite_start]Node.js, Laravel (PHP), LAMP Stack [cite: 88, 1229, 1294]                              |
| **Databases** | [cite_start]DynamoDB (NoSQL), MySQL (SQL) [cite: 81, 1326]                                         |
| **Tools & Utilities** | [cite_start]AWS CLI, Postman, Git, VS Code, Composer [cite: 85, 91, 100, 1414]                       |


---

## Acknowledgement

[cite_start]These projects were created as deliverables for the **Cloud Computing Internship program at Worisgo / 1stop.ai**[cite: 1156, 1210]. I am grateful for the mentorship and hands-on experience gained during this program.
