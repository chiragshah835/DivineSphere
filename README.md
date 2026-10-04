# 🛕 DivineSphere

## AI-Driven Pilgrimage Management & Safety System

> **Predictive Crowd Management • Smart Evacuation • AI-Based Security • Intelligent Pilgrim Assistance**

**DivineSphere** is an AI-driven pilgrimage management and safety platform designed to make large-scale pilgrimages **safer, smarter, and more efficient**.

The system combines **Machine Learning, Computer Vision, mobile-camera inputs, real-time data processing, GIS, and intelligent route optimization** to help pilgrims and authorities manage crowds, predict waiting times, respond to emergencies, and monitor potential security threats.

---

## 🌟 Project Overview

Large pilgrimage destinations often experience:

* 👥 High crowd density
* ⏱️ Long waiting and queue times
* 🚨 Emergency situations
* 🗺️ Difficulty finding safe evacuation routes
* 🛡️ Security challenges in crowded environments

Traditional approaches may rely heavily on manual monitoring, which can make real-time decision-making difficult.

**DivineSphere** addresses these challenges through three intelligent AI-powered modules:

1. ⏱️ **Waiting Time Prediction**
2. 🚨 **Smart Evacuation Route System**
3. 🛡️ **AI-Based Security Detection**

---

# 🚀 Core Modules

## 1. ⏱️ Waiting Time Prediction

The Waiting Time Prediction module uses **historical and real-time crowd-related data** to estimate the expected waiting time at pilgrimage locations.

### Key Features

* 👥 Crowd density analysis
* ⏱️ Waiting-time estimation
* 📊 Historical data analysis
* 📈 Peak-hour identification
* 🔄 Real-time crowd data processing
* 🧠 Machine Learning-based prediction

### Workflow

```text
Historical + Real-Time Crowd Data
                ↓
         Data Preprocessing
                ↓
        Feature Extraction
                ↓
       ML Prediction Model
                ↓
       Estimated Waiting Time
                ↓
        User / Admin Dashboard
```

### Example

```text
Current Crowd: 850 people
        ↓
Historical Pattern Analysis
        ↓
ML Model
        ↓
Estimated Waiting Time: 42 Minutes
```

The prediction can help pilgrims plan their visit while helping authorities understand crowd conditions.

---

# 2. 🚨 Smart Evacuation Route System

The Smart Evacuation Route System provides an intelligent route during emergency situations.

Instead of simply selecting the shortest route, the system considers factors such as:

* 👥 Crowd density
* 🚧 Blocked paths
* 🚪 Available exits
* 📍 Current location
* 📏 Route distance
* ⚠️ Emergency conditions

### Key Features

* 🗺️ Map-based route visualization
* 🚨 Emergency route generation
* 👥 Crowd-aware routing
* 🚧 Blocked-path consideration
* 📍 Location-based navigation
* 🛣️ Safer route selection
* 🔄 Dynamic route calculation

### Workflow

```text
User Location
      +
Map / GIS Data
      +
Crowd Information
      +
Emergency Information
          ↓
     Route Analysis
          ↓
   Safety Evaluation
          ↓
  Route Optimization
          ↓
   Safer Evacuation Route
          ↓
    User Navigation
```

### Route Selection Concept

```text
                 Emergency
                     │
                     ▼
              Route Analysis
                     │
          ┌──────────┴──────────┐
          ▼                     ▼
     Shortest Route        Safer Route
          │                     │
          ▼                     ▼
   High Crowd Density      Low Crowd Density
          │                     │
          └──────────┬──────────┘
                     ▼
            Optimized Route
                     ↓
             User Navigation
```

---

# 3. 🛡️ AI-Based Security Detection

The Security Detection module uses a **mobile camera** as the primary visual input instead of fixed CCTV infrastructure.

Images or video frames captured through a mobile device are processed using **Computer Vision and AI models** to detect people, objects, and potentially suspicious activities.

### Key Features

* 📱 Mobile camera input
* 📸 Image/video frame processing
* 👤 Person detection
* 🔍 Object detection
* 🧠 AI-based activity analysis
* ⚠️ Suspicious-activity detection
* 🔔 Security alerts
* 📊 Security monitoring dashboard

### Workflow

```text
Mobile Camera
      ↓
Image / Video Frame
      ↓
Frame Processing
      ↓
Person / Object Detection
      ↓
Activity Analysis
      ↓
Risk Classification
      ↓
Security Alert
      ↓
Admin / Authority Dashboard
```

### Important

DivineSphere is an **AI-assisted security system**. A detected activity should be treated as an alert or indication requiring human verification, rather than automatically declaring a person a criminal.

---

# 🏗️ System Architecture

```text
                         ┌───────────────────────┐
                         │    PILGRIM / USER     │
                         │      Mobile App       │
                         └───────────┬───────────┘
                                     │
                                     │
                    ┌────────────────▼────────────────┐
                    │       MOBILE CAMERA INPUT      │
                    │   Images / Video Frames        │
                    └────────────────┬────────────────┘
                                     │
                                     ▼
                         ┌───────────────────────┐
                         │      API / BACKEND    │
                         │ Authentication        │
                         │ Data Processing       │
                         │ API Services          │
                         └───────────┬───────────┘
                                     │
              ┌──────────────────────┼──────────────────────┐
              │                      │                      │
              ▼                      ▼                      ▼
     ┌────────────────┐    ┌────────────────┐    ┌────────────────┐
     │ Waiting Time AI │    │ Smart Evac.    │    │ AI Security    │
     │ Prediction     │    │ Route System   │    │ Detection      │
     └───────┬────────┘    └───────┬────────┘    └───────┬────────┘
             │                     │                     │
             └─────────────────────┼─────────────────────┘
                                   │
                                   ▼
                         ┌───────────────────────┐
                         │       AI ENGINE       │
                         │                       │
                         │ Machine Learning      │
                         │ Computer Vision       │
                         │ Data Analytics        │
                         │ Route Optimization    │
                         └───────────┬───────────┘
                                     │
                                     ▼
                         ┌───────────────────────┐
                         │      DATA LAYER       │
                         │                       │
                         │ Crowd Data            │
                         │ Prediction Data       │
                         │ Map / GIS Data        │
                         │ Security Logs         │
                         └───────────┬───────────┘
                                     │
                                     ▼
                         ┌───────────────────────┐
                         │ DASHBOARD & ALERTS    │
                         │                       │
                         │ Pilgrim Interface     │
                         │ Admin Dashboard       │
                         │ Security Alerts       │
                         │ Emergency Alerts      │
                         └───────────────────────┘
```

---

# 🔄 Overall System Workflow

```text
                    DATA INPUTS
                         │
        ┌────────────────┼────────────────┐
        │                │                │
        ▼                ▼                ▼
   Mobile Camera    Crowd Data       Map / GIS
        │                │                │
        └────────────────┼────────────────┘
                         ▼
                 Data Processing
                         │
                         ▼
                  ┌──────────────┐
                  │   AI ENGINE  │
                  └──────┬───────┘
                         │
        ┌────────────────┼────────────────┐
        │                │                │
        ▼                ▼                ▼
   Waiting Time     Evacuation       Security
    Prediction        Route          Detection
        │                │                │
        └────────────────┼────────────────┘
                         ▼
                  Smart Dashboard
                         │
             ┌───────────┴───────────┐
             ▼                       ▼
          Pilgrims               Authorities
```

---

# 🧠 AI Architecture

```text
┌───────────────────────────────────────────────┐
│                 INPUT LAYER                   │
├───────────────────────────────────────────────┤
│ Mobile Camera • Crowd Data • Map/GIS Data     │
└──────────────────────┬────────────────────────┘
                       │
                       ▼
┌───────────────────────────────────────────────┐
│              PROCESSING LAYER                 │
├───────────────────────────────────────────────┤
│ Data Cleaning • Frame Processing              │
│ Feature Extraction • Data Transformation      │
└──────────────────────┬────────────────────────┘
                       │
                       ▼
┌───────────────────────────────────────────────┐
│                   AI LAYER                    │
├───────────────────────────────────────────────┤
│ Machine Learning • Computer Vision            │
│ Prediction • Classification • Analytics       │
└──────────────────────┬────────────────────────┘
                       │
                       ▼
┌───────────────────────────────────────────────┐
│              DECISION LAYER                   │
├───────────────────────────────────────────────┤
│ Waiting Prediction • Route Optimization       │
│ Security Risk Analysis                        │
└──────────────────────┬────────────────────────┘
                       │
                       ▼
┌───────────────────────────────────────────────┐
│             APPLICATION LAYER                 │
├───────────────────────────────────────────────┤
│ User Dashboard • Admin Dashboard • Alerts     │
└───────────────────────────────────────────────┘
```

---

# 📊 Module Comparison

| Module                     | Input                      | AI Technology            | Output                 |
| -------------------------- | -------------------------- | ------------------------ | ---------------------- |
| ⏱️ Waiting Time Prediction | Crowd & historical data    | Machine Learning         | Estimated waiting time |
| 🚨 Smart Evacuation        | Location, map & crowd data | GIS + Route Optimization | Safer evacuation route |
| 🛡️ Security Detection     | Mobile camera              | Computer Vision + AI     | Security alert         |

---

# 🛠️ Technology Stack

> Update this section according to the technologies actually used in your implementation.

### Frontend

* React.js
* HTML5
* CSS3
* JavaScript
* Responsive UI

### Backend

* Node.js
* Express.js
* REST APIs

### AI / ML

* Python
* Machine Learning
* Computer Vision
* Data Analytics

### Mapping

* GIS / Digital Maps
* Route Optimization

### Database

* MongoDB / MySQL

### Development Tools

* Git
* GitHub
* VS Code
* Postman

---

# 📂 Project Structure

```text
DivineSphere/
│
├── frontend/
│   ├── components/
│   ├── pages/
│   ├── services/
│   ├── assets/
│   └── App.jsx
│
├── backend/
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   ├── middleware/
│   └── server.js
│
├── ai-models/
│   ├── waiting-time/
│   ├── security-detection/
│   └── route-optimization/
│
├── datasets/
│   ├── crowd-data/
│   ├── waiting-time/
│   └── security-data/
│
├── maps/
│
├── docs/
│   ├── architecture/
│   ├── screenshots/
│   └── diagrams/
│
├── requirements.txt
├── package.json
└── README.md
```

---

# ✨ Key Features

### 👥 Crowd Management

* Real-time crowd data processing
* Crowd density analysis
* Peak-hour identification
* Crowd-aware decision making

### ⏱️ Prediction

* AI-based waiting-time prediction
* Historical pattern analysis
* Estimated queue time
* Predictive analytics

### 🚨 Emergency Management

* Emergency route generation
* Crowd-aware evacuation
* Safe exit identification
* Dynamic route optimization

### 🛡️ Security

* Mobile camera-based monitoring
* Computer Vision
* Person/object detection
* Suspicious activity analysis
* Security alerts

### 📊 Dashboard

* Real-time system insights
* Prediction results
* Route visualization
* Security notifications
* Admin monitoring

---

# 🎯 Problem Statement

Large pilgrimage destinations attract thousands or millions of visitors, creating challenges related to **crowd congestion, long waiting times, navigation, emergency evacuation, and security**.

Manual monitoring and static information may not be sufficient to respond effectively to rapidly changing situations.

### DivineSphere aims to solve this problem by providing:

> **An AI-powered platform that predicts crowd conditions, recommends safer evacuation routes, and assists with security monitoring using mobile-camera-based Computer Vision.**

---

# 💡 Proposed Solution

DivineSphere integrates three intelligent modules into one unified platform.

### 01 — Predict

Use Machine Learning to estimate pilgrimage waiting times.

### 02 — Protect

Use Computer Vision with mobile camera input to assist in detecting potentially suspicious activities.

### 03 — Evacuate

Use GIS and route optimization to identify safer evacuation paths during emergencies.

```text
                 DivineSphere
                      │
        ┌─────────────┼─────────────┐
        ▼             ▼             ▼
      PREDICT       PROTECT      EVACUATE
        │             │             │
    ML Model       AI + CV       GIS + AI
        │             │             │
 Waiting Time     Security       Safe Route
 Prediction        Alerts        Guidance
```

---

# 📱 Mobile Camera Architecture

Unlike conventional surveillance systems that depend on fixed CCTV infrastructure, DivineSphere uses **mobile cameras as the visual data source**.

```text
             User / Volunteer Mobile
                       │
                       ▼
                Mobile Camera
                       │
                       ▼
              Image / Video Frame
                       │
                       ▼
               AI Processing
                       │
             ┌─────────┴─────────┐
             ▼                   ▼
       Crowd Analysis       Security Analysis
             │                   │
             ▼                   ▼
       Crowd Insights       Risk / Alert
             │                   │
             └─────────┬─────────┘
                       ▼
                  Backend API
                       │
                       ▼
                 Admin Dashboard
```

### Advantages

* 📱 Uses commonly available mobile devices
* 💰 Reduces dependence on dedicated surveillance infrastructure
* 🚀 Easy to deploy at different pilgrimage locations
* 🔄 Flexible camera positioning
* 🌐 Can support distributed monitoring

---

# 📈 Expected Impact

## For Pilgrims

* ⏱️ Better understanding of expected waiting times
* 🗺️ Improved navigation
* 🚨 Faster emergency route guidance
* 🛡️ Improved safety awareness

## For Authorities

* 📊 Better crowd insights
* 🧠 Data-driven decision making
* 🚨 Faster emergency response
* 🛡️ AI-assisted security monitoring

## For Pilgrimage Management

* Improved crowd flow
* Better emergency preparedness
* Efficient monitoring
* Reduced operational uncertainty

---

# 🔐 Security & Responsible AI

DivineSphere follows a **human-in-the-loop approach** for security-related decisions.

### Principles

* 🔒 Secure handling of collected data
* 👤 Human verification of security alerts
* ⚠️ AI predictions are treated as alerts, not final judgments
* 🛡️ Role-based access for administrative functions
* 📝 Logging of important system events
* 🔐 Privacy-conscious processing of camera data

> **DivineSphere does not automatically declare an individual a criminal. AI-generated security alerts require appropriate human verification and responsible handling.**

---

# 🛣️ Development Roadmap

```text
Phase 1 — Foundation
│
├── Problem Analysis
├── Dataset Collection
├── Data Cleaning
└── System Architecture

        ↓

Phase 2 — Waiting Time Prediction
│
├── Feature Engineering
├── ML Model Development
├── Model Training
└── Model Evaluation

        ↓

Phase 3 — Smart Evacuation
│
├── Map/GIS Integration
├── Route Generation
├── Crowd-Aware Routing
└── Route Optimization

        ↓

Phase 4 — AI Security
│
├── Mobile Camera Integration
├── Image/Frame Processing
├── Computer Vision Model
└── Security Alert System

        ↓

Phase 5 — Platform Integration
│
├── Frontend
├── Backend APIs
├── AI Integration
└── Dashboard

        ↓

Phase 6 — Testing & Deployment
│
├── System Testing
├── Model Testing
├── Performance Optimization
└── Deployment
```

---

# 🔮 Future Scope

* 📱 Dedicated Android/iOS application
* 🌐 Multi-pilgrimage and multi-location support
* 📡 Real-time distributed mobile-camera monitoring
* 🧠 Advanced Deep Learning models
* 📈 Crowd surge prediction
* 🌦️ Weather-aware crowd prediction
* 🗣️ Multilingual AI assistant
* 🚑 Emergency-service integration
* ☁️ Cloud-based scalable deployment
* 🔔 Advanced real-time notification system
* 🗺️ 3D / advanced pilgrimage map visualization

---

# 📸 Screenshots

Add your project screenshots here:

```text
docs/
└── screenshots/
    ├── home.png
    ├── waiting-time.png
    ├── evacuation-route.png
    ├── security-detection.png
    └── admin-dashboard.png
```

Example:

### 🏠 Dashboard

*Add screenshot here*

### ⏱️ Waiting Time Prediction

*Add screenshot here*

### 🚨 Smart Evacuation Route

*Add screenshot here*

### 🛡️ AI Security Detection

*Add screenshot here*

---

# ⚙️ Installation & Setup

## 1. Clone the Repository

```bash
git clone https://github.com/your-username/DivineSphere.git
```

## 2. Navigate to the Project

```bash
cd DivineSphere
```

## 3. Install Frontend Dependencies

```bash
cd frontend
npm install
```

## 4. Install Backend Dependencies

```bash
cd ../backend
npm install
```

## 5. Install Python Dependencies

```bash
pip install -r requirements.txt
```

## 6. Configure Environment Variables

Create a `.env` file:

```env
PORT=5000
DATABASE_URL=your_database_url
MAP_API_KEY=your_map_api_key
AI_API_KEY=your_ai_api_key
```

## 7. Run the Application

### Backend

```bash
npm run server
```

### Frontend

```bash
npm run dev
```

---

# 🔗 System Integration

```text
Frontend
   │
   │ REST API
   ▼
Backend
   │
   ├──────────────► Database
   │
   ├──────────────► ML Prediction Service
   │
   ├──────────────► Computer Vision Service
   │
   └──────────────► GIS / Route Service
                         │
                         ▼
                    AI Results
                         │
                         ▼
                  User Dashboard
```

---

# 🧪 Testing

The system should be evaluated using:

### Waiting Time Module

* MAE
* RMSE
* Prediction accuracy
* Response time

### Evacuation Module

* Route distance
* Route generation time
* Crowd-aware route performance
* Emergency response time

### Security Module

* Precision
* Recall
* F1-score
* Detection accuracy
* False-positive rate

---

# 🌍 Real-World Use Cases

DivineSphere can be adapted for:

* 🛕 Temples
* 🕉️ Religious festivals
* 🚶 Large pilgrimages
* 🎉 Religious gatherings
* 🏟️ High-footfall public events
* 🚨 Emergency crowd management

---

# 🏆 Project Highlights

```text
🤖 AI-Powered
      +
⏱️ Predictive Analytics
      +
📱 Mobile Camera Vision
      +
🗺️ Smart Route Optimization
      +
🚨 Emergency Management
      +
🛡️ AI-Assisted Security
      =
🛕 DivineSphere
```

---

# 📌 Project Vision

> ### **“Making every pilgrimage safer, smarter, and more seamless through Artificial Intelligence.”**

DivineSphere aims to transform pilgrimage management from **reactive monitoring to proactive, AI-driven decision making**.

---

# 👨‍💻 Project

### DivineSphere — AI-Driven Pilgrimage Management System

**Built with:**
`AI` • `Machine Learning` • `Computer Vision` • `GIS` • `Predictive Analytics` • `Web Technologies`

---

## ⭐ Support

If you find **DivineSphere** interesting or useful, consider giving the repository a ⭐ **Star** and sharing the project.

---

### 📜 License

This project is developed for **educational, research, and prototype purposes**.
