# 🍽️ Recipes App

A Flutter application that allows users to explore food recipes from different **categories** and **countries**, view detailed recipe information, watch cooking videos, and save their favorite meals.

---

## 📱 Features

* 🔎 Search recipes by name
* 🍲 Browse recipes by **categories** (Beef, Chicken,Dessert, Pasta, Seafood,..etc)
* 🌍 Explore recipes by **countries** (Malaysian, Mexican, Moroccan, Egyptian,.. etc)
* 📖 View recipe details:

Here is a **professional, clean, and GitHub-ready README.md** for your project, based on your pubspec, API constants, and documentation file.

You can copy this directly into your `README.md` 👇

---

# 🍽️ Habayeb Recipes App

A modern Flutter application for exploring, searching, and saving delicious recipes from different categories and countries.

Habayeb Recipes makes cooking simple and enjoyable by combining recipe details, ingredients, and YouTube video tutorials in one smooth experience.

---

## 📱 Overview

The app allows users to:

* Browse recipes by category
* Explore recipes by country
* Search recipes by name
* View detailed recipe information
* Watch cooking videos
* Save favorite recipes
* Authenticate securely using Firebase

---

## 🔎 Features

### 🔐 Authentication

* Firebase Authentication
* Secure login & user sessions

### 🏠 Home Screen

* Categories section (Beef, Chicken,Dessert, Pasta, Seafood,..etc)
* Countries (Areas) section (Malaysian, Mexican, Moroccan, Egyptian,.. etc)

* Easy navigation

### 📖 Recipe Details

Each recipe includes:

* Description
* Ingredients list
* Preparation steps
* Embedded YouTube video
* Recipe image

### ❤️ Saved Screen

* Save / Unsave recipes
* Persistent storage using SharedPreferences

### 🔍 Search Screen

* Search recipes using name
* Real-time API fetching

---

## 🏗️ Architecture

The project follows **Clean Architecture** principles with proper separation of concerns:

* Presentation Layer
* Domain Layer
* Data Layer

### State Management

* Cubit (Flutter Bloc)

### Dependency Injection

* GetIt

---

## 🌐 API Integration

Base URL:

```dart
https://www.themealdb.com/api/json/v1/1/
```

### Endpoints Used

```dart
categories.php        // Get all categories
list.php?a=list       // Get all areas (countries)
filter.php            // Filter meals by category or area
search.php            // Search meals by name
lookup.php            // Get meal details by ID
```

API handled using:

* Dio
* Retrofit
* JSON Serializable

---

## 🛠️ Technology Stack

* Flutter
* Dart
* Firebase Core
* Firebase Authentication
* Cloud Firestore
* Firebase Storage
* Dio
* Retrofit
* JSON Serializable
* Flutter Bloc (Cubit)
* GetIt (Dependency Injection)
* YouTube Player Flutter
* Shared Preferences
* ScreenUtil
* Lottie
* Shimmer
* SVG Support

---

## 📌 Conclusion

Habayeb Recipes demonstrates the power of Flutter in building scalable, clean, and production-ready mobile applications using modern architecture, state management, and API integration.

It combines usability, performance, and clean code principles to deliver a smooth recipe browsing experience.

