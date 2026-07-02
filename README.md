# NYERI POLICE AND COMMUNITY CHAPEL

A comprehensive web platform for the Nyeri Police and Community Chapel providing spiritual resources, community announcements, and administrative management.

## 🌟 Features

### User Features
- **📖 Bible App** - Good News Bible with search functionality
- **🎵 Tenzi App** - Hymns and worship songs collection
- **📺 Sermon Animation** - Live/featured sermon display at home
- **💬 Announcements** - Daily community messages and updates
- **🙏 Prayer Requests** - Submit prayer requests (public feature)
- **📅 Events Calendar** - View upcoming church events
- **✉️ Today's Bible Verse** - Daily scripture inspiration
- **📞 Help Centre** - Support and contact information

### Admin Features
- **👤 Admin Dashboard** - Complete management panel
- **📢 Message Management** - Create weekly announcements (Mon-Sun cycle)
- **📅 Event Management** - Create, edit, delete events
- **📊 Statistics Dashboard** - View total members, attendance
- **💰 Offering Management** - Track and manage church offerings
- **📧 Announcement Scheduling** - Auto-clear old messages
- **👥 Member Management** - View and manage church members
- **🛠️ Settings & Configuration** - Church settings and branding

## 🏗️ Project Structure

```
├── index.html                 (Home page)
├── bible.html                 (Bible app)
├── tenzi.html                 (Hymns/Tenzi app)
├── events.html                (Events calendar)
├── prayer-requests.html       (Prayer request form)
├── announcements.html         (View announcements)
├── help.html                  (Help centre)
├── admin-login.html           (Admin authentication)
├── admin-dashboard.html       (Admin control panel)
├── manifest.json              (PWA manifest)
├── service-worker.js          (Offline support)
│
├── css/
│   ├── style.css              (Global styles)
│   ├── home.css               (Home page styles)
│   ├── admin.css              (Admin panel styles)
│   ├── responsive.css         (Mobile responsive)
│   └── animations.css         (Animations)
│
├── js/
│   ├── app.js                 (Main app initialization)
│   ├── firebase.js            (Firebase config)
│   ├── auth.js                (Authentication)
│   ├── home.js                (Home page logic)
│   ├── bible.js               (Bible app)
│   ├── tenzi.js               (Tenzi app)
│   ├── announcements.js       (Announcements management)
│   ├── events.js              (Events management)
│   ├── prayers.js             (Prayer requests)
│   ├── admin.js               (Admin functions)
│   ├── offerings.js           (Offering management)
│   └── service-worker-register.js
│
└── assets/
    ├── images/
    ├── icons/
    └── logo/
```

## 🚀 Getting Started

1. Clone the repository
2. Configure Firebase credentials in `js/firebase.js`
3. Set up admin credentials
4. Open `index.html` in a web browser

## 📋 Firebase Collections

- `users` - Church members and admin accounts
- `announcements` - Weekly announcements (auto-cleared)
- `events` - Upcoming church events
- `prayers` - Prayer requests from members
- `offerings` - Offering records and totals
- `bible-verses` - Daily Bible verses
- `sermons` - Sermon information and videos
- `settings` - Church configuration settings

## 🔐 Admin Credentials

Contact administrator for login credentials at: **nyeripolice@gmail.com**

## 📱 Features by Page

### Home (index.html)
- Sermon animation/featured content
- Quick access to Bible and Tenzi
- Today's Bible verse
- Recent announcements
- Prayer request button
- Events preview

### Admin Dashboard
- Weekly announcement management (Mon-Sun cycle)
- Event creation and management
- Prayer request review
- Offering tracking and statistics
- Member management
- Settings configuration

## 🛠️ Technologies

- HTML5
- CSS3
- JavaScript (ES6+)
- Firebase (Realtime Database & Firestore)
- Service Workers (PWA)

## 📞 Contact

**Email:** nyeripolice@gmail.com

---

© 2026 Nyeri Police and Community Chapel. All rights reserved.
