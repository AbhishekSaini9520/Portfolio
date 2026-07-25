# Abhishek Saini - Developer Portfolio

A modern, responsive portfolio website built with React, Tailwind CSS, and Vite. It showcases my experience, education, projects, technical skills, and coding profiles in a clean dark-themed interface.

## Live Demo

- [Portfolio Website](https://portpolio-xi-seven.vercel.app/)

## Highlights

- Responsive layout for desktop, tablet, and mobile
- Dark UI with gradient accents and smooth section transitions
- Typing effect and interactive profile presentation
- Parallax tilt cards for a more dynamic visual feel
- Experience and education sections powered by structured data
- Projects section with modal-style project details
- Contact form connected to EmailJS
- Social links for GitHub, LinkedIn, LeetCode, Codeforces, and CodeChef

## Tech Stack

- React
- Tailwind CSS
- Vite
- React Router DOM
- React Icons
- React Parallax Tilt
- React Typing Effect
- React Toastify
- EmailJS

## Project Structure

```text
src/
├── assets/
├── components/
│   ├── About/
│   ├── Contact/
│   ├── Education/
│   ├── Experience/
│   ├── Footer/
│   ├── Navbar/
│   ├── Skills/
│   └── Work/
├── constants.js
├── App.jsx
├── main.jsx
└── index.css
```

## Data Source

The portfolio content is centralized in [src/constants.js](src/constants.js), including:

- Skills grouped by frontend, backend, languages, tools, and core concepts
- Experience entries such as CodeCanvas AI, Code Hub, ICSCIS-2026, and Yuga Yatra Retail
- Education entries for CSJMU and Hilton Convent Senior Secondary School
- Projects including CodeCanvas AI, CodeHub, and Simple Weather Card
- Coding profile stats for LeetCode, CodeChef, and Codeforces

## Projects

| Project | Description | Tech Stack |
| --- | --- | --- |
| CodeCanvas AI | AI-powered DSA learning platform with progress tracking, analytics, and interactive support | React.js, Node.js, Express.js, PostgreSQL, Prisma ORM, Tailwind CSS, JWT |
| CodeHub | Online coding platform with real-time execution, judge integration, leaderboards, and discussions | React.js, Node.js, Express.js, MongoDB, Redis, Socket.IO, Judge0 API, JWT, Google OAuth |
| Simple Weather Card | Weather dashboard for displaying real-time weather data | HTML, CSS, JavaScript, Weather API |

## Coding Profiles

| Platform | Rating | Problems Solved |
| --- | --- | --- |
| LeetCode | 1734 | 500+ |
| CodeChef | 1630 (3-star) | 200+ |
| Codeforces | 1249 (Pupil) | 400+ |

## Connect With Me

- GitHub: [AbhishekSaini9520](https://github.com/AbhishekSaini9520)
- LinkedIn: [Abhishek Saini](https://www.linkedin.com/in/abhishek-saini-8b7561309/)
- LeetCode: [AbhishekSaini2149520](https://leetcode.com/u/AbhishekSaini2149520/)
- Codeforces: [AbhishekSaini95](https://codeforces.com/profile/AbhishekSaini95)
- CodeChef: [abhishek_cpp](https://www.codechef.com/users/abhishek_cpp)

## Environment Setup

The contact form uses EmailJS. Add these variables to a local `.env` file:

```bash
VITE_EMAILJS_SERVICE_ID=your_service_id
VITE_EMAILJS_TEMPLATE_ID=your_template_id
VITE_EMAILJS_PUBLIC_KEY=your_public_key
```

## Getting Started

```bash
git clone https://github.com/AbhishekSaini9520/Portfolio.git
cd Portfolio
npm install
npm run dev
```

## Build

```bash
npm run build
```

## License

This project is open source and available under the MIT License.

Built with care by Abhishek Saini.
