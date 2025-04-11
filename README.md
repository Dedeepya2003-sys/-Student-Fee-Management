# -Student-Fee-Tracing-System
# 📚 Student Fee Tracing System

This project is a simple yet effective solution for managing and tracking student fee payments. It automatically identifies students who have not cleared their dues and sends them notifications via email, including OTPs for verification.

## ✨ Features

- 🔍 Track unpaid student fees
- 🔐 OTP (One-Time Password) generation and email delivery for verification
- 📧 Send email alerts to defaulters
- 💾 Simple and clean codebase for easy customization

## 🛠️ Tech Stack

- **Language**: Python
- **Libraries/Tools**:
  - `smtplib` – for sending emails
  - `email.message` – to format the emails
  - `random` – for OTP generation
  - `csv` or `pandas` (optional) – for handling student data

## 📁 Project Structure

```bash
student-fee-tracing/
│
├── data/
│   └── students.csv            # CSV file with student data (name, email, fee status)
│
├── otp_sender.py               # Script to generate OTP and send emails
├── fee_checker.py             # Script to identify unpaid fees
├── config.py                  # Email credentials and settings
└── README.md                  # Project documentation
