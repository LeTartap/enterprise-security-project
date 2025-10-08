# Enterprise Security Analysis: A Case Study for Rumble B.V.

This repository contains the deliverables for a group project for the **Enterprise Security** course at the University of Twente. The project involved a comprehensive security analysis and the development of a strategic defense plan for a real-world SaaS company.

## Table of Contents
1.  [Project Overview](#project-overview)
2.  [The Case Study: Rumble B.V.](#the-case-study-rumble-bv)
3.  [The Challenge: Threats & Risks](#the-challenge-threats--risks)
4.  [The Solution: A Multi-Layered Defense Strategy](#the-solution-a-multi-layered-defense-strategy)
5.  [Evaluation: Cost vs. Impact](#evaluation-cost-vs-impact)
6.  [Team Members](#team-members)
7.  [Project Deliverables](#project-deliverables)

## Project Overview

The objective of this project was to perform a thorough security assessment of a small, high-growth technology company. Our team was tasked with identifying critical vulnerabilities, analyzing potential business impacts, and proposing a prioritized and cost-effective set of security controls. The entire analysis, from threat modeling to implementation planning, is summarized in the project poster.

## The Case Study: Rumble B.V.

* **Company:** Rumble
* **Industry:** Automotive Software Development
* **Business Model:** A SaaS platform, "RumbleDirect," that simplifies vehicle claim and repair management on a usage-based monthly subscription.
* **Size & Status:** A small company with fewer than 10 full-time employees, currently experiencing exponential growth, making security an urgent priority.

## The Challenge: Threats & Risks

Our analysis identified that Rumble's primary risk lies in the severe **indirect losses** from a security breach, such as reputational damage and loss of client trust, which could be fatal for a growing company.

* **Threat Modeling:** An **Attack Tree** was developed to visualize potential attack vectors, mapping out paths an adversary could take to compromise the system.
* **Key Threat Categories:**
    * **DDoS & Virus Attacks:** Exploits targeting service availability and system integrity.
    * **Vulnerable Code & Unsecure Accounts:** Threats arising from software vulnerabilities and inadequate access control policies.

## The Solution: A Multi-Layered Defense Strategy

A holistic defense strategy was proposed, focusing on technical controls, access management, and process improvements. Each solution was evaluated for its usability based on the **ISO 9241-11** standard (effectiveness, efficiency, and satisfaction).

#### Technical Defenses
* **Web Application Firewall (WAF):** To protect against application-layer attacks.
* **Hardware Firewall:** Upgrading existing hardware to provide robust network-level protection.
* **System Hardening:** Enforcing antivirus use and timely system updates through a formal device policy.

#### Access & Policy Controls
* **Multi-Factor Authentication (MFA):** To enforce strong authentication, reducing the likelihood of account compromise by 99.9%.
* **Password Manager:** Mandating a company-wide password manager to eliminate weak or reused passwords.
* **Principle of Least Privilege:** Restricting access to sensitive data only to employees who absolutely require it for their roles.
* **Agile Workflow:** Implementing daily update meetings to improve communication and enable a faster, more adequate response to security incidents.

## Evaluation: Cost vs. Impact

All proposed solutions were mapped on a **Cost vs. Impact** matrix to provide a clear, data-driven basis for implementation priority. This analysis highlighted high-value solutions like the Password Manager (High Impact, Low Cost) and MFA as immediate priorities.

## Team Members
* Quinten van Breugel
* Narcisa Dobre
* David Galati
* Lena de Kraker
* Cheng Qi Wang

## Project Deliverables

* **[Final Project Poster](./Final%20poster%20Enterprise%20Security%20(7)%20(1).pdf)**: A high-resolution PDF of the project summary poster.
