Todo - Task Management Application
Overview
Todo is a task management application designed for Android. It enables users to create, manage, and organize tasks efficiently. Built with a modern tech stack, the application leverages best practices in Android development, utilizing Kotlin, MVVM (Model-View-ViewModel) / Clean Architecture, Fragments, and Dependency Injection via Dagger & Hilt. Firebase powers the backend for user authentication and real-time data management, while the interface follows Material Design 3 guidelines and adapts to the system's light/dark mode preference.

Features
Task Management: Create, read, update, and delete tasks with ease.
Task Attributes: Each task includes a title, description, due date, priority level, and completion status.
Data Persistence: Task data is stored in Firebase Firestore, allowing for cloud-based storage and retrieval.
User Authentication: Firebase Authentication ensures secure login for users.
Dark/Light Mode: The interface adapts to the device’s light/dark mode settings.
Clean Architecture: Adheres to MVVM/Clean Architecture principles for better maintainability and separation of concerns.

Tech Stack
Kotlin: The primary language for Android development.
MVVM / Clean Architecture: Ensures separation of concerns and testability.
Fragments: Modular UI components for efficient navigation.
Dagger & Hilt: Dependency injection framework for better management of dependencies.
Firebase:
Authentication: Secure login system.
Firestore: Cloud-based database for real-time storage of tasks.
Material 3: Follows Material Design guidelines for UI and adapts to the system’s light/dark mode.
