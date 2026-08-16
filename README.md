# Duesday

**Never miss a deadline again.**

Duesday is a simple deadline tracker for students. Add your assignments, exams, projects, and quizzes — then see at a glance what's coming and how heavy your week really is.

**Offline-first. No account. No ads. No tracking.** Your data stays on your phone. The optional AI features are the only features that require an internet connection.

## Features

* **Workload dashboard** — the next 7 days at a glance: total hours, your busiest day, and hours per subject.
* **Calendar** — a month view where every day is color-tinted by workload (light → moderate → heavy → very heavy), with tap-for-details and swipe between months.
* **Requirements** — assignments, exams, projects, quizzes, presentations, labs, research, and more, each with a title, subject, deadline, estimated hours, and priority.
* **AI note scanner (optional)** — photograph your handwritten notes or pick a PDF, and the tasks and deadlines are added for you. Uses Google's Gemini service only when you use it.
* **AI priority hints (optional)** — a suggested priority as you type.
* **Smart reminders** — local notifications before each deadline, with the lead time you choose (e.g. 1 day or 3 hours).
* **Home-screen widgets** — countdown and upcoming-deadline widgets.
* **Recurring tasks** — for weekly or monthly assignments.
* **Extras** — dark/light theme, Monday-or-Sunday week start, CSV export, and an interactive tutorial.

## Screenshots

Screenshots of the dashboard, calendar, requirements list, AI scanner, workload overview, and settings will be added here.

## Privacy

Your requirements stay on your phone. Everything is stored locally in an encrypted on-device database using SQLCipher with AES-256 encryption, with encryption keys held in the Android Keystore.

The only exception is the optional AI scanner and priority features, which send the specific note, photo, or text you choose to Google Gemini for one-time processing.

**No accounts. No ads. No analytics. No tracking.**

See [PRIVACY_POLICY.md](PRIVACY_POLICY.md) for the full privacy policy.

## Tech Stack

* **Platform:** Android
* **Language:** Java
* **Architecture:** ViewModel + LiveData
* **Database:** Room with SQLCipher encryption
* **Security:** AES-256 encryption with Android Keystore
* **UI:** Material Components with light and dark theming
* **AI:** Google's Gemini API for optional AI features
* **Minimum Android version:** Android 8.0 (API 26)
* **Target SDK:** 35

## Offline-First

Duesday is designed to work without an internet connection for its core functionality.

Your requirements, deadlines, workload information, settings, and other app data are stored locally on your device.

An internet connection is only needed when you use the optional AI features.

## Download

Grab the latest APK from the [Releases page](https://github.com/KBDATUIN/duesday/releases).

> **Note:** Android may warn about installing from "unknown sources" — that's normal for APKs installed outside the Play Store. Tap **Install anyway** (or allow **Install unknown apps** for your browser or file manager).

## Support

Found a bug or have an idea for a future update?

* Open an [issue](https://github.com/KBDATUIN/duesday/issues), or
* Email: **[duesday.app.ph@gmail.com](mailto:duesday.app.ph@gmail.com)**

## License

See the repository for the current license and project terms.
