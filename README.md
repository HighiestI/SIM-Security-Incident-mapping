# SIM-Security-Incident-mapping
Campus crime reporting web app SIM project 
# SIM - Security Incident Mapping

## Project Overview

SIM (Security Incident Mapping) is a web-based platform designed to help campus communities quickly report security incidents. The system enables students, staff, and landlords to submit crime reports (stabbing, rape, theft, assault, murder, etc.) with location details, timestamps, and urgency levels. Security administrators can then track, manage, and respond to these incidents effectively.

This project was developed as a solution to address campus insecurity in Nigeria, providing a fast, anonymous, and accessible reporting mechanism for the community.

---

## Project Objectives

- Provide a simple and intuitive interface for reporting security incidents
- Enable quick submission with essential details (type, location, time, description)
- Categorize incidents by type and urgency (Low, Medium, High)
- Support anonymous reporting to protect whistleblowers
- Give administrators tools to monitor and managereports
- Reduce response time to security incidents on campus

---

## Repository Structure

---

## Features

### For Reporters (Students, Staff, and Landlords):

- Incident Type Selection - Choose from predefined categories (Stabbing, Rape, Theft, Physical Attack, Murder, Other)
- Location Input - Specify where the incident occurred
- Date and Time - Record when the incident happened
- Detailed Description - Provide contextual information
- Urgency Levels - Set priority (Low, Medium, High/Emergency)
- Instant Confirmation - Visual feedback after submission
- Mobile Responsive - Works on all screen sizes

### For Administrators (Security Personnel):

- View All Reports - See all submitted incidents
- Status Management - Update report status (Pending, In Progress, Resolved)
- Task Assignment - Delegate cases to security teams
- Statistics Generation - Analyze incident patterns
- Notification System - Alert relevant personnel

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure and content |
| CSS3 | Styling and responsive design |
| JavaScript | Interactive functionality |
| Draw.io | Diagram creation (Ishikawa and Use-Case) |
| Google Forms | Survey data collection |
| GitHub | Version control and hosting |

---

## Documentation

### 1. Software Requirements Specification (SRS)

The SRS.md file contains:
- Functional requirements (FR-01 to FR-07)
- Non-functional requirements (NFR-01 to NFR-05)
- System scope and user classes
- Operating environment specifications

### 2. Ishikawa Diagram (ishikawa-diagram.drawio)

Fishbone analysis identifying root causes of campus crime:

- People: Lack of awareness, substance abuse, mental health, intruders
- Environment: Poor lighting, CCTV gaps, broken fences, isolated areas
- Policy: Weak penalties, slow procedures, unclear conduct codes
- Technology: Broken cameras, no alarms, poor network coverage
- Management: Insufficient staff, inadequate training, slow response
- Community: Weak watch programs, mistrust, no police collaboration

### 3. Use-Case Diagram (usecase-diagram.drawio)

Shows system interactions between:

- Actors: Reporter (Student, Staff, and Landlord) and Security Administrator
- Use Cases: Report submission, status checking, emergency alerts, report management, statistics generation, and more
- Relationships: Include and extend relationships between use cases

### 4. Survey Questionnaire (questionnaire-link.txt)

Google Form link collecting feedback from:
- Students
- Staff and Faculty
- Landlords

---

## How to Run the Application

### Option 1: Direct Browser Access

1. Download index.html
2. Double-click to open in any modern browser (Chrome, Firefox, Safari, Edge)
3. Start submitting reports immediately

### Option 2: Live Server (Recommended for Development)

Using VS Code with Live Server extension:

1. Open index.html in VS Code
2. Right-click and select "Open with Live Server"
3. Application runs on http://localhost:5500

### Option 3: Host on GitHub Pages

1. Go to repository Settings
2. Navigate to Pages section
3. Select branch (main) as source
4. Click Save
5. Access at: https://your-username.github.io/SIM-Security-Incident-Mapping/

---

## How to Use the Application

### Submitting a Report:

1. Select Incident Type - Click one of the colored buttons (Stabbing, Rape, Theft, etc.)
2. Enter Location - Specify where the incident occurred
3. Set Date and Time - Use the calendar and clock pickers
4. Add Description - Provide detailed information about the incident
5. Choose Urgency - Select Low, Medium, or High priority
6. Click Submit - The report is sent (simulated in this prototype)

---

## Responsive Design

The application automatically adapts to:

- Desktop: Full layout with all features visible
- Tablet: Optimized spacing and font sizes
- Mobile: Stacked layout, touch-friendly buttons, compact form fields

---

## Submission Requirements

This project fulfills the following assignment requirements:

- Google Form questionnaire design
- Ishikawa problem analysis (Draw.io)
- Mini web interface development
- Use-Case diagram (Draw.io)
- SRS document (functional and non-functional requirements)
- GitHub repository with all documentation
- Submitted via email to ajcomponentengineer@gmail.com

Deadline: Friday, 10th July 2026

---

## Target Users

| User Group | Role | Interaction |
|------------|------|-------------|
| Students | Report incidents they witness or experience | Submit reports, check status |
| Staff | Report campus security issues | Submit reports, escalate concerns |
| Landlords | Report incidents in off-campus housing | Submit reports, monitor area safety |
| Security Admin | Manage and respond to incidents | View all reports, update status, assign tasks |

---

## Future Enhancements

The following features are planned for future iterations:

- User Authentication - Secure login for all users
- Database Integration - Persistent storage of reports
- Real-time Map View - Show incidents on an interactive campus map
- Image and Video Upload - Attach evidence to reports
- Email and SMS Notifications - Alert users about report progress
- Dashboard Analytics - Visual statistics and trend analysis
- Multi-language Support - Localization for broader accessibility

---

## Known Limitations

- No Backend - Currently a front-end prototype only; reports are not stored permanently
- No Authentication - No login system; suitable only for demonstration purposes
- No Real-time Updates - Cannot track report status in real-time
- No Data Export - Statistics and reports cannot be exported yet

---

## Contact

For questions, feedback, or support:

- Email: ajcomponentengineer@gmail.com
- GitHub: [Your GitHub Profile URL]

---

## License

This project is developed for academic purposes as part of the SEN202 course requirement. All rights reserved.

---

## Acknowledgments

- Nigerian Government and University Administration for highlighting this security issue
- Lecturer and course coordinators for providing project guidance
- Students, staff, and landlords who participated in the survey
- Open-source community for tools and resources

---

## Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | July 2026 | Initial release - Complete submission package |

---

Built for a safer campus community
