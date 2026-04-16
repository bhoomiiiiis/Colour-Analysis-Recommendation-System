# 🎨 Color Analysis App

## 📌 Overview

The Color Analysis App is a web-based application that analyzes a user's undertone, contrast, and depth to generate a personalized color palette and determine their color season.

This project simulates a real-world recommendation system and includes data visualization and analytics features.

---

## 🎯 Features

* Interactive 3-step quiz (Undertone, Contrast, Depth)
* Personalized color palette with HEX codes
* Color season classification (Spring, Summer, Autumn, Winter)
* Analytics dashboard with charts and insights
* Local storage used to simulate database functionality

---

## 🛠 Tech Stack

* Frontend: Next.js, TypeScript
* Styling: Tailwind CSS
* UI Components: ShadCN UI
* Data Handling: LocalStorage (Database Simulation)

---

## 🗄 Database Design (Conceptual)

### SQL Schema

```
Users Table:
- id (Primary Key)
- undertone
- contrast
- depth
- season
- palette
```

### MongoDB Schema

```
{
  undertone: String,
  contrast: String,
  depth: String,
  season: String,
  palette: [String],
  createdAt: Date
}
```

---

## 🔄 Working Flow

1. User answers 3 quiz questions
2. System processes inputs using logic-based rules
3. Color palette and season are generated
4. Results are stored in local storage
5. Analytics dashboard displays insights

---

## 🚀 How to Run

```bash
npm install
npm run dev
```

---

## 📌 Future Improvements

* Database integration (MongoDB / SQL)
* User authentication
* Save and share results
* AI-based image color detection

---

## 👨‍💻 Author

Bhumika Sain
