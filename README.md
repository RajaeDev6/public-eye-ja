# Public Eye JA

Public Eye JA is an AI-driven reporting platform designed to make it simple for Jamaicans to report infrastructure issues such as potholes, broken streetlights, flooding, garbage pile-ups, drainage issues, and more.

Users take a picture, submit it, and Public Eye JA automatically:
1. Classifies the type of issue  
2. Extracts the location  
3. Packages the report  
4. Routes it to the correct government authority  

Built during the **Interibus AI Hackathon** by a team of three:
- **Abishua**
- **Areeba**
- **Rajae**

---

## 🚀 Problem We Wanted to Solve

Infrastructure issues across Jamaica often go unreported because:
- People don’t know *who* to contact  
- Reporting systems are slow and inconvenient  
- Users must manually type details and attach photos  
- Authorities receive incomplete or inconsistent reports  

Public Eye JA removes every barrier.

No forms.  
No frustration.  
Just: **Snap → Submit → Done.**

---

## ✨ Key Features

### 📸 **1. One-Tap Photo Reporting**
Users upload or take a picture.  
The app handles everything else automatically.

### 🤖 **2. AI Classification**
The system identifies:
- Potholes  
- Garbage pile-ups  
- Streetlight outages  
- Damaged road signs  
- Drainage/flood issues  
- Other hazards  

Powered by a cloud model integrated into the backend.

### 📍 **3. Automatic Geolocation Detection**
Extracts the image location:
- GPS coordinates from the device  
- Users can type in manually if they wanted to

### 📨 **4. Authority Matching**
Based on the issue type + location, the app determines:
- NWC  
- KSAMC  
- NSWMA  
- NWA  
- Parish councils  
- Relevant municipal offices  

Reports are automatically grouped by responsible entity.

### 🌐 **5. Admin Web Dashboard (React)**
The admin panel allows verification, monitoring, and exporting of reports:
- View incoming reports in real-time  
- Filter by category, location, or severity  
- Export reports for processing  
- Track which issues are resolved  

### 📱 **6. Mobile App (React Native)**
A clean UI focused on speed and simplicity:
- Minimal steps  
- Optimized photo uploads  
- Works on low-data connections  
- Persistent submission history

### ☁️ **7. Firebase Integration**
- Cloud Firestore for storing reports  
- Firebase Auth (optional future)  
- Firebase Storage for images  
- Real-time syncing with web dashboard

### 🧠 **8. Backend Powered by Flask**
The backend handles:
- Image preprocessing  
- AI inference call  
- Location pipeline  
- Authority routing logic  
- Report creation  
- Admin endpoints

---

## 🧰 Tech Stack

### **Frontend**
- React Native (mobile app)
- React (admin web interface)
- Expo (optional for build/testing)

### **Backend**
- Flask (Python)
- REST API architecture
- Geocoding + AI classification pipeline

### **Database / Storage**
- Firebase Firestore
- Firebase Storage

### **Infrastructure**
- Python environment  
- Firebase SDK  
- Cloud functions (optional upgrades)  

---

