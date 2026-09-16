# 🏠 PG CONNECT

A location-based platform that simplifies the search for Paying Guest (PG) accommodations and hostels — built for students and working professionals, local and non-local alike, who need a fast, trustworthy way to find a place to stay.

---

## 📌 Overview

Finding a reliable PG or hostel is often a frustrating, word-of-mouth process — scattered listings, unverified reviews, and no easy way to filter by what actually matters. PG CONNECT solves this with a centralized, location-based directory of PG and hostel listings, each with pricing, owner contact details, amenities, and property images, paired with a filtering system and a review model designed specifically to keep feedback honest.

---

## 🔑 Key Features

- **Location-based listings** — browse PG and hostel accommodations by area, making the search relevant to where the user actually needs to stay
- **Detailed property listings** — each entry includes pricing, owner contact information, available amenities, and images
- **Verified review system** — ratings and feedback can only be submitted by current residents of a property, ensuring reviews are authentic and trustworthy rather than open to anyone
- **Advanced filtering** — narrow results by price range, room-sharing options (single/double/triple occupancy), AC availability, and other preferences
- **Full-stack architecture** — from database design through a responsive, user-facing interface

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript, React
- **Backend:** Node.js
- **Database:** Supabase (PostgreSQL-based SQL database)

---

## 🧱 System Design

Before development, the core entities of the platform — listings, owners, residents, and reviews — along with their relationships and key workflows (such as submitting a verified review or filtering search results) were carefully mapped out to ensure a clean, maintainable structure. This upfront design work shaped how the database schema, review logic, and filtering system were ultimately implemented.

---

## 🎯 What This Project Demonstrates

- Translating a real, everyday problem (unreliable PG/hostel search) into a structured software solution
- Designing a review system with built-in integrity constraints (resident-only reviews) rather than an open, unmoderated model
- Building backend query logic to support multi-criteria filtering (price, occupancy, amenities) efficiently
- Planning system structure and key workflows before writing code, for a cleaner and more maintainable build
- End-to-end full-stack development — from database schema design to a working, responsive user interface

---

## 👥 Who It's For

- Students relocating to a new city for college, needing verified, filterable housing options
- Working professionals looking for short- or long-term PG accommodation
- Property owners seeking a straightforward way to list and manage their PG/hostel details
