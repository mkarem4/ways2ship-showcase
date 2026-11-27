# Ways2Ship — Shop and Ship from the United States

**Your US address, your packages, your door.** Ways2Ship is a package forwarding and cross-border shipping platform: customers shop from US stores with a US address, and Ways2Ship receives, checks, repacks and ships the order to their home country.

🔗 Live product: **[ways2ship.com](https://ways2ship.com)**

> This repository is a project showcase. It contains documentation only — the production source code is private.

---

## Overview

Buying from US stores is easy. Getting the parcel home is not. Ways2Ship gives every customer a US shipping address, receives their packages, verifies and consolidates them, then ships internationally with the carrier that fits.

The platform integrates carrier APIs for **live shipment tracking**, so a customer follows the parcel from the US warehouse to their door without asking support where it is.

## My role

**Senior Laravel Backend Engineer & Backend Team Lead**

- Built the shipping platform backend: customer accounts with US addresses, package intake, consolidation and shipment records.
- Integrated the **FedEx** and **DHL** APIs for live tracking and status updates.
- Built the real-time tracking layer with WebSockets so shipment status updates reach the customer as they happen.
- Optimised the MySQL queries behind the package and shipment lists.
- Worked on payment and delivery flows with the product team.

## Tech stack

| Area | Stack |
| --- | --- |
| Language & framework | PHP, Laravel, MVC, Eloquent ORM |
| Real time | WebSockets (Laravel Reverb / Pusher) |
| Integrations | FedEx API, DHL API |
| Data | MySQL, Redis caching |
| Background work | Laravel queues |
| Delivery | Git, CI/CD, Linux, Nginx |

## Key features

**Shopping and receiving**
- A personal US address for every customer.
- Package intake with verification, repacking, and consolidation of several orders into one shipment.
- Support for orders from US and international stores.

**Shipping**
- Multiple carrier options with shipment booking.
- International delivery to the customer's local address, dispatched within 24 hours of intake.
- Shipment lifecycle tracking from warehouse to delivery.

**Live tracking**
- FedEx and DHL tracking events pulled into a single timeline.
- Real-time status updates pushed to the customer over WebSockets.

**Customer account**
- Address book, package list, shipment history and shipping cost estimates.

## About this repository

This is a documentation-only showcase of a production product. It contains no client code, data or infrastructure details.

**Mohamed Karem Tawfik** — Senior PHP / Laravel Developer, Backend Team Lead
[GitHub](https://github.com/mkarem4) · [LinkedIn](https://linkedin.com/in/mohamed-karem93) · [ways2ship.com](https://ways2ship.com)
