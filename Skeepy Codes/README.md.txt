Skeepy WordPress HMO System

A suite of WPCode Pro snippets for the Skeepy Pet HMO system, covering pet registration, clinic partnerships, dashboards, payment verification, pricing, and global styling.

Table of Contents

Overview

Snippet Organization

Pet Module

Clinic Module

Admin Module

Shared Components

General & Standalone Tasks

Installation

Configuration

Usage

Styling

Contributing

Overview

The Skeepy Pet HMO WordPress System is built entirely with WPCode Pro snippets. It provides:

Pet Signup & Dashboard: Register pets for HMO plans and manage their profiles.

Clinic Partnership System: Allow clinics to apply, automatically create WP users, and submit claims.

Admin Dashboard: A full administrative interface for system-wide overview and management.

Payment Verification: Integrates with Paystack to confirm payments and activate HMO plans.

Pricing Section: An interactive pricing toggle for monthly, quarterly, and annual plans.

Global Styling: CSS variables and utility classes for a cohesive design system.

Utility Snippets: Miscellaneous tasks like hiding admin bars, headers/footers, and benefit tracking.

Snippet Organization

Pet Module

File

Snippet Name

Usage/Hook

Skeepy Complete Pet Signup System.txt

Skeepy – Pet Signup & User Creation

Shortcode: [skeepy_pet_signup]

Skeepy Pet Sign In Form.txt

Skeepy – Pet Sign In Form

Ajax: wp_ajax_nopriv_skeepy_pet_signin

Skeepy Pet Dashboard.txt

Skeepy – Pet Dashboard

Shortcode: [skeepy_pet_dashboard]

Clinic Module

File

Snippet Name

Usage/Hook

Skeepy Complete Clinic Partnership System.txt

Skeepy – Clinic Signup & User Creation

Shortcode: [skeepy_clinic_signup]

Skeepy Claims Form.txt

Skeepy – Clinic Claims Form

Shortcode/Function: skeepy_claims_form

Skeepy Clinic Dashboard.txt

Skeepy – Clinic Dashboard

Shortcode: [skeepy_clinic_dashboard]

Admin Module

File

Snippet Name

Usage/Hook

Skeepy Admin Dashboard.txt

Skeepy – Admin Dashboard

Shortcode: [skeepy_admin_dashboard]

Shared Components

File

Snippet Name

Purpose

Skeepy Complete Database Creation System.txt

Skeepy – Database Tables Creation

Creates skeepy_pets, skeepy_clinics, skeepy_claims

Skeepy Payment Verification & Activation.txt

Skeepy – Payment Verification & Activation

Ajax: skeepy_verify_payment and Paystack integration

Skeepy Unified Benefit Tracker.txt

Skeepy – Unified Benefit Tracker

Tracks benefit usage across modules

Skeepy Admin Interface.txt

Skeepy – Admin Interface Tools

Utility functions for admin metrics and dashboards

Skeepy Admin Benefit Tools.txt

Skeepy – Admin Benefit Tools

Benefit calculation helpers

Skeepy Clinic Dashboard Relationship Connector.txt

Skeepy – Clinic Dashboard Connector

Links clinic records to the dashboard

Skeepy Clinic Sign In Form.txt

Skeepy – Clinic Sign In Form

Ajax: wp_ajax_nopriv_skeepy_clinic_signin

Skeepy Global Styling System – Brand & Components.txt

Skeepy – Global Styling System

CSS variables and utility classes

General & Standalone Tasks

File

Snippet Name

Purpose

Skeepy Pricing Section.txt

Skeepy – Pricing Section

Shortcode: [skeepy_pricing_section]

Hide Admin Bar When Signed In.txt

Skeepy – Hide Admin Bar for Users

Hides WP admin bar for non-admin logged-in users

Hide Header and Footer for Signed in Users.txt

Skeepy – Hide Header/Footer for Logged‑in Users

Injects CSS to hide header/footer when appropriate

Installation

Install WPCode Pro: If not installed, add the WPCode Pro plugin.

Import Snippets: In WPCode, create a new snippet for each .txt file. Paste its content and assign the suggested Snippet Name.

Activate: Choose the appropriate insertion method (Shortcode, Header/Footer, etc.) for each snippet and save.

Create Pages:

Pet Signup: Add [skeepy_pet_signup]

Pet Sign In: Use the slug/shortcode for pet sign-in

Pet Dashboard: [skeepy_pet_dashboard]

Clinic Signup: [skeepy_clinic_signup]

Clinic Dashboard: [skeepy_clinic_dashboard]

Admin Dashboard: [skeepy_admin_dashboard]

Pricing Page: [skeepy_pricing_section]

Configuration

Paystack Key: Update the secret key in the Payment Verification & Activation snippet.

Roles & Capabilities: Custom roles (skeepy_pet, skeepy_clinic, skeepy_admin) are defined—ensure no conflicts with existing roles.

Permalinks: Enable pretty permalinks under Settings > Permalinks.

AJAX Security: Verify nonces are correctly localized and validated.

Usage

Pet Owners: Register pets, view HMO coverage, and book services.

Clinics: Apply for partnership, submit claims via the claims form, and manage through dashboard.

Administrators: Monitor overall adoption, revenue, pending approvals, and generate system backups and reports.

Styling

All components rely on the Global Styling System snippet, which provides:

CSS variables (colors, spacing, shadows).

Utility classes for layout, typography, and responsive design.

You can extend or override these styles in a child theme or custom CSS.

Contributing

Fork the repository.

Add or update snippets under the relevant module folder.

Submit a pull request with clear descriptions and testing steps.

Thank you for using the Skeepy Pet HMO WordPress System! We welcome your feedback and contributions.

