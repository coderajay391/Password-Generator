# Password Generator — Documentation

## Overview

Password Generator is a client-side web app (React + TypeScript) that creates strong, random passwords using configurable character sets and lets you copy the result instantly.

## Features

- Password generation with options like:
  - Length
  - Include uppercase letters
  - Include lowercase letters
  - Include numbers
  - Include special characters
- One-click copy to clipboard
- Preview the generated password so it’s ready to use immediately

## How to Use

1. Select the desired options (length and character types).
2. Generate the password (button/interaction in the UI).
3. Copy the password using the copy control.

## Tech Stack

- React + TypeScript (Vite)
- TailwindCSS

## Running Locally

```bash
npm install
npm run dev
```

App URL:

- http://localhost:3000

## Build

```bash
npm run build
npm run preview
```

## Notes / Considerations

- Since password generation happens in the browser, no password is sent to any server.
- For strongest results, enable multiple character sets and use sufficient length.
