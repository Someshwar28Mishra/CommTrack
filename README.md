# Comm Track

Comm Track is a React-based Calendar Application designed to help businesses maintain strong professional relationships by tracking and managing communication with companies. The application ensures timely follow-ups, provides a centralized platform for logging interactions, and enables efficient communication management.

## Features

### Admin Module
This module allows administrators to configure and manage company interactions.
- **Company Management**:
  - Add, edit, and delete companies with details such as name, location, LinkedIn profile, emails, phone numbers, comments, and communication periodicity.
- **Communication Method Management**:
  - Define communication methods, including LinkedIn Post, LinkedIn Message, Email, Phone Call, and Other.
  - Set communication sequences and mark methods as mandatory.

### User Module
This module provides an intuitive interface for users to manage communication tasks.
- **Dashboard**:
  - View companies in a grid format with recent communication history and next scheduled communication.
  - Color-coded highlights for overdue (red) and due today (yellow) communications.
- **Interactive Features**:
  - Tooltips for additional communication notes.
- **Communication Action**:
  - Log new communications with type, date, and notes.
  - Reset overdue or due highlights upon submission.
- **Notifications**:
  - View overdue and today's due communications in a dedicated section.
  - Badge notification count for overdue/due communications.
- **Calendar View**:
  - Visualize past and upcoming communications.

### Reporting and Analytics Module (Optional)
- **Communication Frequency Report**:
  - Visual representation of communication methods over a selected timeframe.
- **Engagement Effectiveness Dashboard**:
  - Insights into the effectiveness of different communication methods.
- **Overdue Communication Trends**:
  - Track overdue communications over time.
- **Downloadable Reports**:
  - Export reports in PDF or CSV format.
- **Real-Time Activity Log**:
  - Live feed of all communication activities.

## Installation

Clone the repository and navigate to the project directory:
```sh
git clone <repository-url>
cd comm-track
```

Install dependencies:
```sh
npm install
```

Start the development server:
```sh
npm start
```

## Deployment
The project is live at:
[Comm Track](https://commtracker.netlify.app/)

## Technologies Used
- **React** – Frontend framework
- **CSS** – Styling and UI components
- **React Calendar** – Interactive calendar view
- **React Notifications** – Alerts and updates
- **Charts.js/D3.js** – Data visualization (optional analytics module)



