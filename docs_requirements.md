# Requirements & Features

## Problem Statement
Franchise businesses struggle with scattered data, manual compliance, and lack of sales insights. This CRM solves these problems via Salesforce automation and dashboards.

## Objectives
- Centralize data for franchisees, outlets, sales, and compliance
- Automate compliance/audit workflows
- Analyze sales and identify trends
- Manage franchisee agreements and renewals
- Provide actionable dashboards

## Key Data Model
- **Franchisee**: Name, contact, agreement, renewal date
- **Outlet**: Name, location, linked franchisee
- **Sales Record**: Date, amount, linked outlet
- **Compliance Check**: Date, status, linked outlet

## User Roles
- Franchisee: Can view/edit own outlet data
- Manager: Can view/edit all data
- Auditor: Can view compliance records

## Next Steps
1. Create custom objects & fields in Salesforce
2. Set up relationships
3. Define user roles & permissions
4. Draft automation workflows (Flows, Process Builder)
5. Build basic dashboards and reports