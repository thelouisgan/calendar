![image](https://github.com/user-attachments/assets/8c2b87d7-e263-4bca-bfba-29bdb51a1603)
# Hack Club Meetings & Hackathon Events Management Calendar

## Overview
This is an event management system for organizing and tracking **Hack Club meetings** and **Hackathon events**. The calendar allows users to create, manage, and view upcoming events with real-time updates using Firebase.

## Features
### 🗓️ Event Scheduling
- Add new events with **date, time, and participant details**.
- Support for **Hack Club meetings** and **Hackathon events**.
- View events in a **monthly calendar layout**.
![image](https://github.com/user-attachments/assets/9f240b07-4df3-4f8a-84ff-cb06d6d4359e)

### 🔄 Real-Time Updates
- Events are stored in Firebase Firestore.
- **Automatic synchronization** across all users.
- **Live updates** without refreshing the page.

### 🏆 Role-Based Access
- **Admin users** can:
  - Create, edit, and delete events.
  - Assign leaders to events.
  - View action logs/history.
- **Regular users** can:
  - View upcoming events.
  - Volunteer as event leaders.
  
### 📅 Calendar Interface
- Displays **weekly & monthly views**.
- Highlights **today's date**.
- Shows **staffing status** (e.g., events lacking leaders are highlighted).

### 🔥 Event Details Modal
- Click an event to view detailed information:
  - **Time & duration**.
  - **Assigned leaders**.
  - **Number of participants**.
  - **Options to edit or delete** (Admin only).
 
![image](https://github.com/user-attachments/assets/8f2631d1-eb5e-4bb0-94f7-a5057a1c8c03)


### 📌 Event Management
- Assign or remove **event leaders** dynamically.
- Prevent duplicate leaders from being assigned.
- Requires an appropriate number of **leaders per participant ratio**.

### ⚡ Action Logging
- Tracks **event creation, deletion, and leader assignments**.
- Users can access **event history logs**.

### 🎨 Theming & Customization
- **Dark mode toggle**. (BETA- Uncomment HTML button to experience and alter CSS theming as necessary)
- Mobile-friendly **responsive design**.

## Installation & Setup
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/thelouisgan/calendar
cd calendar
```

### 2️⃣ Setup Firebase
1. Go to [Firebase Console](https://console.firebase.google.com/).
2. Create a project and enable **Firestore**.
3. Replace the Firebase config in `calendar.html` with your own.
4. Create a **/users** document with the following structure for each of your Leaders:
   ![image](https://github.com/user-attachments/assets/98c9b629-b37d-45d7-9a10-62e8b4060797)


### 3️⃣ Deploy the Calendar
- Host it on **GitHub Pages, Netlify, Vercel, or Firebase Hosting**.
- Or simply **open `calendar.html` in your browser**.

## Contributing
We welcome contributions! 🚀 If you'd like to improve the project:
1. Fork the repo.
2. Create a new branch.
3. Submit a pull request.

## License
This project is licensed under the **MIT License**.

---
Made with ❤️ by Louis Gan for -> HACK CLUB

