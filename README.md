# Equipment Rental

**Reservation, availability, checkout, return, invoicing, and equipment management software for small rental businesses.**

Equipment Rental is a local-first operations application designed to organize the complete rental workflow in one place:

**Customer → Equipment → Availability → Reservation → Check-out → Return Inspection → Charges → Invoice → Payment Record → Rental History**

> This repository is a **public product showcase only**. The commercial application source code is kept private.

## The Problem

Small rental businesses often track equipment, reservations, deposits, pickups, returns, damage, maintenance, and invoices across spreadsheets, paper forms, and memory.

Equipment Rental brings those workflows into one structured workspace so staff can see what is available, what is reserved, what is currently rented, what is overdue, and what still needs to be billed or maintained.

## Core Features

- Equipment records with rates, meter data, status, maintenance history, and rental history
- Customer records with active rentals, reservations, balances, invoices, and return notes
- Availability checks that prevent reservation overlaps and maintenance conflicts
- Reservation creation and management with pricing snapshots
- Check-out workflow with condition, accessories, meter values, deposits, and printable agreements
- Structured return workflow with late fees, damage/cleaning charges, and maintenance handoff
- Invoice generation with deposits, payments, balances, and printable receipts
- Maintenance scheduling with equipment availability effects
- Dashboard metrics for equipment status, overdue rentals, pickups, returns, unpaid invoices, deposits, revenue, and utilization
- Reports for revenue, utilization, balances, overdue rentals, most-rented assets, fees, maintenance spending, and history
- JSON backup/export and import
- Automated tests around pricing, availability, deposits, checkout, returns, invoicing, and reporting

## Designed For

- Tool rental businesses
- Equipment rental yards
- Contractors renting equipment
- Event rental companies
- Owner-operators
- Small specialty rental businesses

## Technology

The current web product is built with:

- React
- Vite
- JavaScript
- Plain CSS
- Browser localStorage
- Testable domain modules

A separate React Native mobile companion has also been developed for mobile rental workflows.

## Product Direction

The current version is intentionally local-first. Future commercial additions could include cloud sync, authentication, staff accounts, multi-location inventory, dispatch/calendar views, equipment photos, customer portals, online payments, digital agreements, and accounting integrations.

## Commercial Use

The complete Equipment Rental implementation is maintained privately while the product is prepared for commercial licensing and customization.

This repository demonstrates the product interface, workflow design, business logic, and development capabilities without distributing the commercial source code.

## About the Developer

Built by **Amani Robinson**, a React developer focused on business applications, dashboards, workflow tools, CRM-style systems, and operational software.

---

**Equipment Rental** — one workspace for equipment, reservations, rentals, returns, and billing.

All rights reserved.
