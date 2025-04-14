# 👵 Eldora — Empowering Elder Care with Technology

**Eldora** is a compassionate mobile app crafted with love and purpose to support **elders** and their **caregivers**. With features like fall detection, medicine reminders, emergency alerts, and geo-fenced safety zones, Eldora ensures peace of mind, independence, and proactive care — all in one beautifully designed app.

---

## 🌟 Features

### 🔐 Role-Based Login
- Users can choose to log in as either **Elder** or **Caregiver**.
- Role is stored securely using **Firebase Authentication** and **Firestore**.

### 🏡 Elder Dashboard
- View **fall detection reports** in real time (API integrated).
- Receive **medicine reminders** via scheduled notifications.
- Instantly alert family with an **Emergency SOS Button**.
- Monitor whether you're within your **Safe Zone** on a live map.
- Access personal **health records** securely.

### 👩‍⚕️ Caregiver Dashboard
- Monitor elder’s **live location** and **safe zone** status (via Google Maps API).
- Add/edit **medication reminders**, **health records**, and **emergency contacts**.
- Define **geo-fenced safe zones** using an interactive map.
- View elder’s **fall history** and overall wellbeing.

### 🗺️ Google Maps Integration
- Visualise and manage **Safe Zones**.
- Detect if elder leaves the zone and raise alerts.

### 🔔 Medicine Reminders
- Caregivers can schedule medicine reminders.
- Elders receive local push notifications at precise times.
- Data stored in Firestore for real-time syncing.

### 📦 Firebase Integration
- Firebase Authentication for secure login/logout.
- Firestore Database to manage user data, reminders, zones, and more.
- Firebase Functions for future scalability.

### 🚪 Logout Functionality
- Logout securely from either role at any time.
- Session is cleaned and user is redirected to login.

---

## 🧭 Tech Stack

| Tech         | Usage                         |
|--------------|-------------------------------|
| React Native | Mobile UI                     |
| Expo Router  | Navigation                    |
| Firebase     | Auth + Firestore              |
| Google Maps  | Safe Zones, Live Tracking     |
| Lucide Icons | Icons                         |
| Tailwind CSS | UI Styling (via NativeWind)   |
| Expo APIs    | Location, Notifications, etc. |

---

## 🛠️ Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/eldora-app.git
   cd eldora-app
