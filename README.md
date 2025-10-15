
# SwasthFarm — Smart Livestock Health & Risk Management System

SwasthFarm is a web-based farm management system designed to empower livestock and poultry farmers with intelligent insights into **animal health**, **disease risks**, **weather-based alerts**, and **digital recordkeeping**.  

It combines **AI-powered disease detection**, **real-time weather tracking**, and **expert veterinary consultation** to support better decision-making and enhance biosecurity on farms.

---

## 🚀 Key Features

### 🧠 AI-Powered Disease Detection
- Upload photos of animals for instant AI-based disease diagnosis.
- Covers 50+ diseases with high accuracy.
- Provides treatment recommendations and preventive actions.

### 🌦️ Weather Risk Assessment
- Displays **real-time temperature**, humidity, and weather alerts.
- Risk level indicators (e.g., *Moderate risk of respiratory issues*).
- Preventive advisories for better ventilation and care.
- Integrated with live weather API for location-based updates.

### 📊 Smart Farm Dashboard
- **Training Progress Tracker:** Monitor biosecurity training completion and certification.
- **Feed Conversion Ratio (FCR):** Displays feed efficiency with performance indicators.
- **Mortality Rate Monitoring:** Detects abnormal mortality patterns and alerts the user.
- **Nearby Disease Cases:** Shows live swine flu or other outbreak data within a defined radius.
- **Vaccination Schedule:** Displays upcoming vaccination details with reminders.
- **Quick Actions Panel:** One-click access to Disease Detection and Expert Consultation.
- **Notifications Panel:** Real-time alerts for animal health issues (e.g., fever, isolation recommendations).

### 🧩 Risk Assessment Test
- Interactive test to analyze potential farm-level risks.
- Generates recommendations for improving farm safety and hygiene.

### 👨‍⚕️ Expert Consultation
- Connect with certified veterinarians via video calls or chat.
- 24/7 expert availability for personalized support.
- AI-assisted triage for quick guidance.

### 📋 Digital Health Records
- Maintain vaccination, treatment, and medical history for each animal.
- Track training and health analytics in one place.
- Easy data retrieval for reports and assessments.

### 📰 Disease Alerts & News
- Real-time outbreak notifications based on farm location.
- Updates from government and veterinary health departments.
- Preventive measures and disease management guidelines.

### 🎓 Training & Education
- Access expert-led video tutorials and biosecurity training.
- Certification tracking and progress monitoring.
- Best practices for sustainable and safe livestock management.

---

## 📊 Dashboard Overview

The **SwasthFarm Dashboard** presents all key metrics in one unified interface:

| Metric | Description | Example |
|---------|--------------|----------|
| **Temperature** | Real-time weather data | 28°C, partly cloudy |
| **Training Progress** | Biosecurity training completion bar | 0% – 100% |
| **Feed Conversion Ratio (FCR)** | Feed efficiency indicator | 1.65 (Good efficiency) |
| **Mortality Rate** | Health indicator of animal population | 2.3% (Needs attention) |
| **Swine Flu Cases Nearby** | Outbreak alert within radius | 120 (Within 10km) |
| **Vaccination Schedule** | Upcoming vaccination reminders | Next: 5 days |
| **Notifications** |

---

## 🏗️ Project Structure

```

📦 SwasthFarm
├── 📁 model_web               # TensorFlow.js disease models
├── 📁 poultry_disease_tfjs    # AI model data for disease detection
├── 📁 scripts                 # JS logic and Firebase integration
├── 📁 styles                  # CSS stylesheets
├── 📄 dashboard.html          # Main dashboard
├── 📄 disease_test.html       # AI disease detection module
├── 📄 weather.html            # Weather and risk alert page
├── 📄 digitalrecord.html      # Digital health record page
├── 📄 government.html         # Government portal access
├── 📄 index.html              # Landing page
├── 📄 colage.html             # About / Services overview page
├── 📄 pigdashboard.html       # Pig management dashboard
├── 📄 pigrecord.html          # Pig health record system
├── 📄 chatest.html            # Chat testing module
├── 📄 FIREBASE_SETUP_NOTES.md # Firebase configuration guide
└── 📄 README.md

````

---

## 💻 Tech Stack

| Category | Technology |
|-----------|-------------|
| **Frontend** | HTML, CSS, JavaScript |
| **AI Chatbot** |
| **Backend / Auth** | Firebase Authentication & Firestore |
| **Weather API** | OpenWeatherMap API |
| **Version Control** | Git & GitHub |
| **IDE Used** | Visual Studio Code |

---

## ⚙️ Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/SwasthFarm.git
   cd SwasthFarm


2. **Set Up Firebase**

   * Go to [Firebase Console](https://console.firebase.google.com/)
   * Create a new project and add a web app.
   * Copy your Firebase config and replace it in `scripts/firebase.js`.
   * Enable:

     * Authentication (Email/Password)
     * Firestore Database

3. **Run the Application**

   * Open `index.html` in your browser.
   * For live testing, use **VS Code Live Server**.
   * Ensure TensorFlow.js models are in the correct folder.


## 🧩 Future Enhancements

* 📱 Mobile version using React Native.
* 🐷 Integration of IoT sensors for live temperature and animal health monitoring.
* 🤖 Continuous AI model retraining for local disease data.
* 📈 Advanced analytics dashboard for multi-farm management.
* 📤 PDF report export for health and vaccination records.

---

## 👩‍💻 Author

**Apoorva Singh**
💼 Full Stack Developer |
📧 Email: (mailto:apoorva6387@gmail.com)
🔗 GitHub: https://github.com/Apoorva-6387
🔗 LinkedIn: https://www.linkedin.com/in/apoorva-singh-88460a257/

---


