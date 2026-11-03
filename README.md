# Label Sentinel

### AI-Assisted Legal Metrology Compliance Platform

**Project Reference:** SIH26034  
**Domain:** Legal Metrology / Regulatory Compliance Technology

## About the Project

Label Sentinel is an AI-assisted compliance-support platform designed to help identify and review declaration-related compliance issues in packaged commodities and online product listings.

The platform uses OCR and AI-assisted extraction to identify candidate product declarations. A deterministic, version-controlled rule engine evaluates the extracted information against applicable Legal Metrology requirements.

Uncertain findings are routed for human officer review to support transparent and evidence-based assessment.

## Key Features

- Package label and product listing analysis
- AI-assisted OCR and declaration extraction
- Rule-based compliance evaluation
- Evidence-to-rule traceability
- Explainable compliance reports
- Human officer review for uncertain findings
- Separate informational AI assistance through Know More AI

## User Portals

1. **Citizen Portal** – For submitting product-related information and complaints.
2. **Officer Portal** – For reviewing evidence and compliance findings.
3. **Admin Portal** – For managing platform configuration and administration.

## Compliance Statuses

- `PASS`
- `FAIL`
- `NOT_APPLICABLE`
- `NEEDS_REVIEW`

## Technology Stack

- Frontend: Next.js, TypeScript
- Authentication: Firebase Authentication
- Database: Cloud Firestore
- File Storage: Firebase Storage
- OCR: Provider-agnostic OCR adapter
- Rule Engine: Deterministic TypeScript-based rule engine

## Project Scope

This repository documents the proposed system architecture, workflows, planning, and development of Label Sentinel.

**Current Phase:** Week 1 – Project Planning and System Architecture

The platform is intended as a compliance-support tool and does not replace statutory authorities or authorized inspection decisions.

## Documentation

Project documentation and system design materials are maintained in the `docs/` directory.

## Project Reference

**SIH26034 – Label Sentinel**
