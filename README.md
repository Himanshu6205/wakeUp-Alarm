# WakeUp - Alarm Clock Web App

WakeUp is a modern, responsive alarm clock web application built using **React** and **Bootstrap 5**. It allows users to set multiple alarms with custom labels, ringtones, repeat options, and password protection for stopping alarms.

---

## 🚀 Features

| Feature                    | Description                                     |
| -------------------------- | ----------------------------------------------- |
| ⏰ Real-time Clock          | Displays current time updating every second     |
| ➕ Add Multiple Alarms      | Set multiple alarms independently               |
| 🔁 Repeat Option           | Enable daily repeating of alarms                |
| 🏷️ Custom Labels          | Name alarms like “Wake Up”, “Meeting”, etc.     |
| 🎵 Ringtone Selector       | Choose from 9 built-in alarm sounds             |
| 🔊 Sound Preview           | Play the selected ringtone before saving        |
| 🔔 Alarm Notifications     | Desktop notification when alarm goes off        |
| 🔐 Password Protected Stop | Password is required to stop a ringing alarm    |
| 🔘 ON/OFF Toggle           | Enable or disable alarms anytime                |
| 💾 Persistent Storage      | Saves alarms and passwords using `localStorage` |
| 🌙 Dark Mode Toggle        | Switch between light and dark themes            |

---

## 🛠 Tech Stack

* **React 18** with functional components and hooks
* **Bootstrap 5.3.6** for UI styling and responsiveness
* **HTML Audio API** for alarm sound playback
* **Browser Notification API** for desktop alerts
* **LocalStorage** for saving alarm data

---

## 📂 Project Structure

```
src/
├── components/
│   ├── AlarmForm.js        # Alarm creation form
│   ├── AlarmList.js        # List of alarms with Stop and Toggle controls
│   ├── Clock.js            # Current time display
│   └── Navbar.js           # Responsive Navbar with theme toggle
├── App.js                  # Main app logic and state management
public/
└── sounds/                 # Folder with alarm1.mp3 to alarm9.mp3
```

---

## 🧪 How to Use

1. **Set Time** – Choose the alarm time.
2. **Label & Repeat** – Optionally name it and set to repeat daily.
3. **Ringtone** – Pick a sound and preview it.
4. **Password** – Set a password for stopping the alarm.
5. **Add Alarm** – Click the Add button to save it.
6. **When Alarm Rings** – A notification and sound play. Enter the correct password to stop it.

---

## 📦 Installation & Setup

```bash
# Clone the repo
https://github.com/yourusername/wakeup-alarm-app

# Navigate to project
cd wakeup-alarm-app

# Install dependencies
npm install

# Start the app
npm run dev  # or npm start (based on Vite or CRA)
```

---

## 🛡️ Notes & Security

* Passwords are stored as plain text in `localStorage`. For real applications, consider hashing them.
* Notifications require the user to **allow permission** in their browser.
* Works best in latest versions of Chrome, Edge, or Firefox.

---

## 💡 Future Improvements

* Use modals instead of `prompt()` for password input
* Add support for deleting alarms
* Allow sound file upload by user
* Set different volume or duration per alarm
* Add snooze functionality

---

## 👨‍💻 Author

Built by **Himanshu Patel** as part of a React learning series. ✨

---

## 📄 License

MIT License – free to use, modify, and share!
