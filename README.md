# Food Delivery Platform — System Design & Implementation (MVP)

This repository contains the **system analysis, documentation, and implementation** of a food delivery platform MVP.  
It covers the full journey from **product scope and feature breakdowns** to **backend/mobile code**, and will evolve with each milestone.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [MVP Scope](#mvp-scope)
3. [User Roles](#user-roles)
4. [Features & Functions](#features--functions)
5. [System Design](#system-design)
6. [Implementation](#implementation)
7. [Repository Structure](#repository-structure)
8. [Roadmap](#roadmap)
9. [Notes](#notes)

---

## Project Overview
A platform that connects customers with restaurants to browse menus, place orders, complete checkout, and track order status.  
In the MVP phase, **delivery is handled by restaurants** (no platform driver system in phase 1).

---

## MVP Scope
### Included
- Customer ordering experience (browse → cart → checkout → order tracking)
- Restaurant dashboard for managing orders, menus, store settings, promotions, and staff access
- Admin dashboard for managing platform operations (users, restaurants, orders, payments, disputes, settings)

### Not Included (Phase 1)
- Platform drivers / driver app
- Live driver map tracking (status-based tracking only)

---

## User Roles
- **Customer**
- **Restaurant**
- **Admin**

---

## Features & Functions
> Each role has a dedicated feature map attached as an image.

### Customer
![Customer Features & Functions](./doc/feature_and_function_customer.svg)

### Restaurant
![Restaurant Features & Functions](./doc/feature_and_function_resturant_food_delivery.svg)

### Admin
![Admin Features & Functions](./doc/feature_and_function_admin_food_delivery.svg)

---

## System Design
> This section documents core system design artifacts and decisions.

- Architecture overview (services/modules)
- Data model (ERD)
- Core flows (order lifecycle, payment flow, cancellations/refunds)
- API contracts

> Artifacts will be stored under: `docs/system-design/`

---

## Implementation
> The codebase will include the platform implementation and supporting modules.

- Backend services (APIs, database, authentication, orders, payments)
- Client apps (customer-facing)
- Dashboards (restaurant + admin)

---
