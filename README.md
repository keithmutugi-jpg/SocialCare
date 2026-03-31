# SocialCare

SocialCare is a simple multi-page community support website built with HTML and Tailwind CSS. It presents an organization focused on practical care, education access, health support, counseling, and food assistance.

## Overview

This project is a static website designed to share information about SocialCare's mission and services in a clean, accessible layout. It includes:

- A home page with a hero section and service highlights
- An about page with the mission, vision, and values
- A services page describing the key support programs
- A contact page with a message form interface

## Pages

- `index.html` - landing page and service highlights
- `about.html` - organization background and purpose
- `services.html` - detailed service offerings
- `contact.html` - contact form page

## Built With

- HTML5
- Tailwind CSS via CDN

## How To Run

Because this is a static website, you can open `index.html` directly in your browser.

If you want to run it with a local server, you can use:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Project Structure

```text
SocialCare/
├── index.html
├── about.html
├── services.html
├── contact.html
└── README.md
```

## Features

- Responsive layout using Tailwind utility classes
- Simple navigation across all pages
- Community-focused branding and messaging
- Service cards with direct navigation from the home page
- Contact form UI for user inquiries

## Notes

- Tailwind CSS is loaded from the CDN, so an internet connection is needed for styling to appear correctly.
- The contact form currently provides the interface only and is not connected to a backend.

## Author

Created as part of the SocialCare website project.
