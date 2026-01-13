Smart Donation App 📱🤝

Connecting generosity with need. A mobile platform designed to bridge the gap between donors with surplus items and receivers in need, fostering a sustainable community of sharing.

📖 Table of Contents

Project Overview

Key Features

Technology Stack

System Architecture

Project Estimation (COCOMO)

Setup & Installation

Screenshots

Contributors

🚀 Project Overview

The Smart Donation App is an Android application developed to facilitate the donation process of various items such as food, clothes, books, and furniture. It solves the problem of waste by providing a streamlined platform where donors can list items and receivers can browse, request, and coordinate pickups securely.

The application focuses on real-time interaction, user security, and an intuitive user interface.

✨ Key Features

🔐 Authentication & Security

Secure Sign-Up/Login: Email and password-based authentication.

Multi-Factor Authentication (MFA): SMS-based OTP verification using Firebase Phone Auth to verify user identity.

App Integrity: Protected by Firebase App Check to prevent abuse.

🎁 For Donors

Easy Uploads: Capture photos directly from the Camera or select from the Gallery.

Item Management: Categorize items (Food, Clothes, Baby, Toys, etc.), add descriptions, and set pickup locations.

Request Management: View incoming requests and Approve or Reject them instantly.

Edit/Delete: Modify item details or remove listings that are no longer available.

📥 For Receivers

Smart Browsing: Browse available items with category filters.

Request System: One-tap request functionality.

Order Tracking: Track the status of requests from "Pending" to "Approved" to "Completed".

Completion: Confirm item receipt to close the donation loop.

💬 Real-Time Communication

Integrated Chat: Secure, private chat rooms created automatically upon request approval.

Live Updates: Messages and status changes sync instantly across devices using Firestore real-time listeners.

🛠 Technology Stack

Language: Kotlin (100%)

UI Framework: Jetpack Compose (Material Design 3)

Architecture: MVVM (Model-View-ViewModel)

Backend: Google Firebase

Firebase Authentication: Identity management.

Cloud Firestore: Real-time NoSQL database.

Firebase Storage: Cloud storage for images.

Firebase App Check: Security.

Key Libraries:

Coil: Asynchronous image loading.

Navigation Compose: For managing app navigation.

Coroutines & Flow: For asynchronous programming.

🏗 System Architecture

The app follows the MVVM (Model-View-ViewModel) architectural pattern to ensure separation of concerns and testability.

Model (Data Layer): Handles data operations with Firebase (User.kt, Item.kt, Order.kt).

ViewModel (Logic Layer): Manages UI state and business logic (AuthViewModel, DonorViewModel).

View (UI Layer): Composable functions that observe state and render the UI (LoginScreen, DashboardScreen).

📊 Project Estimation (COCOMO)

To estimate the effort, schedule, and cost of this project, the Basic COCOMO (Constructive Cost Model) was applied.

Project Type: Organic (Small team, familiar environment, flexible requirements).

Estimated Size: 3 KLOC (3,000 Lines of Code).

Calculations

Effort (E): 2.4 * (3.0)^1.05 ≈ 7.6 Person-Months

Development Time (TDEV): 2.5 * (7.6)^0.38 ≈ 5.4 Months

Average Staff Size: 7.6 / 5.4 ≈ 1.4 Persons

Estimated Cost: ₹1,90,000 (Based on ₹25,000/month avg. salary).

⚙ Setup & Installation

To run this project locally:

Clone the Repository:

git clone [https://github.com/yourusername/smart-donation-app.git](https://github.com/yourusername/smart-donation-app.git)


Open in Android Studio:
Open Android Studio and select "Open an existing project". Point to the cloned folder.

Firebase Configuration:

Create a project in the Firebase Console.

Add an Android app with package name com.helphive.smartdonationapp.

Download the google-services.json file.

Place it in the app/ directory of the project.

Sync Gradle:
Let Android Studio download the necessary dependencies.

Run:
Connect a physical device or start an emulator and click "Run".

Note: For Phone Authentication to work on a real device, you must add your machine's SHA-1 and SHA-256 fingerprints to the Firebase console.

📸 Screenshots

Login Screen

Dashboard

Donation Upload

Chat Interface

(Add Screenshot)

(Add Screenshot)

(Add Screenshot)

(Add Screenshot)

👥 Contributors


[Team Member Name: Sneha Bai R C, Tejeshwini, Sneha Devale, Sindhu

Submitted as a Final Major Project for Bachelor of Computer Science at Ballari Institute of Technology And Management..