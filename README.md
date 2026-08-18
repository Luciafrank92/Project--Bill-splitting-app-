# FairShare Bill Splitter

A complete, responsive bill-splitting web application built with HTML, CSS, JavaScript and Node.js/Express.

## Features

- Equal bill splitting
- Custom weighted amounts
- Add and remove people
- Nigerian Naira (₦) currency formatting
- Automatic calculation
- Saved bill history
- Delete individual bills
- Clear all saved bills
- Responsive desktop and mobile interface
- Simple Express backend with JSON file persistence
- No database setup required

## Requirements

- Node.js 18 or newer
- A modern web browser

## How to run

1. Extract the project folder.
2. Open a terminal inside the project folder.
3. Run:

```bash
npm install
npm start
```

4. Open:

http://localhost:3000

## Project structure

```text
fairshare-bill-splitter/
├── data/
│   └── bills.json
├── public/
│   ├── index.html
│   ├── styles.css
│   └── app.js
├── package.json
├── server.js
└── README.md
```

## Project description

FairShare solves the common problem of dividing shared expenses. Users enter a bill name, total amount and participants, then choose between an equal split or custom amounts. Calculated bills can be retained in the saved-bills section and deleted when no longer needed.

## Academic project note

This project is intentionally self-contained and ready to run after installing its single server dependency. The interface is responsive and the application includes both frontend and backend functionality.
