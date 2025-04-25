# GOTS - Going Once, Twice, Sold 🇵🇰

**A Firebase-powered auction platform built for Pakistan. Inspired by eBay, localized for our people.**

---

## 📦 Features

- 🔐 **User Authentication**
  - Firebase Authentication (Email + Password + Phone OTP)
  - reCAPTCHA integration for security
- 📱 **User Registration with Phone Verification**
  - OTP-based signup flow
  - Validations for Pakistani numbers and common edge cases
- 🗂️ **Auction Categories**
  - Browse and filter items by category
  - Placeholder listings for testing
- 👥 **User Management**
  - Register, login, logout
  - Firestore integration for storing user data
- 💌 **OTP Workflow**
  - Send, resend, and verify OTPs
  - Handling incorrect/malformed entries and expired OTPs
- ⚠️ **Robust Validation**
  - Form field checks, input sanitization, error messaging

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: Firebase Functions (optional expansion)
- **Database**: Firebase Firestore
- **Authentication**: Firebase Auth (with reCAPTCHA + OTP)
- **Deployment**: Firebase Hosting / GitHub Pages (dev mode)

---

## 🚀 Getting Started

1. **Clone the repo:**

   ```bash
   git clone https://github.com/yourusername/gots-auction-site.git
   cd gots-auction-site
