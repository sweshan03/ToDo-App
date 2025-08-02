# ToDo-App
Absolutely! Here's a **README.md** description for your **Pink-Themed Flutter ToDo App** with login and timestamped tasks:

---

## 🌸 Pink Themed TODO App (Flutter)

A beautifully designed Flutter TODO application with:

* 🩷 Pink gradient theme
* 🔐 Login page
* ✅ Task creation with auto-assigned date & time
* 🔍 Real-time search
* 🗑️ Swipe-to-delete
* 🔄 Pull-to-refresh
* 📱 Responsive layout (works on web & mobile)

---

### ✨ Features

| Feature                   | Description                                                     |
| ------------------------- | --------------------------------------------------------------- |
| 🎨 **Pink UI**            | Fully pink-themed using gradients, soft tones, and styled icons |
| 🔐 **Login Screen**       | Simple login interface with username and password input         |
| ➕ **Add Tasks**           | Add new tasks using a modal dialog                              |
| 🕒 **Timestamped Tasks**  | Automatically displays date & time when the task was added      |
| 🔎 **Search Tasks**       | Filter tasks instantly with a search bar                        |
| 🗑️ **Delete with Swipe** | Swipe left to delete tasks, with an undo Snackbar               |
| 🔄 **Pull to Refresh**    | Refresh task list with a downward swipe gesture                 |
| 📱 **Mobile/Web Support** | Responsive design using Flutter Material 3                      |

---

### 📸 Screenshots

<details>
  <summary>Login Page</summary>

*Login interface with gradient pink background and card design.*

</details>

<details>
  <summary>Task Page</summary>

*Task list with floating add button, search bar, and date & time display.*

</details>

---

### 🛠️ Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/pink-todo-flutter.git
   cd pink-todo-flutter
   ```

2. **Install dependencies**

   ```bash
   flutter pub get
   ```

3. **Run the app**

   ```bash
   flutter run -d chrome  # for web
   flutter run            # for mobile
   ```

---

### 📦 Dependencies

| Package | Purpose                        |
| ------- | ------------------------------ |
| `intl`  | Formatting date & time display |

Make sure to add to your `pubspec.yaml`:

```yaml
dependencies:
  flutter:
    sdk: flutter
  intl: ^0.18.1
```

---

### 🔧 Folder Structure

```
lib/
├── main.dart         # Entry point with all UI and logic
assets/               # (optional) Custom icons, fonts, images
```

---

### 📌 Future Improvements

* 🔔 Notifications for upcoming tasks
* ⏰ Add custom due dates with reminders
* ✅ Mark tasks as completed
* 🧠 Persistent storage (e.g. Hive or SharedPreferences)

---

### 💖 Made with Flutter & Love

---
“This project is a part of a hackathon run by 
https://www.katomaran.com ”
