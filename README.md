# Smart Parking Dashboard 🚗
A simple **GUI-based Java application** built using **Swing** and **AWT** that simulates a smart parking management dashboard.
It displays parking statistics like total slots, occupied slots, available slots, and current vehicles, along with a basic bar chart visualization and interactive buttons for vehicle entry and exit.
---

## 🧩 Features
* **Modern Dashboard UI**
  Displays parking information in an organized and visually appealing layout.

* **Dynamic Bar Chart**
  A simple graphical representation of parking data using custom `paintComponent()`.

* **Interactive Buttons**

  * **Entry Button:** Simulates navigation to the entry section.
  * **Exit Button:** Confirms before exiting the application.

* **Custom Styling**
  Colors, fonts, and borders give a professional look to the dashboard.
---

## 🛠️ Technologies Used

* **Java Swing** – for GUI components
* **AWT (Abstract Window Toolkit)** – for event handling and layout management
* **Object-Oriented Programming (OOP)** principles
---
## 📂 Project Structure

```
project/
│
├── SmartParkingDashboard.java   # Main application source file
└── README.md                    # Project documentation
```

---

## 🚀 How to Run

1. **Open the project in any Java IDE** (e.g., Eclipse, IntelliJ IDEA, or NetBeans)
   or use a terminal/command prompt.

2. **Compile the program:**

   ```bash
   javac SmartParkingDashboard.java
   ```

3. **Run the application:**

   ```bash
   java SmartParkingDashboard
   ```

4. The dashboard window will open, displaying parking details and buttons.

---

## 💡 Code Overview

### Main Components:

* **`JFrame`** → Main window
* **`JLabel`** → Display parking data
* **`JButton`** → Handles Entry and Exit actions
* **`JPanel`** → Organizes components and draws the chart
* **`ActionListener`** → Responds to button clicks

### Methods:

* `createInfoBlock(String title, String value)` → Creates and styles a label block
* `actionPerformed(ActionEvent e)` → Handles button events

---
## 🖼️ Sample Output

**Window Title:** `Vehicle Parking Dashboard`

* Displays:
  * Total Slots: 50
  * Occupied: 30
  * Available: 20
  * Current Vehicles: 30

* Includes:
  * A simple bar chart
  * Entry and Exit buttons
---
## 📘 Author

Developed by:Ann Mariya Joby
Course/Project:Smart Parking Management System – Java Project
---

## 📝 License
This project is open-source and free to use for educational purposes.
