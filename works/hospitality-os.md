# Hospitality OS

**Cafe Milano · Restaurant point-of-sale interface prototype**  
*React · Vite · Browser-local demo state*

[Repository](https://github.com/Z-A-R-R-O/hospitality-os) · [Live site](https://hospitality-os-two.vercel.app)

## The experience

Hospitality OS is a restaurant operations interface concept for a fictional Cafe Milano environment. It brings common service tasks into one workspace: taking orders, managing table context, reviewing reservations, viewing the menu, kitchen display, inventory, customers, reports, staff, and settings.

## Interaction model

- Menu items can be added to an order and quantities changed.
- The pricing module calculates subtotals, tax, service, discounts, and totals.
- Orders can be held and restored, then completed into local demo receipts.
- Demo state is persisted in the browser through localStorage.

The source uses sample menu items and illustrative service data. The displayed totals and operational numbers are not evidence of actual restaurant activity.

## Technical shape

The repository uses React with Vite and Lucide icons. Pricing logic is separated into a small module, and a local store hook keeps demo order state distinct from the main screen.

## Boundaries

This is a frontend prototype. The reviewed code uses browser-local state and sample data; it does not establish a production backend, real payment processing, live inventory, or multi-user synchronization.

## Why it belongs in the portfolio

It demonstrates interaction design for a dense workflow: keep high-frequency tasks visible, separate navigation from order context, and make totals understandable without turning the screen into visual noise.

*Operations software should make busy work feel less chaotic.*
