# Waiter Menu Editor / Manager (Web)

This repository contains the **web build output** for a waiter-focused menu editor and management app.

## Purpose

Use this app to manage restaurant menu data from a browser, including menu updates and operational menu control.

## Project Contents

- `index.html`: web entry page (includes startup loading animation)
- `main.dart.js`: compiled app logic
- `flutter.js`, `flutter_bootstrap.js`: Flutter web runtime/bootstrap files
- `assets/`, `canvaskit/`, `icons/`: static assets required by the app

## Run Locally

Serve the folder as static files:

```bash
python3 -m http.server 8080
```

Open `http://localhost:8080`.

## Deployment

Deploy this folder to any static hosting platform (Nginx, Apache, Netlify, Vercel, Firebase Hosting, etc.).

Requirements:

- Keep the file/folder structure unchanged.
- Serve `index.html` at the app root path.

## Update / Rebuild

This directory is compiled output. Make feature/code changes in the Flutter source project, then rebuild:

```bash
flutter build web
```

Copy the generated `build/web` contents into this directory for release.
