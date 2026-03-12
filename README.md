# Travelo - Smart Travel Companion 🌍📱

**Travelo** is a modern Android application built with **Kotlin** during my Mobile Programming course. It serves as an interactive guide for travelers, allowing users to explore cities, browse tourist attractions by categories, and manage their personal travel settings through a sleek, user-friendly interface.

## 🌟 Key Features
- **User Management:** Complete authentication flow including Splash Screen (`LoadingActivity`), Login, and Registration.
- **City Exploration:** Dynamic views for exploring different cities and their unique landmarks (`CityActivity`).
- **Smart Categorization:** Users can browse attractions by categories (Hotels, Restaurants, Nature, etc.) via `CategoryDetailsActivity`.
- **Interactive Media:** High-quality image viewing with interactive zoom functionality (`ZoomActivity`).
- **Personalized Settings:** A dedicated settings interface (`SettingsActivity`) for user preferences.
- **Modern UI/UX:** Built using Material Design components and ConstraintLayout for a responsive and smooth experience.

## 🛠️ Technical Stack
- **Language:** Kotlin
- **SDK Version:** Target SDK 36 (Android 15) & Min SDK 29.
- **Architecture:** Activity-based architecture with clean separation of concerns.
- **UI Toolkit:** XML with Material Design 3.
- **Build System:** Gradle (Kotlin DSL).
- **Permissions:** Handles real-time Media and Internet permissions.

## 📁 Project Structure
- `LoadingActivity`: Managed the initial splash and app-state checking.
- `LoginActivity` / `RegisterActivity`: Handled user authentication logic.
- `MainActivity`: The central hub for navigating cities and categories.
- `CityActivity` & `CategoryDetailsActivity`: Handled dynamic content rendering based on user selection.
- `ZoomActivity`: Implemented for an enhanced image viewing experience.

## 🤝 Collaborative Effort & Contributions
This project was a result of successful team collaboration. While we worked together on the overall concept, my **specific contributions** included:
- **UI/UX Design:** Designed and implemented the layouts for [ذكر الشاشات التي صممتيها، مثال: Login and MainActivity] using XML.
- **Logic Implementation:** Developed the logic for [ذكر ميزة برمجتيها، مثال: Category filtering or Image Zooming].
- **Testing:** Conducted UI testing to ensure responsiveness across different screen sizes.

## 📸 Screenshots
![Screen_recording_20260312_211020-ezgif com-video-to-gif-converter (1)](https://github.com/user-attachments/assets/1090bb54-7c97-4344-b02b-33b94fa63ffd)

## 🚀 Getting Started
1. **Clone the repository:**
   ```bash
   git clone https://github.com/[YourUserName]/Travelo-Android-App.git
