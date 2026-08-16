# Duesday

**Never miss a deadline again.**

Duesday is a simple deadline tracker for students. Add your assignments, exams, projects and quizzes — then see at a glance what's coming and how heavy your week really is.

**Offline-first. No account. No ads. No tracking.** Your data stays on your phone; the optional AI note scanner is the only feature that needs an internet connection.

## Why Duesday?

Typing your activities, projects, assignments and other deadlines into a plain notes app only stores the text — it doesn't help you keep up.

Duesday turns that list into a working tool:

* A plain note is passive. **Duesday is active** — it tracks how much time each task needs, shows you the busiest days, and reminds you before deadlines hit.
* No more scrolling to find what's due. **The calendar color-tints every day by workload**, so a heavy week is obvious at a glance instead of being buried in a text dump.
* Notes get messy and inconsistent. **Duesday keeps everything structured** — title, subject, type, deadline, estimated hours, priority and status — so nothing important gets lost in the text.
* A note can't warn you. **Duesday sends local reminders** with the lead time you choose and shows countdown widgets on your home screen.
* Notes don't think ahead. **Duesday's 7-day workload dashboard** tells you what's coming and where the crunch is, so you can plan before it becomes an all-nighter.
* And because it's a real tracker, you get **recurring tasks, CSV export and workload statistics** — things a notes app simply can't do.

## Features

* **Workload dashboard** — the next 7 days at a glance: total hours, your busiest day, and hours per subject.
* **Calendar** — a month view where every day is color-tinted by workload (light, moderate, heavy, very heavy), with tap-for-details and swipe between months.
* **Requirements** — assignments, exams, projects, quizzes, presentations, labs and research, each with a title, subject, deadline, estimated hours and priority.
* **AI note scanner (optional)** — photograph your handwritten notes or pick a PDF, and the tasks and deadlines are added for you. Uses Google's Gemini service only when you use it.
* **AI priority hints (optional)** — a suggested priority as you type.
* **Smart reminders** — local notifications before each deadline, with the lead time you choose (e.g. 1 day or 3 hours).
* **Home-screen widgets** — countdown and upcoming-deadline widgets.
* **Recurring tasks** — for weekly or monthly assignments.
* **Extras** — dark/light theme, Monday-or-Sunday week start, CSV export, and an interactive tutorial.

## Screenshots

<img width="1080" height="2392" alt="Screenshot_20260816_122846" src="https://github.com/user-attachments/assets/b8090bc2-af99-49e6-a4f3-aeb6706bf17a" />
<img width="1080" height="2392" alt="Screenshot_20260816_122849" src="https://github.com/user-attachments/assets/1a14059e-b095-4e71-aedc-aa917f2bf572" />
<img width="1080" height="2392" alt="Screenshot_20260816_122852" src="https://github.com/user-attachments/assets/1ebe841a-a8c5-45e0-a79a-19c382b789de" />
<img width="1080" height="2392" alt="Screenshot_20260816_122855" src="https://github.com/user-attachments/assets/3134db4d-b62a-44c8-b410-ed79b0af6e97" />
<img width="1080" height="2392" alt="Screenshot_20260816_122859" src="https://github.com/user-attachments/assets/42114f9d-f861-47dc-9ce4-f7cb8c3e2543" />
<img width="1080" height="2392" alt="Screenshot_20260816_122904" src="https://github.com/user-attachments/assets/0aeb61ac-582d-464f-b49c-6f9b7d279e33" />
<img width="1080" height="2392" alt="Screenshot_20260816_122907" src="https://github.com/user-attachments/assets/2f4cfdc3-1ce2-46fc-884d-f2f272af6694" />


## Privacy

Your requirements stay on your phone. Everything is stored locally in an encrypted on-device database (SQLCipher, AES-256) with keys held in the Android Keystore.

The only exception is the optional AI scanner and priority features, which send the specific note, photo or text you choose to Google Gemini for one-time processing.

**No accounts. No ads. No analytics. No tracking.**

See [PRIVACY_POLICY.md](PRIVACY_POLICY.md) for the full privacy policy.

## Tech Stack

* **Android app:** Java
* **Database:** Room with SQLCipher encryption
* **Architecture:** ViewModel + LiveData
* **Security:** AES-256 encryption with keys held in the Android Keystore
* **UI:** Material Components with light/dark theming
* **AI:** Google's Gemini API for optional AI features
* **Minimum Android version:** Android 8.0 (API 26)
* **Target SDK:** 35

## Offline-First

Duesday is designed to work without an internet connection for its core functionality.

Your requirements, deadlines, workload information, settings and other app data are stored locally on your device.

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
