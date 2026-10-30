# QEC Medha Onneshon 2026 - Registration Status Page

A lightweight, single-page website where students of **QEC Academy's Medha Onneshon 2026** scholarship exam can check their registration and exam eligibility.

The page is mobile-first and works on every phone without any Google sign-in.

## What it does

- Lets a student look up their registration status using the details given in their confirmation message.
- Shows only registration and exam eligibility information, nothing else.
- Displays the official helpline and the scholarship disclaimer, loaded from the organiser's data source.

## How it works

- `index.html` is the whole site: plain HTML, CSS and JavaScript, with no build step and no dependencies.
- Data is read on request from a Google Apps Script web app that the organiser maintains; no student data is stored in this repository.
- Designed as a static site for free hosting such as GitHub Pages (`.nojekyll` makes GitHub Pages serve the files as they are).

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The complete page (layout, styles, script) |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Privacy

This repository contains no personal information about students. The page sets no cookies and uses no analytics or trackers. It loads fonts from Google Fonts and links to the helpline on WhatsApp. Only the status information a student searches for is returned.

## Maintainer

Rifat Hasan - https://github.com/rhrbd
