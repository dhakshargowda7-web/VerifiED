VerifiED — AI-Powered Academic Certificate Verification System

VerifiED is an AI-assisted platform that detects fraudulent academic certificates by analysing textual patterns, formatting inconsistencies, metadata, and document structure. It is designed to support schools, employers, institutions, and verification agencies that need a fast and reliable system to authenticate submitted certificates.

This project is currently in the Prototype Planning Stage and is being developed for AI competitions, hackathons, and future deployment as a full web application.

Problem Statement

Fake academic certificates are a rising issue across schools, colleges, and recruitment processes.
Manual verification is slow, requires expertise, and can be inconsistent.

VerifiED uses AI and rule-based detection to:

Identify formatting anomalies

Flag edited or manipulated areas

Analyse text consistency

Match certificate patterns with known templates

Output a verification confidence score

Project Goals

Build a web application where users can upload certificates (PDF/JPG/PNG)

Process certificates through:

OCR-based text extraction

Layout anomaly analysis

Template matching

Basic image authenticity checks

Deliver a result including:

Authenticity score

Highlighted suspicious regions

Explanations for each flag

Tech Stack (Planned)
Component	Technology
Frontend	React.js / HTML / Tailwind
Backend	Python Flask / Node.js
AI Models	Tesseract OCR, LayoutLM, CV anomaly detection
Database	MongoDB / Firebase
Deployment	Vercel / Render
Current Status

Idea planned and documented

Submitted to competitions

Architecture outlined

UI prototype (upcoming)

OCR + ML pipeline (upcoming)

API integration (upcoming)

MVP deployment (upcoming)

Project will evolve as features are added.
VerifiED/
│── docs/               → Mockups, diagrams
│── backend/            → API & AI models
│── frontend/           → React UI
│── sample_data/        → Example certificates
│── README.md           → Documentation
How It Works

User uploads a certificate

OCR extracts text

AI analyses formatting and layout

Template matcher compares with institution formats

System checks anomalies (text or visual)

Generates an authenticity score

Displays detailed results

Future Roadmap

Build upload UI

Integrate OCR text extraction

Add certificate template matching

Build anomaly detection module

Create a basic certificate database

Add admin dashboard for institutions

Deploy early-version MVP

Document results in a case study
