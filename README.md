# YouTube 2022 React Admin

Create React App dashboard with MUI widgets, charts, tables, and a dark-mode context.

## About

This is an admin dashboard front end with multiple screens, reusable widgets, and chart-heavy analytics components. The code is a good portfolio sample for component composition, layout systems, and data-table driven interfaces.

## Key Features

- Dashboard, list, single-item, login, and create forms
- Material UI layout and component composition
- Charts and progress indicators
- Dark mode state management

## Architecture

- `src/index.js` bootstraps the React app
- `src/App.js` wires the dashboard routes and layout
- `src/components/` contains the dashboard widgets and panels
- `src/context/` stores the dark-mode reducer and provider

## Tech Stack

- React 17
- Create React App
- Material UI
- Recharts
- Sass

## Prerequisites

- Node.js

## Installation

```bash
npm install
```

## Configuration

- No env vars are required by the current code

## How to Run

```bash
npm start
npm run build
npm test
```

## Example Usage

- Open the app and navigate through the dashboard, list, and single-item screens

## Project Structure

- `src/pages/` - top-level views
- `src/components/` - dashboard widgets
- `src/context/` - theme and dark-mode state
- `src/style/` - Sass theme styles

## Current Status

Looks like a complete UI demo that is ready for portfolio review.

## Limitations

- No backend is present in this repo
- Create React App dependencies are older than current React toolchains

## License

No explicit license file was found.
