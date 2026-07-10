Software Requirements Specification (SRS)
for SIM – Security Incident Mapping

 1. Introduction
1.1 Purpose  
To provide a fast, secure, and anonymous way for campus community members to report security incidents, enabling timely response and data‑driven prevention.

1.2 Scope  
A web‑based application accessible from any modern browser, designed for students, staff, and off‑campus landlords. The system will store reports, allow status tracking, and give administrators tools to manage incidents.

2. Overall Description
2.1 User Classes
- Reporter– any community member who submits an incident.  
- Administrator – security personnel who manage reports and responses.

2.2 Operating Environment
- Web browsers (Chrome, Firefox, Safari, Edge)  
- Responsive design for mobile and desktop  
- Backend (optional for this mini version) – can be simulated with local storage or a simple PHP/Node server; for the prototype, we use client‑side only.

3. Functional Requirements
| ID   | Requirement |
|------|-------------|
| FR‑01 | The system shall allow a user to select an incident type from a predefined list. |
| FR‑02 | The system shall capture location, date, time, and description of the incident. |
| FR‑03 | The system shall support optional attachment of images (planned for future). |
| FR‑04 | The system shall provide an “Emergency” priority option that triggers immediate notification to administrators. |
| FR‑05 | Administrators shall be able to view all submitted reports with timestamps. |
| FR‑06 | Administrators shall be able to update the status of each report (Pending, In Progress, Resolved). |
| FR‑07 | The system shall allow reporters to check the status of their report using a unique reference ID (future enhancement). |

4. Non‑Functional Requirements
| ID   | Requirement |
|------|-------------|
| NFR‑01 | Performance: Page load time < 3 seconds; submission acknowledgment < 5 seconds. |
| NFR‑02 | Security: All data transmitted over HTTPS; no personally identifiable information stored unless explicitly given. |
| NFR‑03 | Usability: Clean, intuitive interface; works on screens as small as 320px width. |
| NFR‑04 | Reliability: System uptime ≥ 99%; data backed up daily. |
| NFR‑05 | Maintainability: Code shall be modular, well‑commented, and use semantic HTML. |
