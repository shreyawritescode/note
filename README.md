# Note Keeper App

A **React-based note-taking application** inspired by Google Keep. Built with React 16 and TypeScript, this app lets users create, view, and delete notes in a clean card-based interface.

## Features

- Add new notes with a title and content
- Display notes as individual cards
- Delete notes with a single click
- Clean, minimal UI

## Tech Stack

| Technology | Version | Purpose |
|---|---|---|
| React | 16.8.6 | UI framework |
| React DOM | 16.8.6 | DOM rendering |
| TypeScript | 3.3.3 | Type checking |
| React Scripts | 3.2.0 | Build tooling (CRA) |

## Project Structure

```
note/
├── public/            # Static assets
├── src/               # React source files
│   ├── App.js         # Root component
│   ├── components/    # Note, Header, Footer, etc.
│   └── index.js       # Entry point
├── package.json
└── README.md
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/shreyawritescode/note.git
   cd note
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```
4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Available Scripts

| Script | Description |
|---|---|
| `npm start` | Runs app in development mode |
| `npm test` | Launches the test runner |
| `npm run build` | Builds the app for production |

---

*A hands-on React project for learning component-based architecture and state management.*
