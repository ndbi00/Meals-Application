# 🍽️ Meals Application

<p align="center">
  A simple and user-friendly Flutter application for discovering meals,
  browsing food categories, filtering recipes, and saving favorites.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-Mobile%20App-02569B?logo=flutter" />
  <img src="https://img.shields.io/badge/Dart-Language-0175C2?logo=dart" />
  <img src="https://img.shields.io/badge/Riverpod-State%20Management-5C6BC0" />
  <img src="https://img.shields.io/badge/Material-3-757575?logo=materialdesign" />
</p>

---

## About the App

**Meals Application** is a Flutter app that allows users to explore different
meal categories and discover recipes.

Users can view detailed information about each meal, apply dietary filters,
and save their favorite meals for easy access.

---

## Features

-  Browse meals by category
-  View meal ingredients and cooking steps
-  Add and remove favorite meals
-  Filter available meals
-  Gluten-free filter
-  Lactose-free filter
-  Vegetarian filter
-  Vegan filter
-  Bottom navigation
-  Navigation drawer
-  Material 3 interface
-  State management with Riverpod

---

##  Screens

The application includes:

| Screen | Description |
|:---|:---|
|  **Categories** | Browse the available meal categories |
|  **Meals** | View meals belonging to a selected category |
|  **Meal Details** | View ingredients and preparation steps |
|  **Favorites** | Access meals marked as favorites |
|  **Filters** | Choose dietary preferences |

---

##  Built With

- **Flutter** - UI framework
- **Dart** - Programming language
- **Riverpod** - State management
- **Material 3** - UI components and theming
- **Google Fonts** - Typography

---

##  Project Structure

```text
lib/
│
├── data/
│   └── dummy_data.dart
│
├── models/
│   ├── category.dart
│   └── meal.dart
│
├── providers/
│   ├── favorites_provider.dart
│   ├── filters_provider.dart
│   └── meals_provider.dart
│
├── screens/
│   ├── categories.dart
│   ├── filters.dart
│   ├── meal_details.dart
│   ├── meals.dart
│   └── tabs.dart
│
├── widgets/
│   ├── category_grid_item.dart
│   ├── main_drawer.dart
│   ├── meal_item.dart
│   └── meal_item_trait.dart
│
└── main.dart



##  Getting Started

### 1. Clone the repository

```bash
git clone git@github.com:ndbi00/Meals-Application.git
```

### 2. Open the project

```bash
cd Meals-Application
```

### 3. Install dependencies

```bash
flutter pub get
```

### 4. Start an emulator or connect an Android device

Check that Flutter can detect it:

```bash
flutter devices
```

### 5. Run the application

```bash
flutter run
```

---

##  Main Dependencies

```yaml
dependencies:
  flutter:
    sdk: flutter

  google_fonts:
  transparent_image:
  flutter_riverpod:
```
