# 📊 AWS + Power BI: Ticket Quality Dashboard



This mini project simulates what a Quality Assurance Analyst might do in a contact center environment using AWS and Power BI.

---

## Project Summary

Support ticket data is stored in AWS S3 and downloaded for analysis in Power BI. The goal is to identify trends in agent performance and SLA compliance, just like a QA analyst would in a real-world role.


---

## 📸  Power BI Report Screenshots

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

*Click on each report to view full size*

---

## Tools Used

- **AWS S3** – for uploading and storing mock ticket data
- **Power BI** – for creating a dashboard to track support performance
- **Excel/CSV** – used to generate realistic ticket data

---

## Dashboard Features

- Total Tickets Handled by Agent
- Overall SLA Met vs Missed

---

## Trello Project Board 5/19/2025

!{}(https://github.com/TammyTheAnalyst/aws-powerbi-ticket-quality-dashboard/blob/main/images/Screenshot%20(4694).png)

---

## Screenshots of Bucket created and csv with ticket data uploaded into AWS S3

![Bucket](https://github.com/TammyTheAnalyst/aws-powerbi-ticket-quality-dashboard/blob/main/images/Screenshot%20(4691).png)
![Support tickets csv data](https://github.com/TammyTheAnalyst/aws-powerbi-ticket-quality-dashboard/blob/main/images/Screenshot%20(4692).png)

---


## Folder Structure

data/ → contains support_tickets.csv (mock file)
images/ → contains screenshots of AWS steps and Power BI dashboard
README.md → this file

--







