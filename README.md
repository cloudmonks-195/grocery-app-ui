# 🛒 Grocery App UI

A clean, modern, and responsive **Grocery Shopping App UI** built using **Flutter**.  
This app demonstrates essential UI screens required for any grocery shopping experience, with focus on reusable components, organized code structure, and an intuitive interface.

---

## ✨ Features

- 🏠 Home screen with banners and featured products  
- 📦 Product categories with easy navigation  
- 🧾 Product detail page with image, price, description, and add-to-cart  
- 🛒 Shopping cart with quantity and price management  
- 🔍 Product search screen  
- 🔽 Custom bottom navigation bar  
- 🎞️ Smooth screen transitions and animations  
- 🧱 Clean architecture with reusable widgets  

---

## 📁 Project Structure

grocery-app-ui/
├── assets/
│ └── (fonts, icons, sample images)
├── lib/
│ ├── constants/ # Colors, text styles, sizes
│ ├── data/ # Sample product & category data
│ ├── models/ # Product, Category data models
│ ├── screens/ # UI screens (Home, Cart, Product, etc.)
│ ├── theme/ # Light/Dark themes
│ ├── widgets/ # Reusable UI widgets
│ └── main.dart # App entry point
├── pubspec.yaml # Project configuration

markdown
Copy
Edit

### 📂 Folder Descriptions

- `constants/` – Global styles and constants like colors, text sizes  
- `data/` – Mock data for products and categories  
- `models/` – Defines data models used across the app  
- `screens/` – Contains all UI screens like Home, Product Detail, Cart  
- `theme/` – Flutter `ThemeData` for light/dark themes  
- `widgets/` – Custom widgets for buttons, cards, search bars, etc.  

---

## 🚀 Getting Started

### ✅ Prerequisites

- Flutter SDK (version 3.0 or higher)
- Android Studio / VS Code / IntelliJ
- Android/iOS emulator or real device

### 🧩 Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/cloudmonks-195/grocery-app-ui.git
   cd grocery-app-ui
Install Dependencies

bash
Copy
Edit
flutter pub get
Run the App

bash
Copy
Edit
flutter run
📌 Notes
This app is UI-only, no backend or state persistence is implemented.

Dummy data is stored locally in the data/ folder.

All images and fonts are loaded from the local assets/ folder.

🛠️ Customization
You can easily modify:

🎨 Colors → lib/constants/colors.dart

🖋️ Text styles → lib/constants/text_styles.dart

🎭 Themes → lib/theme/app_theme.dart

📦 Dummy data → lib/data/products.dart

🧠 Concepts Used
Flutter widgets like ListView, GridView, Stack, BottomNavigationBar

Stateless & Stateful widgets

Navigation using Navigator

Light and Dark theming with ThemeData

Modular folder structure

Clean UI design and reusable components

🤝 Contributing
Contributions are welcome!

Fork this repo

Create a feature branch

Commit your changes

Open a Pull Request 🚀

📄 License
This project is licensed under the MIT License.
You’re free to use, modify, and distribute with proper credit.

👨‍💻 Developed By
CloudMonks – A team passionate about Flutter, UI/UX, and mobile development.

