# Kronoscan
Created by [Nico Aroca](https://github.com/tailsmonster)

> Kronoscan is a local-first productivity app that combines a powerful calendar with flexible task and event management, designed to get you started instantly, with optional cloud sync for multi-device use.

---
## 🎶 Vibes

Listen to the Weatherscan's soundtrack while contributing to / using this. Track 27 is incredible.

## ⚡ MVP Goals

Kronoscan’s initial release will focus on:

- **Offline-First Experience**  
  Users can create, edit, and view events and tasks entirely offline with local storage (IndexedDB on web, SQLite on mobile).

- **Core Calendar Views**  
  Basic Month, Week, and Day views to navigate and manage your schedule intuitively.

- **Event & Task Management**  
  Add, edit and delete events and tasks with key details like title, time, description, and optional tags.

- **Backend API**  
  A .NET Web API providing:
  - User authentication (optional sign-in)
  - Data sync endpoints to keep multiple devices updated
  - Proxy and aggregation of external APIs, starting with weather data, to enrich user experience

- **External API Integration**  
  Fetch real-time weather information relevant to the user's location.  
  Additional APIs (e.g., job postings, policy alerts) may be integrated in future updates.

- **Basic Conflict Resolution**  
  Handle simple sync conflicts with last-write-wins logic.

- **Cross-Platform Support**  
  Web app (React + TypeScript) and mobile app (React Native with Expo), sharing core business logic and models.


---

## 📦 Project Structure
```
Kronoscan/
├── backend/ # .NET Web API for authentication and sync
├── web/ # React + TypeScript frontend
├── mobile/ # React Native mobile app (Expo)
├── shared/ # Shared TypeScript models and utilities
└── README.md
```


---

## 🚀 Next Steps

- Build backend API endpoints for auth and sync  
- Add a sparatic note taking system for users to jot down important memos 
- Implement local storage layers for offline data on web & mobile  
- Create basic calendar UI with event CRUD  
- Develop sync manager to push and pull changes from backend  
- Add user registration and login flows  

---

## 🤝 Contributing

This project is in early development. Contributions and ideas are welcome!

---

## ⚠️ Disclaimer

This is a personal project aiming for a minimal viable product. Features, structure, and priorities may change over time.

