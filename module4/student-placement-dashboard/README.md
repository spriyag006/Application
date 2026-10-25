# Student Placement Dashboard

This project was bootstrapped with Create React App.


**GitHub Repository:** https://github.com/spriyag006/shebuilds-fsd-training

## Tech Stack

- React 19
- JavaScript
- HTML5
- CSS3
- React Router (if used)
- React Testing Library
- Jest
- Render (Static Site Deployment)

## Features

- View student placement information.
- Search and filter student records (if implemented).
- Display placement statistics and summaries (if implemented).
- Manage student placement details.
- Responsive dashboard interface (if implemented).

## Getting Started

### Prerequisites

- Node.js 18 or later
- npm
- Git

### Installation

Clone the repository:

```bash
git clone https://github.com/spriyag006/shebuilds-fsd-training.git
```

Navigate to the project directory:

```bash
cd shebuilds-fsd-training/module4/student-placement-dashboard
```

Install dependencies:

```bash
npm install
```

### Run Locally

Start the development server:

```bash
npm start
```

Open http://localhost:3000 in your browser.

The application automatically reloads when you make changes to the source code.

## Available Scripts

| Command | Description |
|---|---|
| `npm start` | Starts the development server |
| `npm test` | Runs the test suite |
| `npm run build` | Creates an optimized production build |
| `npm run eject` | Exposes the underlying configuration (one-way operation) |

## Project Structure

```text
student-placement-dashboard/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   ├── App.js
│   ├── App.css
│   └── index.js
├── package.json
└── README.md
```

*Note: The folder and file structure may vary depending on your implementation.*

## Deployment on Render

This project can be deployed on Render as a **Static Site**.

### Build Settings

| Setting | Value |
|---|---|
| Service Type | Static Site |
| Root Directory | `module4/student-placement-dashboard` |
| Build Command | `npm install && npm run build` |
| Publish Directory | `build` |

If the application uses React Router, configure a rewrite rule in Render:

- **Source:** `/*`
- **Destination:** `/index.html`
- **Action:** Rewrite

After successful deployment, add the generated Render URL to the Live Demo section above.

## Author

**Sangeetha Priya**

GitHub: https://github.com/spriyag006

---

Developed as part of the SheBuilds Full Stack Development Training – Module 4.
