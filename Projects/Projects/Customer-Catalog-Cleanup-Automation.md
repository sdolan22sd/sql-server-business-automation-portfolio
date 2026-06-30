# Customer Catalog Cleanup Automation

## Overview

The Customer Catalog Cleanup Automation project was developed to improve the management of customer catalog data by replacing a manual cleanup process with a controlled, SQL Server-based workflow. The solution identifies obsolete customer catalog records, routes them through a business review process, maintains a complete audit history, and safely automates the cleanup of production data.

The project improves data quality, reduces manual effort, and minimizes the risk of accidental data loss by ensuring catalog changes are reviewed and tracked before implementation.

---

## My Role

I assisted in designing and implementing the SQL Server solution, including the stored procedures, business rules, audit process, and reporting workflow used to identify and manage obsolete customer catalog records. My responsibilities included developing T-SQL stored procedures, implementing SQL triggers for auditing, designing approval workflows, validating business logic, and testing the automation prior to production deployment.

---

## Technologies

- Microsoft SQL Server
- T-SQL
- Stored Procedures
- SQL Triggers
- Audit Tables
- SSRS
- SQL Server Agent

---

## Business Problem

Over time, customer catalogs accumulated obsolete and inactive product records that required manual review and cleanup. The existing process was time-consuming, difficult to audit, and increased the risk of deleting records without sufficient visibility or business approval.

---

## Solution

The solution automates the identification of customer catalog records that meet predefined deletion criteria. Candidate records are stored in a staging process where business users can review the proposed changes through SQL Server Reporting Services (SSRS) reports before any production updates occur.

Once approved, automated SQL processes update or remove the appropriate records while maintaining a complete audit trail for future reference. The workflow provides a structured, repeatable process that improves both data integrity and operational efficiency.

---

## Outcome

- Automated identification of obsolete customer catalog records.
- Reduced manual catalog maintenance.
- Added business approval before production cleanup.
- Implemented complete audit history for catalog changes.
- Improved data integrity and reduced operational risk.
- Created a repeatable and scalable catalog maintenance process.
