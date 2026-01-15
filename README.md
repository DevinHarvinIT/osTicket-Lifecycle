# OS Ticket – Business Critical Outage Ticket Lifecycle

This lab demonstrates a complete help desk ticket lifecycle using osTicket, from initial end user submission through escalation, remediation, and closure. The scenario simulates a business critical outage requiring priority escalation, SLA enforcement, and cross team collaboration.

## Environments and Technologies Used

• osTicket  
• Web based ticket submission portal  
• IT support agent console  
• SysAdmin escalation workflow  

## Operating Systems Used

• Windows Server  
• Windows Client  

## Lab Overview

An end user submits a support ticket reporting a business critical system outage. The IT support team triages the ticket, escalates severity, applies an appropriate SLA, and transfers the issue to the SysAdmins team. The SysAdmin resolves the issue, documents the fix, and closes the ticket.

---

## Step 1: End User Submits Support Ticket

The end user submits a new support request through the osTicket customer portal.

![End user submits ticket](images/shot1.png)

---

## Step 2: End User Provides Ticket Details

The end user completes the ticket form describing the issue and submits the request. A confirmation message verifies successful ticket creation.

![Ticket details entered](images/shot2.png)  
![Ticket submission confirmation](images/shot3.png)

---

## Step 3: IT Support Agent Authenticates into osTicket

The IT support agent logs into the osTicket agent panel to begin triage.

![Agent login](images/shot4.png)

---

## Step 4: Support Agent Locates and Opens Submitted Ticket

The agent locates the newly submitted ticket and opens it for review.

![Locate and open ticket](images/shot5.png)

---

## Step 5: Document Internal Triage Notes

Internal notes are added to document initial triage and verification steps.

![Internal triage note](images/shot6.png)

---

## Step 6: Update Ticket Priority to Emergency and Document Impact

The ticket priority is escalated to Emergency based on confirmed business impact.

![Priority updated to Emergency](images/shot7.png)

---

## Step 7: Apply Sev A SLA Based on Business Impact

A Sev A SLA is applied to enforce rapid response and resolution timelines.

![SLA updated to Sev A](images/shot8.png)

---

## Step 8: Reclassify Ticket Under Business Critical Outage

The help topic is updated to reflect a Business Critical Outage.

![Help topic updated](images/shot9.png)

---

## Step 9: Post Customer Facing Response Outlining Escalation and Next Steps

A response is sent to the end user explaining escalation and next actions.

![Customer response posted](images/shot10.png)

---

## Step 10: Reassign Ticket to SysAdmins Team for Advanced Remediation

The ticket is reassigned to the SysAdmins team for advanced troubleshooting.

![Reassign ticket](images/shot11.png)  
![Department transfer](images/shot12.png)

---

## Step 11: SysAdmin Authenticates and Performs Remediation

A SysAdmin logs in, investigates the issue, and restores system functionality.

![SysAdmin response and remediation](images/shot13.png)

---

## Step 12: Document Resolution and Close Ticket

The resolution is documented and the ticket is marked as resolved and closed.

![Ticket resolved](images/shot14.png)

---

## Step 13: Review Complete Ticket Lifecycle and Audit Trail

The full ticket history is reviewed, showing priority changes, SLA updates, escalations, and resolution.

![Ticket lifecycle history](images/shot15.png)

---

## Outcome

This lab demonstrates real world help desk workflows including triage, escalation, SLA enforcement, cross team collaboration, and proper documentation throughout the ticket lifecycle.
