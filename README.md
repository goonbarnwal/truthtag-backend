# TruthTag Backend 🚀

Backend API for TruthTag, an AI-powered fake job detection system.

## 📌 About Project

TruthTag Backend provides APIs to analyze job details and calculate the risk level of a job posting based on suspicious keywords, email domains, and company information.

## ✨ Features

- Detects suspicious job scam keywords
- Calculates job risk score
- Identifies suspicious email domains
- Provides reasons behind scam detection
- REST API based backend

## 🛠️ Technologies Used

- Python
- Flask
- Flask-CORS
- Requests
- REST API

## 🔗 API Endpoint

### POST /check

### Request Example

```json
{
  "job": "Work from home earn money fast",
  "company": "ABC",
  "email": "abc@gmail.com"
}
```

### Response Example

```json
{
  "status": "🔴 Scam",
  "risk": 50,
  "reasons": [
    "Suspicious keyword found: work from home",
    "Free email domain used"
  ]
}
```

## 🌐 Live Backend

https://truthtag-backend.onrender.com

## 📂 GitHub Repository

https://github.com/goonbarnwal/truthtag-backend
