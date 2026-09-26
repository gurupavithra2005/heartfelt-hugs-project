# Ticketing app completion plan

## Scope
Replace the blank preview with a usable ticket-booking application, then implement the requested AI recommendations and CSV operations exports while checking the uploaded evaluation criteria.

## Work
1. Build the event discovery and detail experience with sign-in, ticket selection, reservation, checkout, mock payment outcomes, and issued-ticket views using the existing secure booking rules.
2. Add role-checked staff validation and admin/staff operations views, including CSV exports with safe spreadsheet handling; add focused tests and concise security/architecture documentation.
3. Add an AI Gateway recommendation feature based on attendee dates, interests, and budget, with server-side model calls and safe error handling.
4. Add booking email notification hooks where the managed email service can be scaffolded; activate sending and reminders after the sender domain is configured.
5. Verify preview rendering, core user flows, mobile layout, accessibility affordances, and current build diagnostics. GitHub sync/push depends on project GitHub connection availability.

## Technical details
- Keep inventory, authorization, idempotency, pricing, signatures, and check-in decisions authoritative on the server/database.
- Use authenticated server functions for mutations and exports; enforce admin/staff roles on the server.
- Use the assigned Lovable AI Gateway Responses model and keep prompts and credentials server-side.
- Avoid fabricated email delivery, scheduled reminders, or GitHub push claims where required external setup is absent.
