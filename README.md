<div align=center>                                                                                                  
<img width="300" height="300" alt="deee" src="https://github.com/user-attachments/assets/e5b49ed0-8c77-41fc-90e9-7a63130298b4" />

# Duesday

</div>

**Never miss a deadline again.**

Duesday is a deadline manager for students. List down your assignments, tests, projects, and quizzes, and get a quick overview of what you have to deal with this week.

**Works offline. Requires no registration. No advertisements. No tracking whatsoever.** All your deadlines are stored on your device, and only the AI scanner requires an internet connection.

## Why Duesday?

Entering what you are supposed to do into a simple notes app just writes it down; it does not help you stay on track.

Here's how Duesday transforms that list into something usable:

* A basic note does not act in any way. **Duesday acts on its own**, as it tracks the time required for the task, indicates the most busy days and reminds about the upcoming deadline.
* No need to scroll through to see which tasks are due. **The calendar highlights every single day by workload**, so one can immediately notice a very busy week in terms of the amount of work, rather than searching for it in the text.
* Notes may be messy and unstructured. **Duesday structures all information** (title, subject, type, deadline, estimated hours, priority and status).
* Notes cannot remind one. **Duesday offers local reminders**, as well as widgets, which display a countdown until the deadline and can be placed on the home screen.
* Notes do not offer a view on the future. **Duesday has a 7-day workload dashboard**, so one can see what is coming next and plan ahead of time.
* The application is also able to offer **recurring tasks, CSV export and workload statistics**, which a notes app cannot provide.

## Features

* **Workload Dashboard** – the next 7 days at a glance: total hours, your busiest day, and hours per subject.
* **Calendar** – a month calendar where each day is tinted by workload (light, moderate, heavy, very heavy), and can be tapped for more details, swiped to switch month.
* **Requirements** – assignments, exams, projects, quizzes, presentations, labs and research, with each having a title, subject, deadline, estimated hours and priority.
* **AI note scanner (optional)** – take a photo of your handwritten notes or select a PDF file, and the tasks with deadlines will be created for you. The app uses Google's Gemini service only if you activate it.
* **AI priority hints (optional)** – a recommended priority while typing.
* **Smart reminders** – local reminders before each deadline, with customizable lead time (e.g. 1 day or 3 hours).
* **Home screen widgets** – countdown widget and upcoming deadlines widget.
* **Recurring tasks** – for assignments that repeat weekly or monthly.
* **Others** – dark/light mode, Monday/Sunday week beginning, CSV export and tutorial.

## Screenshots

<img width="3500" height="1000" alt="Untitled design" src="https://github.com/user-attachments/assets/39d2e7a0-9816-44e5-8549-30c1c77e5142" />

## Privacy

All your requirements are kept in your phone. All data is stored locally on the device in an encrypted database (SQLCipher, AES-256), where keys are kept in the Android Keystore.

The only exception is the optional AI scanner and priority functions, which will transmit the exact note, image, or text that you select to Google Gemini for one-off processing.

**No accounts. No ads. No analytics. No tracking.**

See [PRIVACY_POLICY.md](PRIVACY_POLICY) for the full privacy policy.

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

Duesday works offline by default with regards to its basic functionalities.

Your deadlines, requirements, workload information, settings, and other data about the app are saved on your device.

The Internet is required only when using the extra features provided by the AI assistant.

## Download

Grab the latest APK from the [Releases page](https://github.com/KBDATUIN/duesday/releases).

> **Note:** Android may warn about installing from "unknown sources" — that's normal for APKs installed outside the Play Store. Tap **Install anyway** (or allow **Install unknown apps** for your browser or file manager).

## Support

Found a bug or have an idea for a future update?

* Open an [issue](https://github.com/KBDATUIN/duesday/issues), or
* Email: **[duesday.app.ph@gmail.com](mailto:duesday.app.ph@gmail.com)**

## License

See the repository for the current license and project terms.
