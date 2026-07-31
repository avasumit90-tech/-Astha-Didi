# -Astha-Didi
Astha Foundation Management System 
# Astha Foundation Management System

> A complete **responsive Website + Web Application** for managing registrations, payments, approvals, ID cards, certificates, donations, projects, and administrative operations.

---

# Overview

The Astha Foundation Management System is a centralized digital platform designed to simplify the management of foundation members, coordinators, teachers, students, donations, certificates, and projects.

The platform includes:

- Public Website
- User Portal
- Admin Panel
- Mobile Responsive Design

---

# Features

## Public Website

- Home Page
- About Us
- Projects
- Gallery
- Partner Logos
- Contact Information
- Legal Documents
- Donation Page
- Help & Support
- Authorization Letter Verification

---

## Registration Modules

### Astha Didi

- Online Registration
- Online Payment
- Admin Approval
- Digital ID Card
- Profile Management

---

### Astha Maa

- Online Registration
- Payment
- Approval
- Digital ID Card

---

### Teacher

- Online Registration
- Payment
- Approval
- Digital ID Card

---

### Student

- Free Registration
- Admin Approval
- Student Profile

---

### District Coordinator

- Registration
- Approval
- District Profile
- Public Display with Photo

---

### Block Coordinator

- Registration
- Approval
- Block Profile

---

# Admin Panel

Dashboard includes:

- Total Users
- Registrations
- Pending Approvals
- Donations
- Payments
- Certificates
- Projects
- Gallery
- Reports
- Analytics

---

# Payment System

Supports:

- Registration Fees
- Donation Payments

Features:

- Payment Verification
- Transaction History
- Payment Reports
- Receipt Generation

---

# Donation Module

- Online Donation
- Payment Gateway
- Auto Receipt Generation
- Receipt Number
- Organization Logo
- Donation Date
- 80G Number
- PDF Receipt Download

---

# Certificate Module

Admin can generate:

- Training Certificate
- Internship Certificate

Features

- QR Code
- Unique Certificate Number
- PDF Download

---

# ID Card Module

Generate ID Cards for

- Astha Didi
- Astha Maa
- Teacher
- District Coordinator
- Block Coordinator

Features

- QR Code
- Photo
- Signature
- Organization Logo
- Download PDF

---

# Gallery

- Photos
- Videos
- Albums
- Featured Images

---

# Projects

- Project List
- Project Details
- Images
- Documents

---

# Partner Logos

Display partner organizations on the Home Page.

---

# Legal Documents

Manage:

- Registration Certificate
- PAN
- 12A
- 80G
- Trust Deed
- Other Documents

---

# Contact Information

- Address
- Phone
- Email
- Google Map
- Office Hours

---

# Help & Support

- Contact Form
- Help Email
- User Queries

---

# Reports

Generate reports for:

- Users
- Registrations
- Payments
- Donations
- Certificates
- Projects
- Districts
- Blocks

Export formats:

- PDF
- Excel
- CSV

---

# Roles

- Super Admin
- Admin
- District Coordinator
- Block Coordinator
- Teacher
- Student
- Astha Didi
- Astha Maa
- Donor
- Visitor

---

# Technology Stack

## Frontend

- Next.js
- React
- TypeScript
- Tailwind CSS

## Backend

- Node.js
- Express.js

## Database

- PostgreSQL

## Authentication

- JWT Authentication
- Role-Based Access Control (RBAC)

## Payment Gateway

- Razorpay

## Storage

- Cloudinary / AWS S3

## PDF Generation

- PDFKit

## QR Code

- qrcode

---

# Folder Structure

```
project/

├── app/

├── components/

├── lib/

├── prisma/

├── public/

├── uploads/

├── server/

├── routes/

├── controllers/

├── middleware/

├── utils/

├── docs/

│   ├── README.md

│   ├── PRD.md

│   ├── TECHSPEC.md

│   ├── APPFLOW.md

│   ├── DESIGN.md

│   ├── SCHEMA.md

│   ├── IMPLEMENTATIONPLAN.md

│   ├── TRACKER.md

│   ├── RULES.md

│   ├── SKILLS.md

│   └── ADMIN_PANEL.md

├── package.json

└── .env
```

---

# Installation

Clone the repository

```bash
git clone https://github.com/your-org/astha-foundation.git
```

Install dependencies

```bash
npm install
```

Configure environment variables

```env
DATABASE_URL=
JWT_SECRET=
RAZORPAY_KEY_ID=
RAZORPAY_KEY_SECRET=
SMTP_HOST=
SMTP_USER=
SMTP_PASS=
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
```

Run database migrations

```bash
npm run migrate
```

Start development server

```bash
npm run dev
```

Build for production

```bash
npm run build
```

Start production server

```bash
npm start
```

---

# Security

- JWT Authentication
- Role-Based Permissions
- Password Hashing (bcrypt)
- HTTPS
- Input Validation
- XSS Protection
- CSRF Protection
- SQL Injection Prevention
- Audit Logs
- Secure File Uploads

---

# Responsive Design

Supported devices:

- Mobile
- Tablet
- Laptop
- Desktop

Browsers:

- Chrome
- Firefox
- Edge
- Safari

---

# Future Enhancements

- Mobile App (Android & iOS)
- Push Notifications
- WhatsApp Integration
- SMS Integration
- Biometric Login
- Multi-language Support (Hindi & English)
- Attendance Management
- Event Management
- Volunteer Management
- AI-powered Analytics

---

# License

Copyright © Astha Foundation.

All Rights Reserved.

---

# Project Status

**Status:** Planning / Development

---

# Documentation

This project includes the following documentation:

- README.md
- PRD.md
- TECHSPEC.md
- APPFLOW.md
- DESIGN.md
- SCHEMA.md
- IMPLEMENTATIONPLAN.md
- TRACKER.md
- RULES.md
- SKILLS.md
- ADMIN_PANEL.md

---

# Support

For technical support or project-related queries:

- Email: support@yourdomain.com
- Website: https://yourdomain.com

---

# Version

Current Version: **v1.0.0**
