# ElectronicMedicalRecord-Demo
Black Forest Healthcare System - A modern Hospital Information System (HIS) demo. Simulates end-to-end patient journey and inter-department data flow by Dr. Zaw
# ElectronicMedicalRecord-Demo (HIS)

Black Forest Healthcare System is a modern Hospital Information System (HIS) demo project designed to digitally manage hospital operations from end to end.

---

## Key Features Under Development

The project is structured into three main modules, developed concurrently across separate branches:

1. Patient Registration
   * Recording patient demographics and personal identification (NRC/ID).
   * Generating unique Patient IDs automatically.

2. Appointment Scheduling
   * Managing doctor schedules and shift duties.
   * Booking patient appointments and generating queue tokens.

3. Nurse Station
   * Recording and tracking patient vital signs (Blood Pressure, Temperature, Pulse).
   * Utilizing a Triage system to prioritize patients based on emergency levels.

---

## Tech Stack and Tools

* Frontend: HTML5, CSS3, JavaScript
* Version Control: Git and GitHub (Utilizing a multi-branch workflow for clean development)

---

## Current Project Architecture (Git Branches)

To maintain system stability, the project utilizes the following branching strategy:
* main - The core production branch containing fully tested and approved code.
* pt-registration - Isolated workspace for developing the patient intake workflow.
* appointment - Isolated workspace for building the scheduling and token system.
* nurse-station - Isolated workspace for creating the nurse dashboard and vital logs.

---

## Developer Information
* Lead Developer: Dr. Zaw
* Goal: To simulate and optimize inter-departmental data flow and patient journeys within modern healthcare systems.
