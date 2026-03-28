# 🍽️ Gennit — Safe food parties for everyone!

**Gennit** is an iOS application designed to take the stress out of organizing group meals, parties, and events. It provides a seamless way for hosts to collect and manage the food allergies and dietary restrictions of their guests, ensuring everyone can eat safely and enjoyably.

---

## 🌟 Overview

Planning a dinner but worried about who's allergic to what? **Gennit** bridges the communication gap between hosts and guests. 

- **Hosts** create an event and share a simple code.
- **Guests** join the event and privately log their intolerances.
- **Everyone** eats safely.

---

## ✨ Key Features

- **📍 Simple Event Management**: Create events with a name, date, and location in seconds.
- **🔗 Seamless Joining**: Guests can join via a unique 6-digit code or a direct "smart link" that opens the app and joins the event automatically.
- **🛡️ Real-time Notifications**: Hosts receive push notifications the moment a guest adds or updates an intolerance.
- **🤖 AI-Powered Suggestions (Premium)**: Get intelligent meal suggestions and ingredient analysis tailored to the specific list of allergies in your event.
- **🗺️ Navigation Integration**: One-tap directions to event locations using Apple Maps or your preferred navigation app.
- **☁️ CloudKit Sync**: Your events and data are synced across all your Apple devices securely.
- **🌓 Adaptive Design**: Full support for Dark Mode with a custom design system focused on readability and accessibility.

---

## 🛠️ How it Works

### 1. Create
The host starts a "New Event" and fills in the basic details. Gennit generates a unique 6-character access code.

### 2. Share
The host shares the code or a deep link with the guest list via iMessage, WhatsApp, or any other platform.

### 3. Log
Guests enter the code, select from a list of common allergens (Gluten, Lactose, Nuts, etc.), or type their own specific requirements.

### 4. Plan
The host sees a consolidated list of all dietary requirements, allowing them to plan the menu with confidence.

---

## 💻 Technology Stack

- **Language**: Swift 6.0+
- **Framework**: SwiftUI
- **Persistence & Sync**: Apple CloudKit
- **Deep Linking**: Custom URL Schemes (`gennit://`)
- **Payments**: StoreKit 2 (Subscription-based model)
- **Architecture**: Modern MVVM with Manager-pattern for services (CloudKit, Subscriptions, DeepLinks)

---

## 🔒 Privacy & Data

Gennit is built with privacy at its core:
- **No Account Required**: Uses your existing iCloud account via CloudKit; no third-party registrations.
- **Data Ownership**: Users can delete their own events and remove their logged intolerances at any time.
- **Minimal Tracking**: We only store what is strictly necessary for the app to function.

---

## ⚠️ Disclaimer

**AI & Accuracy**: While Gennit uses advanced models to provide food suggestions, AI can make mistakes. Always double-check ingredient labels and consult directly with guests regarding severe allergies.

---

*Note: This repository contains the documentation and project structure for Gennit. The source code is private and maintained by the developer.*
