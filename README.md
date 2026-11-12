# RentHub — Equipment Rental Marketplace

**CSE327 Software Engineering | Group Project**

## Group Members

| Name | Student ID |
|---|---|
| Aisha Abedin | 2412011042 |
| Sumaiya Chowdhury Sumo | 2411300642 |
| Salman Kabir | 2412347042 |

## Project Overview

RentHub is a proposed web-based equipment rental marketplace connecting customers with independent rental businesses. Customers can browse and compare equipment, check availability, and book items such as cameras, projectors, audio/video equipment, sports equipment, bicycles, storage devices, and computer accessories.

The platform aims to replace scattered messages and manual rental records with organized booking, inventory, payment-status, and equipment-return management.

## Main Features

- **Customer accounts:** Registration and login; customers provide contact details and required identification before renting.
- **Equipment search and booking:** Browse business storefronts, check availability, and request hourly or daily rentals (one day = 24 hours).
- **Business management:** Business owners manage profiles, branches, listings, individual equipment units, prices, and booking approval policies.
- **Availability tracking:** Record bookings, offline rentals, maintenance, and stock changes to prevent overlapping reservations.
- **Customer verification:** Business owners verify identification before handing over equipment.
- **Direct rental payments:** Customers pay rental charges and deposits directly to business owners; owners record payment status in RentHub. No online rental payment gateway is planned.
- **Business subscriptions:** Owners choose monthly plans, pay via bKash or bank transfer, and submit transaction details for administrator verification.
- **Equipment history:** Track handovers, returns, inspections, maintenance, and each unit's rental history (Unit Passport).
- **Notifications and audit records:** Record important booking and administrative updates.

## User Roles

1. **Customer** — Register, browse, book, and track rentals.
2. **Business Owner** — Manage the business, inventory, bookings, customer verification, payments, and returns.
3. **Platform Administrator** — Approve businesses, verify subscription payments, manage subscriptions, and review audit records.

## Proposed Technology Stack

| Layer | Technology |
|---|---|
| Frontend | React with TypeScript |
| Backend | Java Spring Boot |
| Database | MySQL |

## Design Patterns

- **Strategy:** Hourly and daily rental pricing.
- **Decorator:** Optional rental services added to quotations.
- **Observer:** Booking notifications and related updates.
- **Proxy:** Authorization for protected business operations.

## Key Rental Rules

- **Hourly charge:** Booked hours × hourly rate.
- **Daily charge:** Booked 24-hour periods × daily rate.
- Bookings may be confirmed before the customer pays.
- Before handover, the business owner verifies customer identification and records any required payment and deposit.
- After return, the business owner records the return time and inspects the equipment before it becomes available again.

## Project Status

**Proposal / design stage.** Implementation and setup instructions will be added as development progresses.

## Project Documentation

See the RentHub CSE327 project proposal PDF for functional and nonfunctional requirements, ER diagrams, use-case diagrams, class diagrams, and the booking sequence diagram.
