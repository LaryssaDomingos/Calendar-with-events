# Calendar with Events

A simple, responsive calendar web application built with vanilla JavaScript, HTML, and CSS. The application allows users to navigate between months and years, create and manage events, and keep their events saved locally using `localStorage`.

## Overview

### Purpose

The purpose of this project is to provide a lightweight and easy-to-use calendar for personal projects, prototypes, and everyday event management.

The application is designed to be simple, accessible, and easy to understand, while also providing a solid foundation for future improvements such as recurring events, external storage, notifications, and calendar synchronization.

### Key Design Goals

- Clear and intuitive visual hierarchy
- Responsive layout for different screen sizes
- Minimal dependencies and simple project structure
- Easy-to-understand HTML, CSS, and JavaScript
- Immediate visual feedback when events are created or updated
- Accessible controls and keyboard navigation
- Local data persistence without requiring a database

## Features

- Month and year navigation using Previous and Next controls
- Quick access to the current date using the Today button
- Visual event markers on days that contain scheduled events
- Add Event modal with date and title inputs
- View all events for a selected day
- Edit existing events
- Delete events
- Keyboard shortcuts for faster navigation
- Event persistence using `localStorage`
- Accessible day cells with keyboard support and ARIA labels
- Responsive interface for desktop and smaller screens

## Technologies

This project uses the following technologies:

- HTML5 for the application structure
- CSS3 for styling and responsive layouts
- Vanilla JavaScript for calendar functionality and event management
- `localStorage` for saving events in the browser
- Font Awesome for interface icons
- Google Fonts for typography

No frameworks or build tools are required.

## Installation and Running

### Requirements

The project works in any modern web browser, including:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari

### Quick Start

1. Clone or download the repository.
2. Open the project folder.
3. Open `index.html` in your preferred browser.
4. The calendar will load automatically and begin using `localStorage` to save events.

### Clone the Repository

git clone https://github.com/Mauricegitech/Calendar-with-events.git


Then enter the project directory:

cd Calendar-with-events


No additional installation is required.

### Optional Local Server

Although the project can be opened directly in a browser, you can also run it using a local development server.

For example, if you have Python installed:

python -m http.server


Then open the address provided by the server in your browser.

## Usage

### Adding an Event

1. Click the **Add Event** button.
2. Select the date for the event.
3. Enter an event title.
4. Click **Save**.
5. The selected day will display an event marker.

### Viewing Events

Click on a calendar day to open the events view for that date. All events scheduled for the selected day will be displayed.

### Editing an Event

Open the events for a selected day and click the edit icon next to the event you want to modify.

The event information will be loaded into the form, allowing you to make changes and save the updated event.

### Deleting an Event

Open the events for a selected day and click the delete icon next to the event you want to remove.

The event will be deleted immediately from the calendar and from local storage.

## Keyboard Shortcuts

The application supports several keyboard shortcuts:

- `←` / `→` — Navigate between dates
- `T` — Return to today's date
- `A` — Open the Add Event form

These shortcuts make it possible to navigate and manage the calendar without relying entirely on the mouse.

## Data Storage

Events are stored locally in the user's browser using `localStorage`.

Each event is represented as an object with a date and title:

{ date: "YYYY-MM-DD", title: "Event Title" }


All events are stored using the following `localStorage` key:

calendarEvents


Because the data is stored locally, events remain available after refreshing or reopening the page in the same browser.

> Note: Events are stored only on the current device and browser. Clearing the browser's local storage will remove the saved events.

## Project Structure

Calendar-with-events/ ├── index.html ├── styles.css ├── script.js ├── README.md └── LICENSE


- `index.html` — Main structure of the calendar
- `styles.css` — Visual styles and responsive layout
- `script.js` — Calendar logic and event management
- `README.md` — Project documentation
- `LICENSE` — MIT License

## Future Improvements

The project can be extended with additional features, such as:

- Recurring events
- Event categories and colors
- Event search and filtering
- Notifications and reminders
- Dark mode
- External database storage
- Cloud synchronization
- User accounts
- Importing and exporting calendar data

These improvements could make the calendar more suitable for larger applications while keeping its current simple structure.

## Contributing

Suggestions, improvements, and contributions are welcome.

If you find a bug or have an idea for a new feature, feel free to open an issue or submit a pull request.

When contributing, please keep the code simple, readable, and consistent with the existing project structure.

## License

This project is licensed under the **MIT License**.

The MIT License allows the project to be used, modified, and distributed according to the terms of the license.

For more information, see the `LICENSE` file included in this repository.

## Author

Created by **Maurice Githinji (Mauricegitech)**.

GitHub:
https://github.com/Mauricegitech
