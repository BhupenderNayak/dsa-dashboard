# 📊 LeetSight Dashboard

LeetSight is a data-driven interview intelligence platform that transforms thousands of real-world coding interview experiences into actionable preparation insights. Instead of blindly solving problems, users can analyze company-specific DSA trends, identify high-frequency patterns, and generate personalized preparation roadmaps.

## 🚀 Live Demo

🌐 https://leetsight-delta.vercel.app

---

## ✨ Features

- 🔍 **Smart Company Search**
  - Search across **1,500+ tech companies** using a fast, searchable interface powered by `react-select`.

- 📈 **Pattern Analytics**
  - Discover the most frequently asked Data Structure & Algorithm patterns for every company.

- 🗺️ **Dynamic Roadmap Generator**
  - Automatically generates personalized study plans based on:
    - Available preparation days
    - Problem frequency
    - Company interview trends

- 📊 **Interactive Dashboard**
  - Clean visualizations for interview data and company-wise problem distributions.

- ⚡ **Modern SaaS UI**
  - Premium Indigo/Violet design system built with Tailwind CSS for a polished user experience.

- 📱 **Responsive Design**
  - Mobile-first interface optimized for desktop, tablet, and mobile devices.

- 🔄 **Real-Time API Integration**
  - Fetches interview insights dynamically from the backend with loading and error handling.

---

# 🛠 Tech Stack

### Frontend

- React.js
- Vite
- Tailwind CSS
- React Select
- Fetch API

### Architecture

- Component-Based Architecture
- Asynchronous API State Management (`useState` + `useEffect`)
- Modular UI Components
- RESTful API Integration

### Deployment

- Vercel
- GitHub CI/CD Auto Deployments

---

# 🏗 Engineering Highlights

### ⚡ Performance

- Optimized asynchronous data fetching
- Efficient UI rendering with component-based architecture
- Low-latency API synchronization
- Modular code structure for maintainability

### 🎯 UX Strategy

- High-performance searchable dropdown handling **1,500+ companies**
- Dynamic rendering based on API responses
- Loading states and graceful error handling
- Responsive layouts across devices

### 🎨 Design System

- Utility-first Tailwind CSS architecture
- Consistent spacing, typography, and color system
- Scalable reusable components
- Modern SaaS-inspired UI

---

# 🧩 Project Architecture

```
User
   │
   ▼
React Dashboard
   │
   ▼
REST API
   │
   ▼
DSA Miner API
   │
   ▼
PostgreSQL Database
```

---

# 🔗 Backend Repository

The frontend consumes data from the **DSA Miner API**, which handles interview data processing, aggregation, and REST endpoints.

**Backend Repository:**

👉 https://github.com/BhupenderNayak/dsa-miner-api

---

# 🚦 Local Setup

### Clone the repository

```bash
git clone https://github.com/BhupenderNayak/dsa-dashboard.git
```

### Install dependencies

```bash
npm install
```

### Configure Backend

Update the backend API URL inside the project (defaults to the production API).

### Start Development Server

```bash
npm run dev
```

---

# 🚀 Future Improvements

- Debounced API requests
- Loading skeletons
- Error Boundary components
- Advanced filtering & sorting
- Authentication
- User progress tracking
- Dark mode
- Improved SEO (Meta Tags & Open Graph)
- Analytics Dashboard
- Caching for faster repeated searches

---

## 📌 Tech Summary

| Category | Technology |
|-----------|------------|
| Frontend | React.js |
| Build Tool | Vite |
| Styling | Tailwind CSS |
| Search | React Select |
| State Management | useState, useEffect |
| API | Fetch API |
| Backend | DSA Miner API |
| Database | PostgreSQL |
| Deployment | Vercel |
| Version Control | Git & GitHub |

---

## ⭐ If you found this project useful, consider giving it a star!

Built to eliminate the guesswork from technical interview preparation by turning real interview data into personalized learning insights.
