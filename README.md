# Incident Lifecycle Automation in ServiceNow

## Project Overview
This project demonstrates an end-to-end Incident Lifecycle Automation workflow in ServiceNow, covering incident creation, classification, assignment, investigation, change handling, child incidents, resolution, knowledge creation, SLA validation, and final verification.

## Objective
To model a structured ServiceNow incident lifecycle from service configuration through resolution and validation using a realistic Corporate VPN support scenario.

## Scenario
- Service: Remote Access
- Service Offering: Corporate VPN
- Incident: Unable to connect to Corporate VPN from home office
- Caller: Michael Hoefer
- Initial Assignment Group: Service Desk
- Channel: Phone
- Category: Network
- Subcategory: VPN
- Urgency: 2 - Medium
- Initial Configuration Item: ThinkStationS20
- Final Configuration Item: PowerEdge
- Network Assignment: Network
- Level 2 User: David Loo
- On Hold Reason: Awaiting Change
- Probable Cause: PowerEdge service was suspended and required restart.
- Resolution Code: Workaround provided
- Resolution Notes: Restarted VPN-SRV-02 service as per emergency change request.
- Knowledge Base: IT
- Knowledge Template: Standard

## Incident Lifecycle
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

## Repository Structure
- `Documentation/` — project report, project content, and submission evidence
- `Screenshots/` — evidence organized by lifecycle stage
- `Testing/` — test cases and actual test results
- `Demo/` — real demo link when available
- `assets/diagrams/` — diagram assets

## Evidence Policy
Only actual ServiceNow screenshots, real demo links, and executed test results should be added. No fabricated screenshots, credentials, links, or pass/fail results are included.

## Documentation
- [Project Content](Documentation/Project-Content.md)
- [Submission Evidence](Documentation/Submission-Evidence.md)
- [Project Report](Documentation/Project-Report.pdf)
- [Project Report DOCX](Documentation/Project-Report.docx)

## Testing
See [Test Cases](Testing/Test-Cases.md) and [Test Results](Testing/Test-Results.md).

## Demo
The demo link will be added after a real ServiceNow demonstration is available.

## Security
Do not commit ServiceNow passwords, API keys, access tokens, session cookies, or other private credentials.

## Status
Project structure and documentation are prepared. Screenshots, demo link, and executed test results remain evidence-dependent and should be added only after the corresponding ServiceNow work is actually completed.
