# Custamo

A personal macOS menu bar assistant with a retro pixel-art look. It lives behind a small space invader in the menu bar and opens with **Option + Space**.

<p align="center"><img src="icon.png" width="160" alt="Custamo icon"></p>

> The source code is private because the app connects to my own accounts. This page shows what it does and how it is built.

## Screenshots

*Personal details (mail, tasks, deadlines, bus stops) are blurred.*

![Home](screenshots/home.png)

| Kitchen | Lights |
|---|---|
| ![Kitchen](screenshots/kitchen.png) | ![Lights](screenshots/lights.png) |

## What it does

- **Home summary:** today at a glance, what is due in the next two days and the week ahead.
- **Mail:** unread email from several inboxes, summarized and prioritized by an LLM, with tasks created from dates found in messages.
- **Homework:** course deadlines from the university's learning platform with countdowns; submitted work is ticked off automatically from submission receipts.
- **Tasks:** a command line that turns a plain note ("call mom tmrw 5pm") into a dated task.
- **Calendar:** month and week views combining classes, homework, tasks and workouts.
- **Kitchen:** a drawn fridge, freezer and pantry with drag-and-drop food, grocery orders read from delivery emails, shelf-life tracking, and recipes with exact gram amounts that adjust to what is in stock.
- **Gym:** a weekly workout plan with sets, weights, rest timer and progress, synced to iPhone Reminders.
- **Campus bus:** live arrival times and a live map for the university bus routes.
- **Smart lights:** colors, scenes, moods, a sleep timer and music sync for Govee lights.
- **Subscriptions:** finds subscriptions in email, totals monthly costs and warns before trials end.
- **Screen saver:** a now-playing screen with the album cover and a live audio equalizer.
- **Themes:** 15+ pixel themes and backgrounds, plus a mini game.

## Built with

Python and Flask (local server), pywebview and PyObjC (native macOS window, menu bar item, notifications, location), JavaScript, HTML and CSS (interface), Swift (Core Audio tap, screen saver), Gmail API, iCalendar feeds, Leaflet maps, Govee API, and an LLM (Claude) for summaries, parsing and recipes. Developed with AI-assisted programming (Claude Code).

## Author

Deniz Yildiz, Industrial and Systems Engineering, Binghamton University
