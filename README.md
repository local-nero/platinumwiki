# PlatinumDL Wiki

Welcome to the PlatinumDL development wiki.

This wiki serves as a complete archive of every major change made to PlatinumDL throughout development. Instead of keeping one massive changelog, updates are organized into folders based on the day they were implemented.

To-Dos will be added at Issues because there's no convenient way of doing so.

---

# Folder Structure

```
wiki/
├── README.md
├── 2026-06-29/
│   ├── README.md
│   ├── staff-panel.md
│   ├── submissions.md
│   ├── discord-webhooks.md
│   └── stats-viewer.md
├── 2026-06-30/
│   ├── README.md
│   └── ...
```

Each folder represents **one day of development**.

---

# What belongs in each folder?

Each dated folder contains documentation for everything added, changed, or removed that day.

Examples include:

* New features
* Bug fixes
* UI redesigns
* Database changes
* API routes
* GitHub integration
* Discord integration
* Staff tools
* Player features
* Planned improvements

---

# Daily README

Every folder contains its own `README.md`.

Example:

```
2026-06-29/
├── README.md
├── submissions.md
├── review-modal.md
├── stats-viewer.md
```

The daily README acts as an overview of everything completed during that day's development.

Example:

```md
# June 29, 2026

## Completed

- Reworked submission page
- Added submission history
- Added Discord webhook integration
- Added Stats Viewer framework
- Improved staff review UI

## Notes

Most work focused on the submissions system and backend infrastructure.
```

---

# Individual Documentation

Whenever a feature becomes large enough, a separate markdown file will be created for it.

Example:

```
discord-webhooks.md
```

Contents:

* Purpose
* Environment variables
* Webhook format
* Embed layout
* Future improvements

This keeps documentation focused and easy to navigate.

---

# Naming Convention

Folders will always use the following format:

```
YYYY-MM-DD
```

Example:

```
2026-06-29
2026-06-30
2026-07-01
```

This guarantees chronological order.

---

# Documentation Style

Every page should answer the following:

* What was added?
* Why was it added?
* How does it work?
* Which files were modified?
* Are there any known limitations?
* Future improvements (if applicable)

---

# Goal

The goal of this wiki is to make PlatinumDL's development history easy to understand.

Anyone should be able to open any day's folder and immediately see what changed, why it changed, and how the system works.

As PlatinumDL grows, this wiki will become the primary reference for contributors, maintainers, and future developers.
