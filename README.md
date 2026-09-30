# Incident Lifecycle Automation in ServiceNow

## Project Overview
This project demonstrates an end-to-end **Incident Lifecycle Automation** process in ServiceNow, covering incident creation, classification, assignment, investigation, change dependency, child incident handling, resolution, knowledge creation, SLA validation, and final record validation.

## Objective
To model and document a complete ServiceNow incident lifecycle using a realistic Corporate VPN support scenario.

## Scenario
| Field | Value |
|---|---|
| Service | Remote Access |
| Service Offering | Corporate VPN |
| Incident | Unable to connect to Corporate VPN from home office |
| Caller | Michael Hoefer |
| Initial Assignment Group | Service Desk |
| Channel | Phone |
| Category | Network |
| Subcategory | VPN |
| Urgency | 2 - Medium |
| Initial CI | ThinkStationS20 |
| Level 2 User | David Loo |
| On Hold Reason | Awaiting Change |
| Probable Cause | PowerEdge service was suspended and required restart |
| Resolution Code | Workaround provided |
| Knowledge Base | IT |
| Knowledge Template | Standard |

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
11. On Hold - Awaiting Change
12. Child Incident Creation
13. Cause Documentation
14. Resolution
15. Knowledge Article Creation
16. SLA Validation
17. Related Records Validation
18. Final End-to-End Validation

## Repository Structure
- **Documentation/** - project report, content, and submission evidence
- **Screenshots/** - evidence organized by lifecycle stage
- **Testing/** - test cases and actual test-result records
- **Demo/** - real demo link when available
- **assets/diagrams/** - project diagrams and visual assets

## Evidence Policy
Only actual ServiceNow screenshots, real demo links, and actual test execution results should be added. No fabricated evidence or credentials are included.

## Documentation
- [Project Content](Documentation/Project-Content.md)
- [Submission Evidence](Documentation/Submission-Evidence.md)
- [Project Report](Documentation/Project-Report.pdf)
- [Project Report DOCX](Documentation/Project-Report.docx)

## Testing
See [Test Cases](Testing/Test-Cases.md) and [Test Results](Testing/Test-Results.md).

## Demo
The demo link will be added only when a real demo URL is available.

## Security
Never commit ServiceNow passwords, API keys, access tokens, session cookies, or other private authentication information.

## Status
Project documentation structure is prepared. ServiceNow screenshots, real test results, and a real demo URL remain evidence-dependent.
