# 🏷️ Intel Sustainability Summit – Check-In App

A lightweight web application designed to simulate attendee check-ins for a sustainability-focused event.  
The app tracks attendance in real time, visualizes team participation, and provides immediate feedback through a clean, accessible interface.

---

## ✨ Overview

This application models a real-world event check-in system where attendees are assigned to teams and tracked toward a shared attendance goal.

Users can:
- Check in attendees by name and team
- View total attendance progress toward a defined goal
- Track participation across multiple teams
- Expand and filter attendee lists dynamically
- Receive real-time feedback and milestone celebrations

The focus of this project is **state management**, **data persistence**, and **user-centered interface design**.

---

## 🚀 Key Features

- **Real-Time Attendance Tracking**
  - Tracks total attendee count against a configurable goal
  - Visual progress bar updates dynamically as check-ins occur

- **Team-Based Analytics**
  - Attendees are grouped into teams with individual counters
  - Leading team is highlighted once the attendance goal is reached
  - Supports filtered views by team or overall attendance

- **Persistent Client-Side State**
  - Attendance data is stored using browser `localStorage`
  - State is restored on page reload without server dependency

- **Interactive & Accessible UI**
  - Keyboard-accessible controls and ARIA attributes
  - Expandable attendee lists with clear focus states
  - Live region updates for greetings and status messages

- **Event-Ready User Experience**
  - Personalized greetings on successful check-in
  - Celebration banner triggered at attendance milestones
  - Responsive layout optimized for desktop and mobile use

---

## 🛠️ Technical Stack

- **Frontend:** HTML5, CSS3, JavaScript (ES6)
- **State Management:** In-memory state with localStorage persistence
- **UI Patterns:** Progress indicators, expandable lists, modal-style feedback
- **Accessibility:** Semantic HTML, ARIA roles, keyboard navigation

---

## 🧩 Architecture Notes

- Application state (attendees, totals, teams) is managed centrally in JavaScript.
- UI rendering functions update counts, progress, and lists based on state changes.
- Event handlers coordinate form submission, filtering, and list expansion.
- Data is sanitized before rendering to prevent unsafe DOM injection.

---

## ⚠️ Disclaimer

This project is a **demonstration application built for learning purposes**.  
It is **not an official Intel product or event system**.

---

## 👤 Author

**Shivraj Jadeja**  
Software Engineering Apprentice – Global Career Accelerator
