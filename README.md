

The SalonApp is a comprehensive iOS application built with SwiftUI for connecting clients with multiple types of beauty professionals, including nail artists, hair stylists, massage therapists, and spa specialists. Provides a complete ecosystem for clients, professionals, and administrators.

---


## 📱 Overview

SalonApp is a full-featured beauty and wellness marketplace that allows users to **discover, book, and interact with a wide range of beauty professionals**. The app combines professional discovery, client booking, e-commerce, business analytics, and communication tools into a single, beautifully designed iOS app.

Users can first **choose a type of professional** (nail, hair, massage, spa, makeup, wellness) and then access **personalized service menus, portfolios, booking calendars, and e-commerce options**. The app supports multiple user roles, customizable UI themes, and real-time features powered by Supabase.

---

## ✨ Key Features

### 🎯 Client Features

* **Professional Selection** - Choose from nail artists, hair stylists, massage therapists, makeup artists, and other beauty professionals
* **Online Booking System** - Calendar and list views with 60-day booking window per professional
* **Service Menu** - Browse services with pricing, duration, and descriptions
* **Technician Portfolios** - View professional profiles, expertise, and work galleries
* **Product Shop** - Purchase products and supplies related to the selected professional
* **Reward & Loyalty System** - Earn points for bookings and redeem rewards
* **Waitlist** - Join waitlists for preferred time slots
* **Photo Upload** - Guided photo capture for face, hair, nails, body, or other relevant areas
* **Multiple UI Themes** - Beauty Card, Feed, Sidebar, and Modern layouts
* **Dark/Light Mode** - System-aware theme customization
* **AI Chatbot** - Interactive assistant with multiple personality modes

### 👨‍💼 Professional Features

* **Profile & Service Management** - Create professional profile, upload portfolio, manage offered services
* **Schedule Management** - View and manage appointments
* **Earnings Projection** - Track commissions and earnings
* **Statistics Dashboard** - View performance metrics
* **Availability Management** - Set working hours and unavailable dates
* **Real-time Chat** - Private and group messaging with admins and clients
* **Client History** - Access client booking history and preferences

### 👑 Admin Features

* **Complete Dashboard** - Overview of bookings, revenue, and operations
* **Professional Management** - Approve and manage professionals across different categories
* **Service Management** - Add, edit, and configure services for each professional type
* **Finance Hub** - Payroll management, cashflow coach, and financial analytics
* **AI Search** - Intelligent keyword and advanced search across professionals and services
* **Notification System** - Alerts for service/professional mismatches and admin updates
* **Statistics & Analytics** - Comprehensive business insights
* **Theme Customization** - Create and manage custom UI themes
* **Widget Management** - Configure dashboard widgets for different roles
* **Mass Appointment Insertion** - Bulk import appointments via OCR/document parsing
* **Demo Mode** - Simulate appointments for testing

### 💰 Finance Module

* **Payroll Management** - Hourly, commission, hybrid compensation models
* **Cashflow Coach** - AI-powered 30-day cashflow forecasting
* **Payment Settings** - Stripe, PayPal, bank transfer integration
* **Expense Tracking** - Monitor expenses per professional type
* **Revenue Analytics** - Track income and projections

### 💬 Communication

* **Real-time Chat** - Private and group messaging for staff and clients
* **AI Chatbot** - Multiple personality modes (Daisy, Granny, Karen, Max, etc.)
* **Push Notifications** - Appointment reminders, promotions, and updates
* **Email Integration** - Automated email notifications

### 🎨 Customization

* **Multiple UI Layouts** - Beauty Card, Feed, Sidebar, Modern, Floating Panel
* **Theme System** - Custom colors, fonts, and styling
* **Logo Management** - Theme-specific logo customization
* **Translation Support** - English and Greek (extensible to more languages)
* **Currency Support** - Multi-currency support with EUR default

---

## 🏗️ Architecture

### Tech Stack

* **Language**: Swift 5.9+
* **UI Framework**: SwiftUI
* **Backend**: Supabase (PostgreSQL, Realtime, Storage, Auth)
* **Authentication**: Email, Google OAuth, Facebook OAuth
* **AI Integration**: OpenAI API (configurable)
* **Storage**: Hybrid (Supabase + UserDefaults for caching)

### Key Components

* **AuthenticationManager** - Handles user authentication and OAuth
* **BookingManager** - Manages appointments and availability per professional type
* **ProductManager** - E-commerce product management
* **ChatManager** - Real-time messaging system
* **ChatbotManager** - AI chatbot integration
* **FinanceCloudService** - Financial data synchronization
* **ThemeManager** - Theme and UI customization
* **PermissionManager** - Role-based access control

---

## 👥 User Roles

The app supports multiple user roles with different permissions:

* **Guest** - Limited access, can browse and book
* **User/Member** - Full client features, can select professional type
* **Professional** - Profile, services, portfolio, and schedule management
* **Admin** - Full system access
* **Manager** - Administrative access with limited permissions
* **Front Desk** - Reception and booking management
* **Finance** - Financial data access
* **Marketing** - Promotional content management
* **Support** - Customer support tools
* **Supplier** - Product supplier access

---

## 🚀 Booking Flow (Client Journey)

1. **Select Professional Type** - Nail, hair, massage, makeup, spa, or wellness specialist
2. **Choose a Professional** - Browse portfolios, ratings, and availability
3. **Select Services** - Choose one or multiple services offered by the professional
4. **Confirm Appointment** - Choose date/time and optionally join a waitlist
5. **Payment & Rewards** - Pay online and earn loyalty points
6. **Photo Upload** - Optional guided photo upload if required for service
7. **Notifications** - Receive reminders, updates, and promotions

---

## 📚 Documentation

* [Supabase Setup Guide](SETUP_SUPABASE.md)
* [Chat Setup Guide](CHAT_SETUP.md)
* [Finance Module Specification](FINANCE_MODULE_SPEC.md)
* [Guided Photo Capture](GUIDED_PHOTO_CAPTURE.md)
* [Implementation Status](IMPLEMENTATION_STATUS.md)
* [App Enhancement Recommendations](APP_ENHANCEMENT_RECOMMENDATIONS.md)

---

## 🔒 Security

* **API Keys**: No hardcoded keys - configured by admin in settings
* **Authentication**: Secure OAuth and email authentication via Supabase
* **Data Privacy**: Row Level Security (RLS) policies in Supabase
* **User Data**: Encrypted storage with proper access controls

---

## 📞 Support

For support, email [phktistakis@gmail.com](mailto:phktistakis@gmail.com) or open an issue in this repository.

---

**Made with ❤️ for beauty professionals and clients everywhere**

---
