# ServiceNow ITSM Ticketing System Lab

ServiceNow ITSM Ticketing System Lab
By: Milton White

This project simulates real-world IT support operations using a ServiceNow incident management system. A total of 27 incident tickets were created and managed across multiple categories, including Inquiry/Help, Software, Hardware, Network, Database, and Password Reset.

The lab demonstrates hands-on experience with:

Incident lifecycle management (New → In Progress → On Hold → Resolved)
Ticket prioritization based on impact and urgency
Escalation procedures and On Hold reasons
Troubleshooting across multiple IT domains
Proper documentation using work notes and resolution notes

- Platform: ServiceNow Personal Developer Instance (PDI)
- Version: Australia
- Role: System Administrator (admin)
- Purpose: Simulate help desk ticketing system workflows

<img width="2557" height="1304" alt="01-servicenow-dashboard png" src="https://github.com/user-attachments/assets/9541936e-d647-4853-bf4e-52a0c01ee630" />

<img width="2241" height="515" alt="create-user-john_doe png" src="https://github.com/user-attachments/assets/2dac3371-79ef-47c9-8115-7b0d186296f5" />


Incident Simulation – Inquiry/Help
Ticket Type: Network Drive Access Issue
Priority: Low (P3)

Summary:
User reported inability to access the shared network drive. Initial troubleshooting confirmed correct permissions and group membership. The user lacked knowledge of the drive mapping procedure.
 
Actions Taken:
- Created incident ticket
- Contacted user and verified issue
- Confirmed permissions in Active Directory
- Guided user through mapping procedure
- Documented final resolution
  
Outcome:
Issue resolved independently without escalation. Demonstrated effective user guidance and incident resolution.
Screenshots:

<img width="2559" height="449" alt="01-inquiry-help-ticket png" src="https://github.com/user-attachments/assets/e84a03ad-4428-40af-a440-5d07ff886b55" />

<img width="2548" height="1028" alt="02-inquiry-help-in-progress png" src="https://github.com/user-attachments/assets/32ec727c-e4c3-4631-b7c2-1ebea8320f58" />

<img width="2558" height="1174" alt="03-inquiry-help-resolved png" src="https://github.com/user-attachments/assets/5f80ea00-3812-4154-b87f-9bc0c3ad6bfb" />

</>
Incident Simulation – Software Installation Issue
Ticket Type: Application Installation Failure
Priority: Medium (P2)

Summary:
The user could not install Microsoft Office due to permission/registry errors. Initial troubleshooting did not resolve the issue.
Actions Taken:
- Created incident ticket
- Contacted user to confirm details
- Performed initial troubleshooting (installer, admin rights)
- Escalated to Software Support team
- Monitored installation process
- Documented final resolution
- 
Outcome:
Issue resolved after registry cleanup and updated installer applied. Demonstrated escalation, troubleshooting, and documentation in ServiceNow.

Screenshots:

<img width="2559" height="434" alt="01-software-ticket png" src="https://github.com/user-attachments/assets/36b0a224-8b7b-4cfc-93d5-3de59175043f" />

<img width="2236" height="1123" alt="02-software-in-progress png" src="https://github.com/user-attachments/assets/de319c82-e1f0-4e40-977b-b8aec6ad4bb4" />

<img width="2239" height="1254" alt="03-software-escalated png" src="https://github.com/user-attachments/assets/28d7a69c-40d1-405d-825f-0ee6ce257479" />

<img width="2239" height="1253" alt="04-software-resolved png" src="https://github.com/user-attachments/assets/518c5cf1-8556-43f5-8da0-b4527f68e700" />


<br> </br>
Incident Simulation – Hardware Failure
Ticket Type: Laptop Power Issue
Priority: High (P2)

Summary:
 User reported that the laptop would not power on. Initial troubleshooting indicated a possible hardware failure.
 
Actions Taken:
- Created incident ticket
- Contacted user and verified issue
- Performed basic hardware troubleshooting
- Escalated to hardware vendor
- Monitored repair process
- Documented final resolution
  
Outcome:
Issue resolved after the vendor replaced the battery. Demonstrated hardware troubleshooting, escalation, and vendor coordination.
Screenshots:

<img width="2239" height="435" alt="01-hardware-ticket png" src="https://github.com/user-attachments/assets/bbfe2f81-7d8e-4008-9243-1d5ecbfadfff" />

<img width="2242" height="1119" alt="02-hardware-in-progress png" src="https://github.com/user-attachments/assets/3a84b8c2-806c-4172-aaff-0250433d16cf" />

<img width="2241" height="1255" alt="03-hardware-escalated png" src="https://github.com/user-attachments/assets/d411339a-4445-4f80-a54a-4bb583594d12" />

<img width="2240" height="1253" alt="04-hardware-resolved png" src="https://github.com/user-attachments/assets/cde836d7-2e5f-4afb-bc37-54cb83432f99" />



Incident Simulation – Database Access Issue
Ticket Type: Database Connectivity Failure
Priority: High (P2)

Summary:
Multiple users reported an inability to access the internal database. Issue confirmed as system-wide, indicating backend service failure.

Actions Taken:
- Created incident ticket
- Verified issue across multiple users
- Identified potential system-wide outage
- Escalated to Database/Infrastructure team
- Monitored resolution progress
- Documented final resolution
  
Outcome:
Issue resolved after database service restart. Linked to known error. Demonstrated understanding of incident vs problem management and escalation procedures.

Screenshots:

<img width="2238" height="436" alt="01-database-ticket png" src="https://github.com/user-attachments/assets/14f979c6-33a2-4b48-833b-5832314bdfcc" />

<img width="2241" height="1102" alt="02-database-in-progress png" src="https://github.com/user-attachments/assets/8f7eadab-78ff-4fc3-86f0-6f07442a180e" />

<img width="2237" height="1251" alt="03-database-escalated png" src="https://github.com/user-attachments/assets/d45401c7-a0bd-4c7c-84c0-092e7ccfcd0f" />

<img width="2238" height="1254" alt="04-database-resolved png" src="https://github.com/user-attachments/assets/96633b74-e579-4ad8-819f-02ea6f110edd" />



Incident Simulation – Password Reset
Ticket Type: Account Lockout
Priority: Medium (P2)

Summary:
User account locked after multiple failed login attempts. Immediate access required for business operations.

Actions Taken:
- Created incident ticket
- Verified user identity
- Reset password and unlocked account
- Confirmed successful login
- Provided user guidance on password practices
  
Outcome:
Issue resolved quickly without escalation. Demonstrated ability to handle common help desk requests efficiently and securely.

Screenshots:

<img width="2239" height="435" alt="01-password-reset-ticket png" src="https://github.com/user-attachments/assets/bb633a40-0ed0-4d25-b52f-a0c6c413a1c5" />

<img width="2241" height="1103" alt="02-password-reset-in-progress png" src="https://github.com/user-attachments/assets/b4dc39ca-bb4e-41fb-8405-790d266d225a" />

<img width="2238" height="1251" alt="03-password-reset-resolved png" src="https://github.com/user-attachments/assets/a8c1be9f-3f6f-4375-8807-ca25facd218e" />



Incident Simulation – Network Connectivity
Ticket Type: Cannot access the internet  
Priority: Critical (P1)  

Summary:
A user reported an inability to access the internet, affecting productivity. Initial troubleshooting indicated a potential DNS issue.

Actions Taken:
- Created high-priority incident ticket
- Performed initial network troubleshooting (ping tests, connectivity checks)
- Documented findings in work notes
- Escalated issue to Network Team
- Monitored ticket progress
- Documented final resolution

Outcome:
Issue resolved after DNS configuration fix. Service restored. Demonstrated proper escalation and incident handling procedures.

Screenshots:

<img width="2239" height="435" alt="01-network-connectivity-ticket png" src="https://github.com/user-attachments/assets/7b798193-8f64-4a31-a7bc-ab9b8680ba65" />

<img width="2237" height="1107" alt="02-network-connectivity-in-process png" src="https://github.com/user-attachments/assets/5bdee78a-56db-4a6d-b77e-cf315379bfde" />

<img width="2241" height="1255" alt="03-network-connectivity-escalated png" src="https://github.com/user-attachments/assets/3312619c-9178-46c1-8389-d96a11b6b73b" />

<img width="2238" height="1254" alt="04-network-connectivity-resolved png" src="https://github.com/user-attachments/assets/ab6eabf7-f45b-4ee7-8411-a18688525fef" />



<img width="2558" height="1304" alt="showcase_25+_tickets png" src="https://github.com/user-attachments/assets/27d73035-e983-4041-b235-55b633849f37" />













