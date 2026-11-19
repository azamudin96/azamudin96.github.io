# Ruang. — Guesthouse & Event Booking Demo

A responsive, interactive proof-of-concept for a Malaysian guesthouse and event-space booking business. Built by AzariX Software as a client discussion demo.

**Public demo (GitHub Pages):** https://azamudin96.github.io/ruangstay-demo/

## What works

- Browse three sample guesthouses and two event venues.
- Search stays by check-in/check-out and guest count; search events by date and expected attendance.
- Validate date ranges and capacity and prevent overlapping active requests for the same listing.
- Calculate room nights, cleaning fees, event packages and optional add-ons.
- Submit demonstration booking/enquiry forms and receive a reference ID.
- Open **Dashboard admin** to see booking KPIs, review requests, confirm/reject/cancel them, and inspect a month calendar.
- Block/unblock inventory dates, filter/search records, export CSV, and reset demonstration data.
- Use the same UI on mobile, tablet and desktop.

## Quick start

Open `index.html` in a browser. No installation, build step or API key is required. All data is seeded automatically. Changes persist in `localStorage` in browsers that allow it. The demo can be deployed to any static host, including GitHub Pages.

## Important limitations

This is a **front-end interactive prototype, not a production booking platform**. No server, accounts, admin authentication, shared database, payment gateway, automatic WhatsApp/email/SMS, webhook, availability synchronization or real customer communications are integrated. Every visitor has **their own independent browser data**; a booking submitted on one person's device will not appear on another person's device. Please use fictional test names and phone numbers. The quoted 30% deposit is informational only; no money is charged.

For a paid release, implement a secure server/API, a shared transactional database with inventory locking, authentication and roles, payment provider/webhooks, reservation holds and expiry, notifications, audit logs, rate/seasonality management, cancellation policies and reliable deployment/monitoring. Malaysian legal/tax and privacy requirements must be separately confirmed with the business.

Photos load from Unsplash when online, with CSS fallbacks for offline preview.
