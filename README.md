# Student Attendance System

Software engineering case study and requirements documentation for a Student Attendance System (SAS). The proposed system automates attendance capture, monitoring, leave management, alerts, and reporting for educational institutions.

## Project Overview

The system is designed to support:

- Attendance capture through RFID, biometric devices, QR codes, and manual entry
- Role-based portals for students, faculty, parents or guardians, and administrators
- Leave request, review, and approval workflows
- Attendance analytics and reports exportable to PDF and Excel
- Automatic low-attendance and absence notifications through SMS or email
- Timetable, course, user-account, and attendance-rule management
- Integration with institutional ERP or LMS systems
- Audit logging and compliance with India's Digital Personal Data Protection Act, 2023

The minimum attendance alert threshold documented in the SRS is 75%.

## Repository Contents

| File | Description |
| --- | --- |
| [SRS_Student_Attendance_System.docx](SRS_Student_Attendance_System.docx) | IEEE 830-style Software Requirements Specification containing the system scope, stakeholders, requirements, use cases, constraints, and assumptions |
| [SAS_Artifacts.xlsx](SAS_Artifacts.xlsx) | Project planning and quality artifacts, including the RTM, WBS, Gantt chart, agile backlog, test cases, bug reports, and software engineering tools |
| [Context diagram.png](Context%20diagram.png) | Level 0 system context diagram showing external entities and data flows |
| [stakeholder.png](stakeholder.png) | Stakeholder analysis visual |
| [stakeholder .png](stakeholder%20.png) | Additional stakeholder visual |

## Main Stakeholders

- Students
- Faculty and teachers
- Academic administrators and registrars
- Parents or guardians
- Heads of Department and academic coordinators
- IT and system administrators
- Institution management

## Key Requirements

### Functional

- Faculty can record attendance for a class session.
- Students can check in through supported attendance modes.
- Students can submit leave requests and faculty can approve or reject them.
- Users can view, filter, analyze, and export attendance reports.
- The system sends alerts when attendance falls below the configured threshold.
- Administrators can manage users, courses, timetables, rules, and audit logs.
- Enrollment and timetable data can synchronize with an ERP or LMS.

### Non-functional

- RFID or biometric attendance capture should complete within 2 seconds per student.
- The system should support 10,000 or more concurrent students during peak periods.
- Availability target: 99.5% during institutional working hours.
- Mobile clients should support offline attendance caching and later synchronization.
- Role-based access control and encryption are required for sensitive data.
- The system should support modern web browsers, Android 10+, and iOS 14+.

## Project Status

This repository currently contains the requirements, planning, design, and testing artifacts for the proposed system. It does not currently include an executable application or deployment configuration.

## Tools Used

- Microsoft Word for the SRS
- Microsoft Excel for project and testing artifacts
- Draw.io for system diagrams
- Lucidchart for UML and stakeholder mapping
- Google Forms for requirements-gathering surveys

## Reference

Repository: [student-attendance-system-](https://github.com/kshitijarenuke-cell/student-attendance-system-)