# Clinical Internship Management System

A centralized system for managing counseling students, internship sites, clinical placements, faculty tasks, and professional credentialing milestones.

## The Problem

Clinical internship management involves significantly more than assigning students to internship sites.

Programs must coordinate:

- Students
- Internship sites
- Site supervisors
- Faculty supervisors
- Placement interviews
- Documentation
- Training requirements
- Clinical hours
- Licensing requirements
- Site availability
- Student preferences
- Faculty follow-up

When these processes are distributed across email, spreadsheets, documents, and institutional systems, important tasks can easily become difficult to track.

## Solution

The Clinical Internship Management System organizes the internship lifecycle into a centralized workflow.

```text
Student
   ↓
Internship Readiness
   ↓
Site Matching
   ↓
Interview
   ↓
Placement
   ↓
Clinical Experience
   ↓
Hours / Requirements
   ↓
Credentialing Progress
```

## Major Components

### Internship Site Matching

Tracks potential internship sites and assists with matching students based on factors such as:

- Location
- Availability
- Population served
- Clinical opportunities
- Student interests
- Site requirements

### Clinical Placement Tracker

Tracks each student's progression through the placement process.

Example statuses include:

- Preparing
- Searching
- Site identified
- Interview scheduled
- Placement pending
- Placement confirmed
- Clinical experience active
- Completed

### Licensing Tracker

Tracks professional credentialing milestones associated with the student's clinical education.

This includes support for Wisconsin SAC-IT progression and related training requirements.

### Faculty Dashboard

Provides faculty with a centralized view of:

- Students requiring action
- Placement status
- Missing requirements
- Internship sites
- Upcoming deadlines
- Credentialing progress

## System Architecture

The system was designed to take advantage of Microsoft 365 tools commonly available within educational institutions.

Potential architecture:

```text
Microsoft Lists
       ↓
Central Internship Data
       ↓
Workflow / Automation
       ↓
┌──────────────┬──────────────┐
│ Faculty View │ Student View │
└──────────────┴──────────────┘
       ↓
Reporting / Analytics
```

Technologies explored include:

- Microsoft Lists
- SharePoint
- Teams
- Power Automate
- Power Apps
- Power BI
- Excel

## Supporting Tools

Several spreadsheet-based tools were developed as part of the broader system concept, including:

- Internship Site Matching
- Clinical Placement Tracker
- SAC-IT Licensing Tracker
- Automated completion calculations
- Standardized status fields
- Dropdown-driven data entry

These tools can function independently or serve as prototypes for a larger database-driven system.

## Design Goals

- Reduce repetitive faculty administrative work
- Identify stalled placements quickly
- Improve student visibility into the internship process
- Centralize internship-site information
- Standardize placement workflows
- Connect internship completion with professional credentialing

## Privacy

Real student records, educational records, clinical information, passwords, access tokens, and institutional credentials must never be committed to the public repository.

Demo or synthetic data should be used for public demonstrations.

## Project Status

Working tools + broader system architecture under development.
