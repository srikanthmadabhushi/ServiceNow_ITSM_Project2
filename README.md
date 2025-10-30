# ServiceNow_ITSM_Project2
# ServiceNow ITSM + GenAI | Incident Summary Generator

## Overview
This project demonstrates how a Generative AI-style flow can auto-generate summaries for resolved or closed incidents in ServiceNow ITSM, using the **ServiceNow Personal Developer Instance (PDI) – Yokohama release**.

## Flow Logic
1. Trigger: Incident Updated
2. If: State is Resolved OR Closed
3. Update Record: Fill AI Summary field with Short Description, Assignment Group, and Close Notes.

## Example Output
Incident about VPN not connecting  
Assigned to Network Support  
Resolved by John Doe  
Auto-generated summary for documentation.

## Outcome
Automates post-resolution documentation and simulates Generative AI summarization within ServiceNow.

## Environment
ServiceNow Personal Developer Instance (PDI): **Yokohama Release**

## Diagram
![Flow Diagram](Diagrams/ITSM_GenAI_Incident_Summary.png)

## Skills Demonstrated
ServiceNow ITSM | Flow Designer | AI Automation | Predictive & Generative AI Simulation | Yokohama PDI
