💸 Expense Tracker App
An intuitive and efficient Android application that helps users monitor and manage their daily expenses. Whether you're budgeting for a trip, tracking monthly bills, or just want visibility into your spending habits, this app makes it simple and visual.

Built using Kotlin, Jetpack Compose, and Room, this project demonstrates modern Android development practices and a clean architecture.

🧾 About the Project
This Expense Tracker app allows users to:

Add and categorize daily expenses

View detailed lists of recorded transactions

Monitor expense trends and summaries

Maintain a persistent local record using Room Database

Navigate across screens using a clean, single-activity architecture with Jetpack Compose

The architecture follows the MVVM pattern, ensuring a scalable, testable, and maintainable codebase. Navigation is handled using Compose’s native navigation library, and all data operations are performed asynchronously using Kotlin Coroutines and Flow.

This project can serve as a reference for:

Beginners learning Android development with Kotlin and Compose

Developers looking for a solid base template for scalable apps

Open-source contributions in mobile finance tools

✨ Features
✅ Add, update, and delete expense entries

📅 Filter expenses by date and category

📈 Visual summaries and categorized spending views

🗂️ Persistent data storage using Room database

🧭 Declarative navigation with Compose

⚙️ MVVM architecture using ViewModels and UI state flows

📸 Screenshots



🛠️ Gett![Screenshot 2025-04-29 134527](https://github.com/user-attachments/assets/9fd49697-6d0b-4ff1-b920-09175aad5f1c)![Screenshot 2025-04-29 134548](https://github.com/user-attachments/assets/bdc8c98c-2e05-436d-ab98-949f39d05ecb)
![Screenshot 2025-04-29 134608](https://github.com/user-attachments/assets/a06fc0fc-d0ac-4afb-8074-f8d772a926e9)
![Screenshot 2025-04-29 134654](https://github.com/user-attachments/assets/6a4d6fc4-d0ac-46f4-8a57-9eab19adb122)


✅ Prerequisites
Android Studio Hedgehog or later

Kotlin 1.9+

Gradle 8.0+

Minimum SDK 21 (Android 5.0)

📦 Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/expense-tracker-android.git
Open in Android Studio:

Go to File > Open and select the project folder.

Build the project:

Let Gradle sync and resolve dependencies.

Run the app:

Use an emulator or a connected device to install the app.

🧱 Project Structure
bash
Copy
Edit
app/
├── data/                # Room DB setup, DAO, and Entity models
├── base/                # Base ViewModel and navigation event classes
├── ui/                  # Composable screens and UI navigation
├── MainActivity.kt      # App entry point and navigation host
├── ExpenseTrackerApp.kt # Application class and app theme setup
🧪 Testing
Run the following commands for unit and UI tests:

bash
Copy
Edit
./gradlew test
./gradlew connectedAndroidTest
📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
