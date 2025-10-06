# 🍽️ React Native Christoffel Food Menu App (TypeScript)

This project is a simple **React Native mobile application** built with **TypeScript** and **Expo**.  
The app allows users to **view**, **add**, **and delete** dishes from a menu, as well as view a **summary** of the total dishes and total cost.

---

## 📱 App Overview

The project was created to demonstrate the use of **React Native core components** and **navigation** while applying clean coding practices with **TypeScript**.

**Main Features:**
- View a list of dishes (with names, descriptions, and prices)
- Add a new dish using a form
- Delete a dish with a confirmation modal
- Display total number of dishes and combined cost
- Smooth navigation between multiple screens

---

## 🧩 Technologies Used

- **React Native** – for building the mobile interface  
- **TypeScript** – for type safety and cleaner code  
- **Expo** – for easy development and testing  
- **React Navigation** – for navigation between screens  
- **React Native Core Components:**  
  - `Text`, `View`, `FlatList`, `Image`, `TextInput`, `Modal`, `Button`, `Alert`, `StyleSheet`

---

## ⚙️ Installation and Setup

Follow these steps to run the project locally:

### 1. Install Expo CLI (if not already installed)
```bash
npm install -g expo-cli

### Step 2: Create a New Project
expo init menu-manager


Choose the Blank (TypeScript) template when prompted.

### Step 3: Navigate to the Project Folder
cd menu-manager

### Step 4: Install Required Dependencies
npm install @react-navigation/native @react-navigation/stack
expo install react-native-screens react-native-safe-area-context react-native-gesture-handler react-native-reanimated

### Step 5: Add the Project Files

Replace the default files with the following structure:

/screens
 ├── HomePage.tsx
 ├── FoodList.tsx
 ├── AddToMenu.tsx
 └── Summary.tsx
App.tsx

### Step 6: Run the App
expo start


You can scan the QR code using the Expo Go app on your smartphone or run it on an emulator.





