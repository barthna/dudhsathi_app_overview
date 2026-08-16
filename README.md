# Dudh Sathi App

> Digital Dairy Management Companion for Milk Vendors & Dairy Businesses.

---

## 📋 About the Project

**Dudh Sathi** is a professional-grade mobile application designed to help milk vendors and dairy business owners digitally manage their daily operations. Traditionally, milk vendors rely on manual register books to track daily distributions, milk measurements, customer accounts, and billing, which is prone to human error and data loss. Dudh Sathi solves this problem by providing a modern, reliable, and offline-first digital ledger that simplifies customer management, milk logs, and payment tracking directly from a mobile device.

---

## ✨ Key Features

- **Customer Ledger Management:** Create and maintain digital profiles for customers with customizable milk delivery preferences (morning/evening shifts, fat content, standard pricing, or custom rates).
- **Daily Milk Logging:** Log milk quantity, milk types (buffalo, cow, mixed), and rate calculations for each customer with just a few taps.
- **Automated Billing & Invoicing:** Automatically calculate monthly bills, outstanding balances, and generate PDF invoices that can be shared instantly via messaging platforms.
- **Analytical Reports:** View visual charts (monthly earnings, customer growth, and milk collection trends) to make data-driven business decisions.
- **Secure Data Sync & Backup:** Cloud-hosted backup to prevent data loss while supporting offline caching for areas with poor connectivity.
- **Google Play Subscriptions:** Premium features unlocked seamlessly via Google Play Billing integrated with subscription limits.

---

## 🛠️ Technology Stack

- **Frontend Framework:** Flutter (Dart)
- **Backend & Database:** Cloud Firestore & Firebase Storage
- **Authentication:** Firebase Authentication
- **Local Data & Caching:** SharedPreferences & path_provider
- **Analytics & Visualizations:** fl_chart
- **Billing System:** Google Play Billing (in_app_purchase / purchases_flutter)
- **Notifications & Scheduling:** Firebase Cloud Messaging & flutter_local_notifications
- **Utilities:** pdf, printing, qr_flutter, share_plus, url_launcher, and lottie for animations.

---

## 🚀 App Highlights

- **Google Play Billing Integration:** Uses Google Play Billing as the single source of truth for access control. It handles recurring subscriptions, automated customer limits based on plans, license testing (3-minute trials), and background state restoration upon reinstall.
- **Offline-First Capabilities:** Built with local caching using SharedPreferences, allowing vendors to record deliveries in rural areas without internet access. Data is automatically synchronized asynchronously once an active connection is restored.
- **Shareable PDF Reports:** Generates professional-looking milk transaction receipts and monthly summaries using native PDF rendering and printing libraries.

---

## 📥 Google Play Store

The application is available for download on the Google Play Store:

[![Download on Google Play](https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png)](https://play.google.com/store/apps/details?id=com.dudhsathi.milk_dairy_app)

---

## 🔒 Source Code

The source code for this project is hosted in a private repository. This repository is created only to showcase the project details, key features, and technology stack.

---

## 📈 Project Status

The app is **Active** and currently deployed on the Google Play Store. Regular updates include performance optimizations, security patches, and localized language support.

---

## 👤 Developer

Developed by **Barthna and her team, Codetrio Studios**.

- **GitHub:** [Codetrio Studios](https://github.com/code3trio)
- **Contact:** [codetrio.studios@gmail.com](mailto:codetrio.studios@gmail.com)
