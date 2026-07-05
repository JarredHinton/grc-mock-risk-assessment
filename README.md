TechXYZ Mock Risk Assessment

A sample GRC (Governance, Risk, and Compliance) deliverable built for a fictional cloud photo-storage company, TechXYZ. This project was created to demonstrate practical risk assessment and policy-writing skills: identifying realistic risks, scoring them, proposing treatment plans, and translating that analysis into a company policy.

Project Overview

TechXYZ is a cloud-based photo storage and sharing SaaS platform (~50,000 users, hosted on AWS) that handles sensitive customer content, including images and metadata that may involve minors. This assessment walks through the core GRC workflow for a company in that position.

What's in this repo

Company Profile.pdf — Overview of TechXYZ's business model, key assets, user base, and regulatory considerations. This sets the context that everything else in the assessment is built on.

TechXYZ_Risk_Matrix.xlsx — A risk register covering 8 realistic risks for a company like TechXYZ (e.g., S3 bucket misconfiguration, phishing/account compromise, ransomware, DDoS). Each risk is scored on Likelihood (1–5) and Impact (1–5), multiplied into a Risk Score, and paired with a specific treatment plan. Risk scores are color-coded (green/yellow/red) to make severity easy to scan at a glance.
Acceptable Use Policy.pdf — A 1-page policy defining acceptable use of TechXYZ systems for employees and contractors, covering scope, prohibited activities, data handling, monitoring, and enforcement.

Methodology

Each risk in the matrix was scored using a standard Likelihood × Impact model (both rated 1–5), producing a score from 1–25:
1–8: Low risk
9–14: Medium risk
15–25: High risk

I color coordinated the Risk Score to express the significance of each category.

Treatment plans were written to map directly to the specific risk rather than generic advice — e.g., the response to "compromised admin account via phishing" focuses on MFA, phishing simulations, and anomaly detection, while "data loss via accidental deletion" focuses on backups and restore testing.

Why this project

Risk assessment and policy writing are core, everyday deliverables in GRC roles, but they're hard to showcase compared to a coding portfolio. This project was completed as part of a structured GRC learning curriculum, applying core risk assessment and policy-writing concepts to a realistic scenario. It demonstrates that process end-to-end: identifying assets and risk context, scoring and prioritizing risk, and translating that into an actionable governance document.
