# Dr Plus - Clinic Management System

A modern Windows desktop clinic management system designed to help doctors and medical staff manage daily medical practice operations efficiently.

## Overview

Dr Plus is a desktop clinic management application built with modern web technologies and packaged as a Windows application using Electron.

The system provides separate workflows for doctors and secretaries, helping medical practices manage patients, appointments, electronic medical records, prescriptions, billing, reporting, and AI-assisted medical data processing.

## Main Features

## Doctor Panel

- Patient management
- Electronic Medical Records (EMR)
- Digital prescriptions
- Appointment scheduling
- Laboratory analysis
- Medical imaging support
- Insurance management
- Financial reports
- Communication with secretary
- Clinic settings and system configuration

## Secretary Panel

- Patient registration and management
- Appointment management
- Billing and invoices
- Insurance management
- Clinic services management
- Communication with doctors
- Backup and restore management
- System settings

## AI-Assisted Medical Features

- Laboratory report OCR processing
- Persian and English text recognition
- Medical image processing integration
- AI-assisted analysis workflow

## Technology Stack

### Frontend

- React 18
- TypeScript
- Tailwind CSS
- Material UI
- React Router v6

### Desktop Application

- Electron
- Electron Builder
- Windows NSIS Installer

### Backend

- Node.js
- Express.js
- Prisma ORM
- SQLite Database

### Security

- JWT Authentication
- Role-Based Access Control
- Secure API Communication
- Data Privacy Controls

## System Architecture

```text
Electron Desktop Application

            ↓

React + TypeScript Frontend

            ↓

Node.js + Express REST API

            ↓

Prisma ORM

            ↓

SQLite Database
---
Application Modules
Patient Management
Patient profiles
Medical history
Documents and records
Appointment Management
Daily schedules
Calendar management
Doctor and secretary workflow
Financial Management
Billing
Insurance
Reports
Backup System
Data backup and restore
Local database management
Project Structure
Dr Plus

├── Frontend
│   ├── React Application
│   ├── Components
│   ├── Pages
│   └── Services
│
├── Backend
│   ├── Express API
│   ├── Prisma
│   ├── Database
│   └── Authentication
│
└── Electron
    └── Desktop Application Layer
Screenshots

Screenshots and demo videos will be added soon.

Future Improvements
Cloud synchronization
Advanced analytics dashboard
Mobile companion application
About The Project

Dr Plus is a proprietary software product developed as a complete clinic management solution, combining desktop application development, backend services, database design, security, and AI-assisted medical workflows.

License

This project is proprietary software.

Source code and commercial usage rights are not publicly available.