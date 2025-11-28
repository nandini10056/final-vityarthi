
# Smart Medicine Reminder (Python CLI Application)

## 📌 Project Overview
The **Smart Medicine Reminder** is a command-line application designed to help users manage their medication schedules effectively. It allows users to save medicines with dosage intervals and start times, then continuously monitors and notifies when each dose is due. All reminders are logged automatically for record-keeping.

---

## ✨ Features
- Add medicines with:
  - Name
  - Dosage interval (hours)
  - First dose time (HH:MM)
- Automatic real-time reminder system
- Logs reminders with timestamps
- Simple menu-based CLI interface
- Persistent storage using text files

---

## 🛠️ Technologies / Tools Used
- **Python 3.x**
- Built-in Python modules:
  - `time`
  - `datetime`
  - `os`

---

## 📥 Installation & Running the Project

### 1. Clone or download the project
```bash
git clone <your-repository-url>
````

### 2. Navigate to the project directory

```bash
cd smart-medicine-reminder
```

### 3. Run the application

```bash
python main.py
```

or

```bash
python3 main.py
```

---

## ▶️ How to Use the Application

When you launch the program, you will see:

![img 1](<screenshots/Screenshot 2025-11-23 165635.png>)

### **Option 1: Add Medicine**

You will enter:

* Medicine name
* Interval in hours (e.g., 6)
* First dose time in HH:MM format (e.g., 09:30)

The information is stored in `medicines.txt`.

### **Option 2: Start Reminder System**

* Runs continuously
* Checks every minute
* Alerts when it's time to take medicine
* Logs each reminder in `medicine_log.txt`
* Stop using **CTRL + C**

### **Option 3: Exit**

Ends the program.

---

## 🧪 Instructions for Testing

1. **Add a test medicine**

   * Name: TestMed
   * Interval: 1
   * First dose: Set time 1–2 minutes ahead of current time

2. **Start the reminder system**

   * Wait for the system to trigger a reminder
   * Confirm the message appears
   * Check `medicine_log.txt` for the new log entry

3. **Test multiple medicines**
   Add different medicines to verify the reminder system handles multiple intervals.

4. **Test data persistence**
   Restart the program and verify previously added medicines still load correctly.

# Output Screenshots:
![alt text](<screenshots/Screenshot 2025-11-23 165635.png>)

![alt text](<screenshots/Screenshot 2025-11-23 165801.png>)

![alt text](<screenshots/Screenshot 2025-11-23 165855.png>)

#  Conclusion

The Smart Medicine Reminder provides a simple yet effective solution for managing medication schedules using a lightweight Python CLI interface. By combining real-time notifications, persistent storage, and automated logging, the system ensures users never miss their important doses. Its modular structure, ease of use, and minimal dependencies make it highly accessible for beginners while still demonstrating core programming concepts like file handling, scheduling logic, and time-based automation. With further enhancements—such as GUI integration, mobile notifications, or database storage—the project can be expanded into a fully featured personal health assistant.