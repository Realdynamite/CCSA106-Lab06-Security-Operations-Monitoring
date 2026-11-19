# CCSA106 – Lab 06: Security Operations Monitoring

## Overview

This repository contains my practical assessment for **CCSA106 – Check Point Security Operations Monitoring (R82)** under the ICDFA training programme.

The practical focuses on monitoring an assigned Check Point Security Gateway, reviewing log collection and retention, investigating firewall traffic, and checking gateway health.

## Objectives

The practical covers the following areas:

- Review Log Server indexing, storage and retention settings.
- Verify firewall rule tracking configurations.
- Use predefined and custom queries to investigate network traffic.
- Examine firewall events and interpret their actions.
- Monitor gateway health and available system counters.
- Compare firewall logs with administrative audit logs.

## Practical Sections

### Lab 6A – Elevate Traffic View

- A1: Inspect Logging Configuration
- A2: Verify Rule Tracking and Run a Predefined Query
- A3: Build and Test Custom Queries
- A4: Interpret a Firewall Event

### Lab 6B – Monitor System States

- B1: Review Gateway Status and System Counters
- B2: Compare Firewall and Audit Evidence

## Evidence

The assessment requires six evidence categories:

| Evidence | Description |
|---|---|
| E1 | Logging server, indexing and storage settings |
| E2 | Predefined query and firewall rule Track setting |
| E3 | Custom Accept and Drop query results |
| E4 | Detailed firewall log and traffic observation |
| E5 | Gateway status and system counters |
| E6 | Firewall and administrative audit logs |

Available screenshots are identified and dated in the accompanying report. Any evidence that could not be collected is explicitly identified.

## Storage Capacity Calculation

The practical includes a storage estimation exercise:

- Daily raw logs: 4 GB
- Daily indexes: 2 GB
- Indexed retention: 14 days
- Additional raw-log retention: 7 days
- Total storage budget: 140 GB

**Estimated storage usage:** 112 GB

**Remaining storage:** 28 GB

## Tools and Environment

- Check Point SmartConsole R82
- Check Point Security Gateway
- OpenVPN (ICDFA-assigned lab access)
- SmartView Monitor
- SmartView Web

## Access and Evidence Limitations

The assigned ICDFA laboratory VPN was unavailable on the assessment date because access was restricted to weekends. Consequently, some live configuration and log evidence could not be collected.

Previously captured SmartConsole screenshots are distinguished from observations made on the assessment date.

## Submission

The final practical report is provided as a PDF document.

**Course:** CCSA106  
**Module:** 6  
**Assessment:** Security Operations Monitoring Lab  
**Training Institution:** ICDFA

## References

- ICDFA – CCSA106 Module 6 Student Lab Brief.
- Check Point R82 Logging and Monitoring Administration Guide.
- Check Point SmartConsole Help.
