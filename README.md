# Campus Event & Club Hub

A responsive, modern university event discovery and student club management platform built using pure **HTML5, CSS3, Vanilla JavaScript, and LocalStorage**.

---

## 📌 Project Overview

**Campus Event & Club Hub** is a software engineering student web application created to help university students discover upcoming campus events, explore student clubs, register for activities, and manage their personal schedules.

Designed with a clean, professional university design system, modern card components, responsive drawer menus, client-side validation, and instant LocalStorage state management.

---

## ✨ Features

- **Home Portal:** Hero banner, weekly highlights preview, featured event cards, popular student club grid, feature highlights, and real-time statistics counters.
- **Event Discovery (`events.html`):**
  - Dynamic rendering of campus events.
  - Category filters (*Technical, Cultural, Sports, Workshop, Competition*).
  - Instant live keyword search.
  - Date filtering and clear filters button.
  - "No events found" empty state feedback.
- **Detailed Event Page (`event-details.html`):**
  - Dynamic URL parameter routing (`?id=1`).
  - Comprehensive schedule timeline (Registration, Opening Ceremony, Keynote, Workshop, Closing).
  - Real-time remaining seat counter.
  - Eligibility guidelines and direct registration links.
- **Club Directory (`clubs.html`):**
  - Search and filter student organizations (*Technical, Cultural, Sports, Arts, Entrepreneurship*).
  - Instant **Join Club / Joined ✓** state toggles saved to LocalStorage.
- **Detailed Club Page (`club-details.html`):**
  - Club mission statement, meeting day, venue, and faculty coordinator details.
  - Weekly programs and key member benefits.
- **Event Registration Form (`register.html`):**
  - Form validation (Full Name, University ID, Valid Email, Phone Number, Department, Year, Event Selection).
  - Auto pre-selection of events/clubs from query parameters (`?eventId=2`).
  - LocalStorage record storage with unique reference ID generation.
  - Automatic seat count deduction upon registration.
- **Student Dashboard (`dashboard.html`):**
  - Personal student profile header.
  - Quick stat counters (*Registered Events, Upcoming Events, Joined Clubs*).
  - Interactive registered events cards with **Cancel Registration** option.
  - Joined clubs list with **Leave Club** action.
  - Complete registration history data table.

---

## 🛠️ Technologies Used

- **HTML5:** Semantic document structure, accessible form fields, and custom datasets.
- **CSS3:** Custom properties (CSS variables), Flexbox, CSS Grid, smooth transitions, mobile breakpoint media queries, custom badges, and clean typography.
- **Vanilla JavaScript (ES6+):** Dynamic rendering, URL parameter extraction, event delegation, input validation, DOM manipulation, and array filtering.
- **LocalStorage API:** Browser-side persistence for event seat management, registration records, and club membership states without requiring an external backend.

---

## 📁 Project Folder Structure

```
Campus-Event-Club-Hub/
│
├── index.html              # Home Page
├── events.html             # All Events Listing & Filter Page
├── event-details.html      # Individual Event Details & Schedule
├── clubs.html              # Student Clubs Listing Page
├── club-details.html       # Individual Club Details & Mission
├── register.html           # Event & Club Registration Form
├── dashboard.html          # Student Dashboard & History
│
├── css/
│   └── style.css           # Master University Design System & Layouts
│
├── js/
│   ├── script.js           # Core Data, Storage Helpers & Mobile Nav
│   ├── events.js           # Event Search, Filters & Cards
│   ├── clubs.js            # Club Search, Filters & Membership Toggles
│   └── dashboard.js        # Student Dashboard Stats & Reg Cancellations
│
├── images/
│   └── README.md           # Asset documentation
│
└── README.md               # GitHub Project Documentation
```

---

## 🚀 How to Run Locally

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/Campus-Event-Club-Hub.git
   cd Campus-Event-Club-Hub
   ```

2. **Open in VS Code:**
   - Open VS Code.
   - Click `File > Open Folder...` and select `Campus-Event-Club-Hub`.

3. **Launch with Live Server:**
   - Install the **Live Server** extension in VS Code.
   - Right-click on `index.html` and click **"Open with Live Server"**.
   - Or navigate directly to `index.html` in any web browser.

---

## 🔮 Future Enhancements (Backend Roadmap)

This frontend Version 1 is designed to seamlessly transition into a full-stack enterprise web application:

- **Java Backend:** Refactoring logic into Java Servlets / Spring Boot controllers.
- **MySQL Database & JDBC:** Persisting student accounts, registrations, and club memberships in relational database tables.
- **Spring Boot REST APIs:** Exposing endpoints for `/api/events`, `/api/clubs`, and `/api/registrations`.
- **User Authentication:** Implementing Spring Security with JWT or OAuth2 for Student & Faculty login.
- **Admin Dashboard:** Role-based access control for event organizers to post and edit events.
- **Email Notifications:** Automated confirmation emails using JavaMail Sender.

---

## 📄 License & Attribution

Developed as a software engineering student portfolio project for GitHub and resume showcase.
