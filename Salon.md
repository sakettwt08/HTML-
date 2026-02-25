# PRD For Salon Shop
# PRD — Salon Shop Website

## Objective

Create an offline-capable, responsive HTML website for a local salon to showcase services, pricing, portfolio, team, and contact details — enabling customers to discover the salon and request appointments quickly.

## Scope

- In scope: static responsive HTML pages (or single-page with sections), services & prices, gallery, team profiles, contact & map link, appointment request form (client-side), asset optimization and offline caching for core pages.
- Out of scope (v1): full backend booking system, payment processing, user accounts, analytics beyond simple owner-tracked metrics.

## Audience & User Needs

- Local customers looking for salon services and prices.
- Mobile users who need quick contact or to request an appointment.

## Features & Requirements

### P1 (Must-have)
- Home/hero with phone CTA and hours.
- Services list with clear names, descriptions, and prices.
- Contact & location (address and map link) and a prominent phone number.
- Gallery of work with optimized images.
- Appointment request form (name, phone, service, preferred date/time) that sends via email (mailto) or client-side behavior.
- Responsive, accessible semantic HTML and image alt text.

### P2 (Should-have)
- Stylist/team profiles with specialties.
- Offline caching for core pages using a service worker.
- Basic client-side validation and user feedback on the form.

## User Stories

- As a potential customer, I want to see services and prices so I can decide to call or book.
- As a mobile user, I want to call the salon or request an appointment quickly.
- As a visitor, I want to view a gallery to assess the salon's work quality.

## Technical Requirements

- HTML5, CSS3 (mobile-first), minimal JavaScript.
- Images optimized and served responsively (srcset), lazy-loaded.
- Progressive enhancement: core content available without JS; JS adds form improvements and offline support.

## Design Requirements

- Clean, calming color palette and readable typography.
- Clear CTAs: `Call`, `Book`, `Directions`.
- Consistent photo style and accessible UI (contrast, keyboard focus states).

## Success Metrics

- Fast load on mobile (target: <3s on simulated 3G with optimized assets).
- Owner receives appointment requests (target: measurable initial volume — e.g., 10 requests in first 30 days).
- Users view services before leaving (owner-monitored conversion metric).

## Timeline (20 days)

- Days 1–3: Gather content (services, prices, images) and wireframes.
- Days 4–10: Build responsive HTML/CSS and pages (home, services, gallery, contact).
- Days 11–14: Form UX, image optimization, accessibility checks.
- Days 15–17: Add offline caching and QA.
- Days 18–20: Cross-device testing and handoff.

## Deliverables

- [index.html](index.html) (or single-page with sections), `gallery/` assets, `css/`, `js/` for form/offline support, and a short README with editing/deployment notes.

