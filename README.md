# Lead Capture & Logging Automation

## Overview
This project implements a reliable lead capture and logging system for a marketing agency.
The goal is to ensure that every inbound lead is captured, standardized, timestamped, and stored in a single source of truth with minimal manual effort.

## Problem
Marketing agencies often receive leads through web forms, but manual handling leads to:
- Missed inquiries
- Slow response times
- Inconsistent data formatting
- Poor visibility into lead volume and sources

## Solution
An automated workflow that:
- Triggers on new form submissions
- Cleans and standardizes lead data
- Logs each lead into a structured Google Sheet
- Adds timestamps and lead source metadata
- Ensures consistent, auditable records

## Tech Stack
- Google Forms (lead input)
- Zapier (automation orchestration)
- Google Sheets (system of record)

## Workflow Summary
1. A lead submits a web form
2. The automation triggers immediately
3. Lead fields are cleaned and normalized
4. A new row is added to Google Sheets
5. The lead is timestamped and tagged with its source

## Success Criteria
- One row per form submission
- No missing required fields
- Consistent formatting across entries
- Timestamped records
- Easy review and filtering by the agency team

## Edge Cases Considered
- Empty optional fields
- Inconsistent name capitalization
- Duplicate email submissions
- Long free-text messages

## Outcome
This system removes manual data entry, reduces the risk of missed leads, and gives the agency a reliable, centralized view of inbound inquiries.

## Possible Extensions
- Slack or email notifications for high-intent leads
- CRM (HubSpot) integration
- Lead routing based on service or budget
- Error monitoring and alerting
