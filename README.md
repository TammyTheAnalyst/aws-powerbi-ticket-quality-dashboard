# 📊 AWS + Power BI: Ticket Quality Dashboard



This mini project simulates what a Quality Assurance Analyst might do in a contact center environment using AWS and Power BI.

---

## Project Summary

Support ticket data is stored in AWS S3 and downloaded for analysis in Power BI. The goal is to identify trends in agent performance and SLA compliance, just like a QA analyst would in a real-world role.


---

## 📸  Power BI Report Screenshots

The following visuals were created in a Power BI **report** using support ticket data stored in AWS S3.

<p align="center">
  <img src="https://github.com/TammyTheAnalyst/aws-powerbi-ticket-quality-dashboard/blob/main/images/Screenshot%20(4696).png" alt="Tickets per Agent - Clustered Column Chart" width="45%" />
  &nbsp;&nbsp;&nbsp;
  <img src="https://github.com/TammyTheAnalyst/aws-powerbi-ticket-quality-dashboard/blob/main/images/Screenshot%20(4698).png" alt="SLA Met vs Missed per Agent - Stacked Bar Chart" width="45%" />
</p>

## Dashboard Features

- **Tickets Handled by Agent**: Ava, Ben, Leo, and Jade each handled a different number of support tickets.
  Ava handled the most, while Leo and Jade had fewer. This clustered column chart gives a quick view of agent workload.

- **SLA Met vs Missed by Agent**: The stacked bar chart shows how each agent performed on SLA compliance.
  Ben and Leo met all SLAs, while Ava and Jade had a mix of met and missed. This highlights who may need coaching.

*Click on each visual to view full size*

---

## Tools Used

- **AWS S3** – for uploading and storing mock ticket data
- **Power BI** – for creating a dashboard to track support performance
- **Excel/CSV** – used to generate realistic ticket data

---


## Trello Project Board 5/19/2025

![](https://github.com/TammyTheAnalyst/aws-powerbi-ticket-quality-dashboard/blob/main/images/Screenshot%20(4694).png)

---

## Screenshots of Bucket created and csv with ticket data uploaded into AWS S3

![Bucket](https://github.com/TammyTheAnalyst/aws-powerbi-ticket-quality-dashboard/blob/main/images/Screenshot%20(4691).png)
![Support tickets csv data](https://github.com/TammyTheAnalyst/aws-powerbi-ticket-quality-dashboard/blob/main/images/Screenshot%20(4692).png)

---


## Folder Structure

data/ → contains support_tickets.csv (mock file)
images/ → contains screenshots of AWS steps and Power BI dashboard
README.md → this file


---

## 💼 Real-World Job Roles This Project Supports

This project demonstrates hands-on experience in tools and tasks commonly used in the following roles:

- **Quality Assurance Analyst** – Auditing support tickets and tracking SLA performance using cloud-stored data and BI tools
- **Data Analyst** – Loading structured data from cloud storage (AWS S3), transforming it, and visualizing trends
- **Business Intelligence Analyst** – Building performance dashboards and reports to help leadership make data-driven decisions
- **Customer Support Operations Analyst** – Monitoring agent performance, customer satisfaction metrics, and compliance with service standards
- **CRM Analyst** – Analyzing ticket or case data, often exported from platforms like Salesforce or Zendesk

> 📌 Recruiters: This project highlights my ability to work with real-world support data using AWS and Power BI, create visual reports, and deliver insights aligned with business and quality goals.






