# Volunteer-Application

A full-stack web application for managing volunteer activities, events, and reporting for organizations. The app supports volunteer sign-up/sign-in, event management, participation tracking, notifications, and exportable reports.

---

## Features

- **User Authentication:** Secure sign-up and sign-in for volunteers and admins
- **Event Management:** Create, view, and manage events
- **Volunteer Matching:** Assign volunteers to events based on preferences and availability
- **Participation Tracking:** Track events attended and points earned by volunteers
- **Notifications:** Automated notifications for event updates and confirmations
- **Reports:** Export volunteer participation reports as CSV or PDF
- **Admin Dashboard:** Metrics, management, and overview tools for administrators

---

## Tech Stack

- **Frontend:** Next.js, React, TypeScript, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** Supabase (PostgreSQL)
- **Testing:** Jest, React Testing Library
- **Reporting:** jsPDF, PapaParse

---

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- npm or yarn
- Supabase account and project

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/Volunteer-Application.git
    cd Volunteer-Application
    ```

2. **Install dependencies:**
    ```bash
    cd client
    npm install
    cd ../server
    npm install
    ```

3. **Set up environment variables:**
    - Copy `.env.example` to `.env` in both `client` and `server` folders and fill in your Supabase and other API keys.

4. **Start the development servers:**
    - _Frontend:_
        ```bash
        cd client
        npm run dev
        ```
    - _Backend:_
        ```bash
        cd server
        npm start
        ```

---

## Usage

- **Sign up** as a volunteer or log in as an admin to access the dashboard.
- **Admins** can create events, view metrics, assign volunteers, and export participation reports.
- **Volunteers** can view upcoming events, sign up, track their participation, and receive notifications.

---

## Testing

Run tests using:

```bash
npm test

```
---
### Contributors
Godswill Effi

Omoyeni Kuku

Isaias Gonzales

Jason Vu
