---
layout: post
type: case-study
title: "Modernising HR Infrastructure: The Employee Records Digitisation Project"
date: 2020-09-30 09:00:00 -0000
categories: [data-modelling, operations]
permalink: /writing/eko-hotels-digitisation/
---

 * **Project Type:** Operational Transformation & Digital Migration
 * **Organization:** Eko Hotels and Suites (Largest hospitality brand in West Africa)
 * **My Role:** HR Intern & Systems Initiative Lead
 * **Tools Used:** Advanced Excel (Data Arrays, Cross-Referencing Formulas, VLOOKUP/INDEX-MATCH architecture), Physical Archival Schemas

## 1. The Challenge & Context
As Eko Hotels and Suites rapidly expanded to anchor itself as West Africa’s premier hospitality brand, its internal administrative infrastructure lagged behind its commercial growth.
Upon joining the Human Resources department, I inherited an entirely manual information system: the records of over **2,400 current employees and legacy leavers spanning a 10-year history** were stored exclusively in physical files and cabinets.
### The Operational Bottlenecks:
 * **Severe Retrieval Latency:** Locating a single file for urgent disciplinary actions, compliance audits, or regulatory updates could take hours—sometimes days—disrupting departmental timelines.
 * **Compliance Risk:** A lack of centralized indexing meant there was no immediate way to audit file completeness, track document variables, or safeguard against missing historical records.
 * **Scale Vulnerability:** The physical filing footprint was expanding unsustainably, rendering the traditional "paper-first" workflow obsolete for a business of this scale.
Recognising this in my first week, I identified this not just as an administrative inconvenience, but as a high-leverage operational risk that required a structural solution.

## 2. The Strategy & Execution
Despite my formal designation within HR, I drew upon my early foundational training in computer engineering and advanced Excel capabilities to design a digital-first solution. Because the business still required physical file retention for legal compliance, the objective was to create a **hybrid data ecosystem**: complete digital visibility backed by an exact physical reference system.
### Phase 1: Data Auditing & Mapping (The "Schema" Design)
Before inputting any data, I spent time modeling the staff information. I audited the entire file library to identify every critical data point required by the business and categorized them by functional behavior:
 * **Static Data:** Fixed attributes that never change (e.g., National ID, Employee Name, Date of Birth, Original Hire Date).
 * **Variable Data:** Dynamic attributes requiring regular tracking and updating (e.g., Department, Current Status, Disciplinary Records, Promotion History).
By distinguishing between these data states, I ensured the digital directory would remain clean, scalable, and easy for non-technical HR staff to update.
### Phase 2: Building the Digital Relational Model
Using advanced spreadsheet architecture, I built a centralized database directory.
 * Designed a uniform template for employee profiles, turning messy paper trails into structured, predictable data sets.
 * Engineered a strict **Unique Identifier (ID) system** that served as a "primary key," ensuring that no two employees could be confused, even with identical or similar names.
 * Built automated lookup cross-references, allowing the HR team to query an employee ID and instantly pull up their complete professional history on one screen.
### Phase 3: Physical-to-Digital Indexing
To ensure the physical files could be retrieved instantly when needed, I mapped the digital directory directly to the physical storage landscape. Every digital record contained a precise location index (e.g., Cabinet A, Drawer 3, File 42), linking the screen instantly to the shelf.

## 3. Business Impact & Outcomes
The implementation of this system completely transformed the daily workflow of the HR department, moving it from a reactive, paper-hunting unit to a proactive, digitally enabled operation.
 * **"Zero-Touch" Data Retrieval:** Over 90% of routine information queries were shifted entirely to the screen. HR personnel could verify employment history, check compliance status, or review past actions instantly without ever touching a physical file cabinet.
 * **Drastic Time Reductions:** The time required to locate and verify personnel files for critical disciplinary or regulatory audits dropped from hours to seconds.
 * **100% Record Integrity:** Successfully digitized and structured a decade's worth of records for 2,400+ personnel, eliminating data duplication and closing operational gaps.

## 4. Professional Evolution: Connecting to the Present
While this project was built early in my career using advanced spreadsheet structures rather than formal enterprise tools like UML diagrams or SQL databases, the core intellectual challenge was identical to modern enterprise data architecture.
