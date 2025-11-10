# GoTag

"I wanted to be sure I locked my door every day without checking twice."

GoTag is an Android app that connects your daily tasks with NFC/IC tags, allowing you to mark daily tasks as completed simply by scanning a tag. It's perfect for building habits, tracking routines, and confirming physical actions — like locking your door or reading a book — in real life. It's also perfect for seeing when you completed a specific action or knowing how many times a specific task was done in one day. 

---
## Not Available Yet, this README is written by AI for now.
---

## Features

- **NFC Task Linking** – Attach a unique NFC/IC tag to each task. When scanned, it automatically marks the task as completed for the day, each additional scan will increase the count.
- **Daily Reset** – Tasks reset every 24 hours, encouraging consistent daily habits.
- **Progress Tracking** – View completion history and streaks to stay motivated.
- **Local Database** – All data is stored locally on your device for privacy and offline use.
- **Rainmeter Integration (PC)** – Optional module for syncing local progress data to display the last 7 days and up to 5 selected tasks on your PC desktop.

---

## Architecture Overview

**Platform:** Android (Kotlin)

**Local Storage:** Room Database (SQLite)

**Rainmeter Sync:** Local JSON or SQLite export accessed from PC (via local network or shared folder)

**UI:** Jetpack Compose

**NFC Handling:** Android NFC API (`NfcAdapter`, `Tag`, `NdefMessage`)

---

## Example Use Cases

- **Door Check:** Place a tag on your door. Scan it when leaving to confirm it's locked.
- **Reading Tracker:** Attach a tag to your favorite book. Scan it when you start reading.
- **Workout Routine:** Place tags on gym equipment or at home workout spots.

---

## Roadmap

- [ ] Core Android NFC scanning and task binding
- [ ] Daily reset service (midnight reset)
- [ ] Streak and progress view
- [ ] Reminder notifications
- [ ] Export data to JSON for Rainmeter
- [ ] Rainmeter skin development

---

## License
Apache‑2.0

---

## Contributing

Pull requests and feature suggestions are welcome! Please open an issue before making significant changes.
