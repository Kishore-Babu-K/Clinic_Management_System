## Clinic Management System

This project is a web-based application designed for small clinics to streamline the management of outpatient services. The system enables secure and efficient handling of patient records, doctor assignments, appointment queues, and diagnosis tracking, providing an intuitive interface for clinic staff.

## Overview

The Out-Patient Management System offers an end-to-end solution for managing daily clinical operations such as patient registration, medical history tracking, and queue scheduling. Built using Python and Streamlit, the system leverages CSV files for lightweight data storage and rapid deployment without the need for complex database setup.

## Features

- Secure role-based login system (Admin, Nurse, Doctor)
- Patient record creation, retrieval, update, and deletion
- Real-time patient queue management
- Patient-doctor assignment based on availability and specialization
- Doctor dashboard to access medical history and record diagnosis/prescriptions
- Visit history tracking
- Lightweight CSV-based data management
- Minimal setup and easy deployment via Streamlit

## Technologies Used

- **Python** – Application logic and data handling
- **Streamlit** – User interface and frontend rendering
- **CSV Files** – Simple, flat-file data storage

## Project Structure
clinic_management_system/
│
├── app.py # Entry point for the Streamlit application
├── doctor.py # Doctor dashboard and functionality
├── nurse.py # Nurse dashboard and patient queue
├── admin.py # Admin user and credential management
├── utils/ # Helper functions and utilities
│ └── helpers.py
├── data/ # CSV storage files
│ ├── users.csv
│ ├── patients.csv
│ └── visits.csv
├── .gitignore
└── README.md

Future Enhancements
- Calendar-based appointment scheduling
- Role-specific access control with session management
- Integration with pharmacy and billing modules
- Integration with relational databases (e.g., MySQL or PostgreSQL)
