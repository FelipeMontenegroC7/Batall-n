# 🎖️ Battalion Manager - Vehicle & Mission Management System

A **Java-based** management system designed to centralize and automate the control of military vehicles and tactical missions. This project implements core **Object-Oriented Programming (OOP)** principles and ensures data reliability through rigorous unit testing.

## 🚀 Key Features

The system manages diverse military units with specialized attributes:
* **Vehicle Management:** Full CRUD (Create, Read, Update, Delete) operations for:
    * 🚚 *Troop Transports* (Soldier capacity tracking).
    * 🛡️ *Armored Vehicles* (Armor level specifications).
    * 🚑 *Support Vehicles* (Logistics, Medical, and Communication functions).
* **Operational Control:** Real-time updates for mileage, operational status (Available, On Mission, Maintenance), and mission counters.
* **Mission Tracking:** Detailed logs of mission IDs, dates, locations, assigned personnel, and deployed vehicles.
* **Advanced Filtering:** Automatic reporting of high-experience units (vehicles with over 50 completed missions).

## 🛠️ Tech Stack

* **Language:** Java 17+
* **User Interface:** Swing (`JOptionPane`) for interactive dialog-based GUI.
* **Architecture:** OOP (Encapsulation, Inheritance, and Polymorphism).
* **Testing:** JUnit 5 for unit testing business logic and model constraints.

## 🧪 Unit Testing

To ensure system stability, unit tests were developed for every class within the model (`Battalion`, `Vehicle`, `Mission`). Key validations include:
- Successful vehicle registration and ID uniqueness.
- Accurate editing logic and status transitions.
- Mission counter integrity.
- Edge case handling for operational status updates.

## 📋 Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/repository-name.git](https://github.com/your-username/repository-name.git)
