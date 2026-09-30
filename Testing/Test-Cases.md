# Test Cases

| Test ID | Test Case | Expected Result |
|---|---|---|
| TC-01 | Create Remote Access service | Service is created with required details |
| TC-02 | Create Corporate VPN service offering | Offering is associated with Remote Access |
| TC-03 | Create VPN incident | Incident record is created successfully |
| TC-04 | Classify incident as Network / VPN | Classification values are saved |
| TC-05 | Assign and reassign incident | Incident reaches the correct support group |
| TC-06 | Update configuration item | Correct CI is associated with the incident |
| TC-07 | Place incident on hold | On Hold reason is Awaiting Change |
| TC-08 | Create child incident | Child record is related to the parent incident |
| TC-09 | Resolve incident | Cause, resolution code, and notes are documented |
| TC-10 | Validate SLA and related records | SLA and relationships can be verified |

## Execution Note
These test cases describe the intended validation. Actual Pass/Fail results must be recorded only after execution in the ServiceNow instance.
