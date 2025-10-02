### README.md


```md
# IILM Mentor-Mentee Frontend


This is a React + Vite frontend scaffold for the Mentor-Mentee application for IILM University, Gurgaon.


## Features
- Registration & Login (mentor & mentee roles)
- Dashboard with upcoming meetings and resources
- Profile management (edit skills, availability)
- Mentor search with filtering
- Chat UI (mock) ready for real-time integration
- Scheduler (calendar) for booking meetings
- Resource library to upload/share resources
- Responsive design and accessibility considerations
- State management via Context API
- Routing with React Router


## Tech stack
- React 18
- Vite
- Tailwind CSS
- React Router
- Axios (for API calls)
- react-calendar


## Setup (local)


1. Ensure Node.js 18+ is installed.
2. Clone the repository (or copy files into a folder).
3. In the project folder, run:


```bash
npm install
npm run dev
```


4. Open `http://localhost:5173` (Vite default) in the browser.


## Notes & Next steps
- Authentication, chat, and persistent data are mocked locally. Integrate the backend (Node/Django) with endpoints to: `/api/auth`, `/api/users`, `/api/mentors`, `/api/meetings`, `/api/resources`.
- For real-time chat: use Socket.io (Node) or Firebase Realtime Database.
- For video calls: integrate WebRTC, Twilio, or Agora.
- Improve accessibility by adding ARIA labels, keyboard navigation tests, and contrast checks.