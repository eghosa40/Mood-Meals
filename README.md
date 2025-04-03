# 🥗 Mood Meals

📱 *Tell me how you feel, and I’ll tell you what to eat.*  
Mood Meals is a simple Android app that uses OpenAI to suggest meals based on your current mood and available ingredients.

---

## 📌 Project Overview

### **App Name**
Mood Meals

---

### **Purpose**
Too many people waste time deciding what to eat. Mood Meals makes that decision fun and fast by using your *mood* and *available ingredients* to suggest recipes instantly via AI.

---

### **Target Users**
- University students
- Busy professionals
- Anyone who struggles with meal decisions
- People who want quick, mood-based food ideas

---

### **Core Features (MVP)**
- 😌 Mood selection screen (e.g. Lazy, Sad, Gym-mode, Broke)
- 🥕 Optional ingredient input (type a few ingredients you have)
- 🧠 OpenAI GPT-powered meal generation
- 🧾 Display 2–3 short recipe ideas
- ❤️ Save favorite recipes locally
- 📚 View saved recipes anytime (Favorites screen)

---

## 🧰 Tech Stack

### **Language**
- Kotlin

### **UI**
- Jetpack Compose

### **Architecture**
- MVVM (Model-View-ViewModel)

### **Backend**
- OpenAI GPT-3.5 API
- Local storage via `SharedPreferences` (or Room if extended)

---

## 📱 Screens

- **Mood Selection Screen** – User selects their mood from visual cards
- **Ingredients Input Screen** – Type in ingredients (optional)
- **Meal Suggestions Screen** – View AI-generated meal ideas
- **Favorites Screen** – View and manage saved recipes

---

## 🧪 How to Run

1. **Install Android Studio** (Electric Eel or newer recommended)
2. **Clone this repo**
   ```bash
   git clone https://github.com/eghosa40/Mood-Meals.git
