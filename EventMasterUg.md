eventmaster-ug/
│
├── frontend/                                    # All client-side files
│   │
│   ├── public/                                  # Publicly accessible (no auth)
│   │   ├── index.html                           # Landing page – hero, featured events, categories
│   │   ├── events.html                          # Browse events – filters by category, city, date
│   │   ├── event-details.html                   # Single event view – venue map, ticket types
│   │   ├── seat-selection.html                  # Interactive seat/table map
│   │   ├── checkout.html                        # Payment page – MoMo, Airtel, card
│   │   ├── payment-success.html                 # Payment confirmation
│   │   ├── receipt.html                         # Digital receipt with QR codes
│   │   ├── about.html                           # About EventMaster UG
│   │   ├── contact.html                         # Contact form
│   │   ├── faq.html                             # Frequently asked questions
│   │   ├── terms.html                           # Terms of service
│   │   ├── privacy.html                         # Privacy policy
│   │   └── 404.html                             # Not found page
│   │
│   ├── auth/                                    # Authentication pages
│   │   ├── login.html                           # Sign in – demo accounts available
│   │   ├── register.html                        # Two‑step registration with role selection
│   │   ├── forgot-password.html                 # Password reset request
│   │   ├── reset-password.html                  # New password form (token)
│   │   └── verify-email.html                    # Email verification
│   │
│   ├── dashboard/                               # Role‑based dashboards (each includes RBAC)
│   │   ├── admin/                               # System Administrator
│   │   │   ├── index.html
│   │   │   ├── analytics.html
│   │   │   ├── users.html
│   │   │   ├── roles.html
│   │   │   ├── events.html
│   │   │   ├── event-approvals.html
│   │   │   ├── venues.html
│   │   │   ├── transactions.html
│   │   │   ├── refunds.html
│   │   │   ├── payment-gateways.html
│   │   │   ├── reports.html
│   │   │   ├── revenue-report.html
│   │   │   ├── user-report.html
│   │   │   ├── event-report.html
│   │   │   ├── system-logs.html
│   │   │   ├── security-logs.html
│   │   │   ├── error-logs.html
│   │   │   ├── settings.html
│   │   │   ├── email-settings.html
│   │   │   ├── sms-settings.html
│   │   │   ├── notification-templates.html
│   │   │   ├── backup.html
│   │   │   └── profile.html
│   │   │
│   │   ├── manager/                             # Event Organizer / Manager
│   │   │   ├── index.html
│   │   │   ├── my-events.html
│   │   │   ├── create-event.html                # Full wizard with 25 categories + location cascade
│   │   │   ├── edit-event.html
│   │   │   ├── duplicate-event.html
│   │   │   ├── my-venues.html
│   │   │   ├── create-venue.html                # New location fields (region/district/town)
│   │   │   ├── edit-venue.html
│   │   │   ├── seat-builder.html
│   │   │   ├── ticket-types.html
│   │   │   ├── promo-codes.html
│   │   │   ├── create-promo.html
│   │   │   ├── attendees.html
│   │   │   ├── attendee-messages.html
│   │   │   ├── my-staff.html
│   │   │   ├── invite-staff.html
│   │   │   ├── staff-permissions.html
│   │   │   ├── sales-report.html
│   │   │   ├── attendance-report.html
│   │   │   ├── revenue-report.html
│   │   │   ├── check-in-log.html
│   │   │   ├── export-report.html
│   │   │   ├── settings.html
│   │   │   └── profile.html
│   │   │
│   │   ├── staff/                               # Check‑in Staff
│   │   │   ├── index.html
│   │   │   ├── check-in.html
│   │   │   ├── manual-check-in.html
│   │   │   ├── attendee-lookup.html
│   │   │   ├── my-scans.html
│   │   │   ├── event-info.html
│   │   │   ├── my-schedule.html
│   │   │   └── profile.html
│   │   │
│   │   ├── cashier/                             # Cashier / POS Operator
│   │   │   ├── index.html
│   │   │   ├── pos.html
│   │   │   ├── quick-sale.html
│   │   │   ├── transactions.html
│   │   │   ├── transaction-history.html
│   │   │   ├── issue-receipt.html
│   │   │   ├── reprint-receipt.html
│   │   │   ├── void-transaction.html
│   │   │   ├── cash-drawer.html
│   │   │   ├── open-shift.html
│   │   │   ├── close-shift.html
│   │   │   ├── end-of-day.html
│   │   │   └── profile.html
│   │   │
│   │   └── customer/                            # Ticket Buyer
│   │       ├── index.html
│   │       ├── my-tickets.html
│   │       ├── upcoming-events.html
│   │       ├── past-events.html
│   │       ├── purchase-history.html
│   │       ├── my-receipts.html
│   │       ├── offline-receipts.html
│   │       ├── saved-events.html
│   │       ├── notifications.html
│   │       ├── settings.html
│   │       ├── change-password.html
│   │       ├── payment-methods.html
│   │       ├── transfer-ticket.html
│   │       └── profile.html
│   │
│   ├── assets/                                  # Static resources
│   │   ├── css/
│   │   │   ├── global.css
│   │   │   ├── components.css
│   │   │   ├── dashboard.css
│   │   │   ├── forms.css
│   │   │   ├── seat-map.css
│   │   │   ├── scanner.css
│   │   │   ├── receipt.css
│   │   │   └── print.css
│   │   ├── js/
│   │   │   ├── app.js
│   │   │   ├── api.js
│   │   │   ├── auth.js
│   │   │   ├── utils.js
│   │   │   ├── notifications.js
│   │   │   ├── modal.js
│   │   │   ├── qr-generator.js
│   │   │   ├── qr-scanner.js
│   │   │   ├── receipt-generator.js
│   │   │   ├── offline.js
│   │   │   ├── charts.js
│   │   │   ├── locations.js                     # [NEW] All Uganda regions, districts, cities, town councils
│   │   │   └── rbac.js                          # [NEW] RBAC helper – check role, redirect if unauthorized
│   │   ├── images/
│   │   │   ├── logo.svg
│   │   │   ├── icons/                           # MoMo, Airtel, etc.
│   │   │   └── profiles/
│   │   └── fonts/
│   │
│   ├── manifest.json
│   ├── service-worker.js
│   └── robots.txt
│
├── backend/                                     # Server‑side PHP application
│   ├── config/
│   │   ├── database.php
│   │   ├── app.php
│   │   ├── payments.php
│   │   └── constants.php
│   ├── middleware/
│   │   ├── AuthMiddleware.php
│   │   ├── RoleMiddleware.php                   # [UPDATED] Validates against expanded roles
│   │   ├── RateLimitMiddleware.php
│   │   └── CorsMiddleware.php
│   ├── controllers/
│   │   ├── AuthController.php
│   │   ├── EventController.php                  # [UPDATED] Accepts new categories, location cascade
│   │   ├── TicketController.php
│   │   ├── PaymentController.php
│   │   ├── UserController.php
│   │   ├── VenueController.php                  # [UPDATED] Handles region/district/town_council
│   │   ├── PromoController.php
│   │   ├── ReportController.php
│   │   └── DashboardController.php
│   ├── models/
│   │   ├── User.php
│   │   ├── Event.php
│   │   ├── Venue.php                             # [UPDATED] New attributes: region, district, town_council
│   │   ├── Ticket.php
│   │   ├── Order.php
│   │   └── ...
│   ├── services/
│   │   ├── MomoService.php
│   │   ├── AirtelService.php
│   │   └── ...
│   └── helpers/
│
├── database/
│   ├── schema.sql                                # [UPDATED] Added region/district/town_council, extended category enum
│   ├── seed.sql                                  # [UPDATED] Seeds all Uganda locations, demo events with new categories
│   └── migrations/
│       └── 018_add_location_fields.sql           # [NEW] Migration to add new columns
│
├── storage/
│   ├── receipts/
│   ├── exports/
│   └── logs/
│
├── .htaccess
├── index.php
├── README.md
└── CHANGELOG.md