# 💸 **Expense Tracker App**

An intuitive and efficient Android application that helps users **monitor and manage daily expenses**. Whether you're budgeting for a trip, tracking monthly bills, or just want visibility into your spending habits, this app makes it simple and visual.

Built using **Kotlin**, **Jetpack Compose**, and **Room**, this project demonstrates **modern Android development practices** and clean architecture.

---

## 🧾 **About the Project**

This Expense Tracker app allows users to:

- 📝 Add and categorize daily expenses
- 📜 View detailed transaction history
- 📊 Monitor expense trends and summaries
- 💾 Store data locally using Room Database
- 🧭 Navigate with Jetpack Compose's native tools

It follows the **MVVM architecture**, uses **Kotlin Coroutines** and **Flow** for asynchronous operations, and serves as a reference for:

- Learning Android development with Jetpack Compose
- Implementing scalable and testable app structure
- Contributing to open-source mobile finance tools

---

## ✨ **Features**

- ✅ Add, update, and delete expense entries
- 📅 Filter by date and category
- 📈 Visualize total and categorized spending
- 💽 Persist data with Room DB
- 🎯 Compose-based navigation
- 📐 Clean MVVM architecture with ViewModels

---

## 📸 **Screenshots**



### 📱 Dashboard / Expense Summary  
![Screenshot 2025-04-29 134527](https://github.com/user-attachments/assets/c03ef709-5f9f-4c7f-a54f-771307f77842)


### ➕ Add New Expense  
![Screenshot 2025-04-29 134654](https://github.com/user-attachments/assets/5ab8b65b-4087-4093-8415-4e241ab09b80)


### 📋 Add Income View 
![Screenshot 2025-04-29 134608](https://github.com/user-attachments/assets/93af1219-2fb4-45e3-80b0-9799d2ffc4e3)


### 🔁 Expense List View
![Screenshot 2025-04-29 134548](https://github.com/user-attachments/assets/8eb442f0-a41e-4801-8d6d-c9fc0d5397ab)


---

## 🛠️ **Getting Started**

### ✅ Prerequisites

- Android Studio **Hedgehog** or later
- Kotlin **1.9+**
- Gradle **8.0+**
- Android SDK **21+**

### 📦 Installation Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/expense-tracker-android.git
   ```

2. **Open in Android Studio:**
   - `File > Open` → Select the project folder

3. **Build the project:**
   - Android Studio will automatically sync Gradle and dependencies

4. **Run the app:**
   - Use an emulator or physical Android device

---

## 🧱 **Project Structure**

```
app/
├── data/                # Room database, DAO, models
├── base/                # Base ViewModel & navigation event logic
├── ui/                  # Composable UI and screen navigation
├── MainActivity.kt      # App entry point with navigation host
├── ExpenseTrackerApp.kt # App theme and application setup
```

---

## 🧪 **Running Tests**

Run unit and UI tests with:

```bash
./gradlew test
./gradlew connectedAndroidTest
```

---

## 📄 **License**

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.

---

Let me know if you’d like help resizing or designing the screenshots for visual consistency.
