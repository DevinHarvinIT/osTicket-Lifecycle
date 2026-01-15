# OS Ticket Help Desk Lifecycle Lab  
Business Critical Incident Escalation and Resolution

![Lab Header Placeholder](images/header.png)

## Overview

This lab demonstrates a complete IT help desk ticket lifecycle using OS Ticket, from initial end user intake through triage, escalation, remediation, and resolution. The scenario simulates a business critical outage impacting a financial services organization and highlights proper prioritization, SLA management, escalation workflows, and professional communication practices.

The focus of this lab is not only technical execution, but also documenting decision making and maintaining clear communication throughout the lifecycle of a ticket.

---

## Environment and Tools Used

Cloud Platform  
Microsoft Azure Cloud

Ticketing System  
OS Ticket built and configured from scratch

Operating System  
Windows  
Accessed from macOS using Microsoft Remote Desktop for enterprise style workflow

Supporting Components  
Azure Virtual Machines  
Web server stack supporting OS Ticket  
Database services required for ticket storage  
Agent and end user role configuration  

---

## Ticket Lifecycle Framework

This lab follows a standard enterprise help desk lifecycle model:

Intake  
Assignment and Communication  
Issue Investigation and Escalation  
Resolution and Closure  

Each step below maps directly to one or more phases of this lifecycle.

---

## Step 1  
End user submits support ticket via customer portal

An end user submits a support request through the OS Ticket customer portal reporting a service outage. The ticket includes a detailed description of the issue and is successfully logged into the system.

Screenshots to include  
Customer portal landing page  
Ticket submission form with issue details entered  
Ticket submission confirmation screen

---

## Step 2  
Support agent accesses ticket for initial triage

The IT support agent logs into the OS Ticket agent portal, locates the newly submitted ticket, and reviews the reported issue to begin triage.

Screenshots to include  
Agent login screen  
Opened ticket displaying reported outage details

---

## Step 3  
Document initial impact assessment and verification

The support agent verifies the reported issue by contacting the end user and confirming the scope of impact. Findings are documented internally to support escalation decisions.

Screenshots to include  
Internal note documenting user confirmation and business impact

---

## Step 4  
Escalate severity and apply business critical controls

Based on confirmed impact, the ticket is escalated to reflect business critical severity. Priority, SLA, and help topic are updated to align with emergency response standards.

Screenshots to include  
Priority level updated to Emergency  
SLA updated to Sev A  
Help topic updated to Business Critical Outage

---

## Step 5  
Communicate escalation and next steps to end user

The support agent posts a customer facing response acknowledging the issue, confirming escalation, and setting expectations for next steps.

Screenshots to include  
Public reply sent to end user

---

## Step 6  
Reassign ticket to SysAdmins team

Due to the technical nature of the outage, the ticket is reassigned to the SysAdmins team for advanced troubleshooting and remediation.

Screenshots to include  
Ticket reassigned to SysAdmin agent  
Department transfer to SysAdmins team

---

## Step 7  
Remediation, correspondence tracking, and service restoration

The SysAdmin investigates the root cause of the outage, performs corrective actions, and restores service functionality.

Throughout the duration of the ticket, detailed correspondence is maintained between agents and teams. This ensures both the IT organization and the end user have continuous visibility into progress, actions taken, and resolution status.

Maintaining a complete correspondence log is a core help desk practice and is critical for accountability, auditing, and clear communication.

Screenshots to include  
Internal notes documenting root cause and remediation steps  
Full correspondence log showing the lifecycle of the ticket  
Confirmation message indicating service restoration

---

## Step 8  
Resolve and close ticket

After service restoration is confirmed with the end user, the ticket is marked as resolved and formally closed to complete the incident lifecycle.

Screenshots to include  
Ticket resolution dialog  
Ticket status updated to Resolved or Closed

---

## Skills Demonstrated

Help desk ticket intake and triage  
Business critical incident management  
SLA prioritization and escalation workflows  
Professional internal and external communication  
Cross team escalation and collaboration  
Incident documentation and audit trail management  
Azure hosted service troubleshooting context  
