# SRM Companion

> Your academic life, organized — attendance tracking, study materials, timetables, and more in one place.

---

## What It Does

SRM Companion is a student portal built for SRM University students who want to spend less time hunting for information and more time studying. It pulls together the things you check daily — attendance, materials, announcements, timetables — into a single, fast interface.

---

## Core Features

### Attendance Tracking
Never get caught off-guard by low attendance again.

- Live percentage display per course
- Automatic warnings when attendance drops below **75%**
- Calculates exactly how many classes you need to attend to recover
- Visual progress bars for a quick read at a glance

### Study Materials
A shared repository for everything your batch needs.

| Type | Description |
|---|---|
| Notes | Complete course notes |
| PYQ | Previous Year Questions with solutions |
| Assignments | Course assignments |
| Reference Books | Additional reading materials |
| Lab Manuals | Lab experiment guides |

**Browse & Search**
- Search by title, subject, or keyword
- Filter by subject (CSE, Data Structures, OS, and more) or material type
- Star ratings (1–5) and download counts help you find the most useful resources

**Upload**
- Add a title, description, subject, and type
- Attach PDF/DOC/DOCX files up to 10 MB
- Optional tags for better discoverability
- Real-time form validation; your upload appears instantly

**Delete**
- Trash icon on every card
- Confirmation dialog before anything is removed

### Timetable
Your weekly schedule at a glance, updated to reflect the current semester.

### Announcements
A live feed of important notices with a full history view.

---

## Additional Modules

| Module | Purpose |
|---|---|
| Lost & Found | Report or find items misplaced on campus |
| Clubs & Societies | Browse and manage your club memberships |
| Transport Info | Bus routes and schedules |
| Marketplace | Buy and sell items with fellow students |
| Placements | Job listings, drives, and career resources |
| Important Links | Quick access to university portals and tools |
| Peer Help Forum | Ask questions, share knowledge, learn together |
| Feedback | Submit suggestions or complaints |
| Profile | Manage your personal information |

---

## Tech Stack

| Layer | Technology |
|---|---|
| UI Framework | React 18 |
| Routing | React Router v6 |
| Styling | Tailwind CSS v3 |
| Icons | Lucide React |

---

## Getting Started

```bash
# Clone the repository
git clone https://github.com/your-username/srm-companion.git
cd srm-companion

# Install dependencies
npm install

# Start the development server
npm run dev
```

Open `http://localhost:5173` in your browser.

---

## Project Structure

```
srm-companion/
├── src/
│   ├── components/      # Reusable UI components
│   ├── pages/           # Route-level page components
│   ├── assets/          # Static files
│   └── main.jsx         # App entry point
├── public/
└── package.json
```

---

## Contributing

Pull requests are welcome. For significant changes, open an issue first to discuss what you'd like to change.

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## License

MIT
