# Project 2: IT Service Desk Ticketing & Incident Management

## Objective
To demonstrate hands-on understanding of IT Service Desk operations using ITIL-aligned ticketing workflows similar to ServiceNow and Jira Service Management.

## Service Desk Concepts Used
- Incident Management (ITIL)
- Ticket lifecycle management
- SLA-based prioritization
- Impact vs Urgency assessment
- User communication and documentation
- First-line support resolution

## Ticket Lifecycle Workflow
1. Incident logged by end user
2. Categorization (Access, Hardware, Software, Network)
3. Impact & urgency assessment
4. Priority assignment (P1–P4)
5. Troubleshooting & resolution
6. User confirmation
7. Ticket closure with documentation

## Sample Incidents (Simulated)

### INC-001 – User Unable to Log In
- Category: Access Management
- Impact: High (user unable to work)
- Urgency: High
- Priority: P1
- SLA Target: 4 hours

**Actions Taken**
- Verified account status
- Reset user password
- Confirmed successful login with user

**Resolution**
- Access restored
- Ticket closed after user confirmation

---

### INC-002 – Slow System Performance
- Category: Hardware / Performance
- Impact: Medium
- Urgency: Medium
- Priority: P3
- SLA Target: 24 hours

**Actions Taken**
- Reviewed startup applications
- Performed disk cleanup
- Verified system resource usage

**Resolution**
- Performance optimized
- User confirmed improvement

---

### INC-003 – No Internet Connectivity
- Category: Network Services
- Impact: High
- Urgency: High
- Priority: P1
- SLA Target: 4 hours

**Actions Taken**
- Checked network adapter status
- Verified IP configuration
- Performed ping and DNS tests

**Resolution**
- Network connectivity restored
- Ticket documented and closed

## Tools Simulated
- ServiceNow-style incident queue
- Jira Service Management workflow concepts
- Knowledge base documentation

## What I Learned
- How real IT Service Desks operate
- SLA-driven prioritization
- Importance of user communication
- Structured documentation for audits and escalation
## Escalation Scenarios

### ESC-001 – Repeated Login Failure After Password Reset
- Original Incident: INC-001
- Escalation Level: Level 2 (System Administration)
- Reason for Escalation:
  - Password reset did not resolve issue
  - Possible account lockout or directory sync issue

**Actions Taken Before Escalation**
- Verified user identity
- Attempted password reset
- Checked local system login logs

**Escalation Notes**
- Escalated to Level 2 for Active Directory investigation
- Documented all troubleshooting steps to avoid repetition

**Outcome**
- Account unlocked by Level 2
- User successfully logged in
- Ticket updated and closed

---

### ESC-002 – Network Outage Affecting Multiple Users
- Original Incident: INC-003
- Escalation Level: Level 3 (Network Team)
- Reason for Escalation:
  - Multiple users impacted
  - Issue beyond first-line troubleshooting scope

**Actions Taken Before Escalation**
- Verified issue affected multiple endpoints
- Restarted local network services
- Confirmed issue not user-specific

**Escalation Notes**
- Escalated to Network Team with impact assessment
- Provided diagnostic details (IP status, ping results)

**Outcome**
- Network configuration issue resolved
- Service restored
- Incident closed after user confirmation

---

### ESC-003 – SLA Breach Risk
- Incident Type: Performance Degradation
- Escalation Level: Supervisor / Team Lead
- Reason for Escalation:
  - SLA target at risk
  - Issue unresolved within allocated time

**Actions Taken**
- Updated ticket status
- Notified supervisor
- Reassigned ticket for faster resolution

**Outcome**
- SLA breach avoided
- User informed of progress
