# Showcase — Entry/Mid-Level Portfolio Hub

Showcase is a minimal, static landing page that links to my main backend-focused projects.  
It is designed as a clean, single entry point for recruiters and interviewers.

---

## Features

- Clean overview of highlighted projects
- Direct links to individual repositories (EventFlow, BuildTracker, AFrameHub)
- Responsive layout using Bootstrap
- Simple, static structure that can be served from any static host

---

## Tech & Structure

- Built with: **HTML**, **Bootstrap 5**, custom CSS
- No backend, no build step, no framework overhead

### Basic structure:

```
index.html
public/
css/
style.css
img/
```
---

## Usage

- Open `index.html` directly in a browser, or  
- Serve the folder with any static file server (for example: `npx serve`, Nginx, etc.)

---

## Architect’s Log

- The page is intentionally minimal: its purpose is to highlight the projects, not to be a complex app itself.
- Layout and copy are focused on clarity at first glance: title, short description, then direct links to repositories.
- No JavaScript or extra frameworks are used to keep the page fast, portable, and easy to reason about in an interview.
- The structure leaves room for future enhancements (sections for experience, skills, case studies) without changing the core layout.