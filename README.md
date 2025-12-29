# Software Requirements Specification (SRS)
**Project:** Athlete Management System

**Team:** CyberAthletes

## 1. Functional Requirements (FR)
The system must provide the following functions to support the academy's daily operations, covering user management, training schedules, performance tracking, and tournament logistics.

### Module A: User Management
1.  **FR-01 (Registration):** The system shall allow the Admin to register new player profiles including personal details (Full Name, Date of Birth, Emergency Contact) and assign them a unique Player ID.
2.  **FR-02 (Role Assignment):** The system shall allow the Admin to create staff accounts and assign specific roles (Head Coach, Assistant Coach, Physio) with appropriate access permissions.
3.  **FR-03 (Authentication):** The system shall verify user identity via a secure login interface requiring a registered email address and password.

### Module B: Training & Scheduling
4.  **FR-04 (Session Creation):** The system shall allow Coaches to schedule new training sessions by specifying the date, time, location (e.g., Field A, Gym), and session type.
5.  **FR-05 (Attendance Tracking):** The system shall allow Coaches to record attendance status (Present, Absent, Late, Injured) for every player assigned to a specific training session.
6.  **FR-06 (Schedule View):** The system shall allow Players to view their personal training calendar, including upcoming sessions and match fixtures, on a dashboard.

### Module C: Performance Records
7.  **FR-07 (Data Entry):** The system shall allow Coaches to input quantitative performance metrics (e.g., Sprint Speed, Pass Completion %, Stamina Level) for individual players after assessments.
8.  **FR-08 (Progress Visualization):** The system shall generate a line graph for selected performance metrics (e.g., "Goals Scored over last 5 months") when viewed by a Player or Coach.
9.  **FR-09 (Qualitative Feedback):** The system shall allow Coaches to attach text-based notes (e.g., tactical improvements, behavioral feedback) to a specific player's profile.

### Module D: Tournament Management
10. **FR-10 (Tournament Entry):** The system shall allow the Admin to record details of external tournaments, including Tournament Name, Host Venue, and Start/End Dates.
11. **FR-11 (Match Results):** The system shall allow the Coach to submit the final score of a match, including opponent details and specific player contributions (Goals, Assists, Cards).
12. **FR-12 (Report Generation):** The system shall allow the Admin to generate and export a "Season Summary Report" (PDF format) listing all matches played and the academy's win/loss record.
