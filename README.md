# Navbat — Android app

Navbat books clinic appointments and live queue places in Uzbekistan. Patients find a clinic, take a place in the queue or book a time, and see their turn move in real time. The same service runs as a Telegram Mini App and a web app.

**[Download the APK](https://github.com/MakhmudSD/navbat-android/releases/latest/download/navbat.apk)** ([all releases](https://github.com/MakhmudSD/navbat-android/releases)) · [Demo video (77 s)](https://youtu.be/NfMuXIbuGT0) · [Web app](https://navbat-kappa.vercel.app) · [Telegram bot](https://t.me/toktok_navbat_bot)

## Install

1. On an Android phone, open the Releases page above and download the `.apk` file.
2. Open it and allow installs from your browser when Android asks.
3. Open Navbat and sign in.

The Google Play release is in review. This build is a preview: clinics and doctors are demo data.

## What's inside

- **Patients:** clinic search with a Yandex map, live queue position, booking by time, an AI assistant that finds free times from a plain-language request (Uzbek, Russian, English), visit history and notes.
- **Clinic staff:** call the next patient, manage the queue and the day's schedule.
- **Admins:** clinics, doctors, articles and polls in three languages.

## Built with

- **Mobile:** Expo (React Native), TypeScript, shared code with the web app.
- **Web and Telegram Mini App:** React, Vite, Tailwind.
- **API:** NestJS on Render, Supabase (PostgreSQL).
- **AI service:** FastAPI, Gemini with tool calling, grounded in live free times.

Source code is private. Built by [Makhmud Kudratov](https://github.com/MakhmudSD).
