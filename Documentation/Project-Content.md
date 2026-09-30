# Project Content

## Project
**Incident Lifecycle Automation in ServiceNow**

## Objective
The project models an end-to-end incident lifecycle in ServiceNow, from service setup through final validation.

## Scenario
A user is unable to connect to the Corporate VPN from a home office. The incident is created through the Service Desk, classified as a Network/VPN issue, investigated by Level 2 support, placed on hold while awaiting a change, linked to a child incident, resolved using a documented workaround, and followed by knowledge creation and validation.

## Configuration
| Field | Value |
|---|---|
| Service | Remote Access |
| Service Offering | Corporate VPN |
| Caller | Michael Hoefer |
| Channel | Phone |
| Assignment Group | Service Desk |
| Category | Network |
| Subcategory | VPN |
| Urgency | 2 - Medium |
| Initial CI | ThinkStationS20 |
| Final CI | PowerEdge |
| Network Assignment | Network |
| Level 2 User | David Loo |
| On Hold Reason | Awaiting Change |
| Probable Cause | PowerEdge service was suspended and required restart. |
| Resolution Code | Workaround provided |
| Resolution Notes | Restarted VPN-SRV-02 service as per emergency change request. |
| Knowledge Base | IT |
| Knowledge Template | Standard |

## Lifecycle
1. Service Creation
2. Service Offering Creation
3. Incident Creation
4. Incident Classification
5. Agent Assist
6. Knowledge Article Integration
7. Watch List / Work Notes List
8. Reassignment to Network
9. Level 2 Investigation
10. Configuration Item Update
11. On Hold – Awaiting Change
12. Child Incident Creation
13. Cause Documentation
14. Resolution
15. Knowledge Article Creation
16. SLA Validation
17. Related Records Validation
18. Final End-to-End Validation

## Stakeholders
- End Users
- Service Desk Agents
- Level 2 Support / Network / Hardware Teams
- Change Management Team
- ServiceNow Administrator

## Evidence Policy
This document records the intended project content. Actual screenshots, demo links, and test outcomes must be captured from the real ServiceNow instance. No evidence is fabricated.
