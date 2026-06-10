# 🩺 GaavSvaasthy
**AI-Powered Rural Healthcare Triage & Management System**

<p align="center">
  <em>An intelligent "Gatekeeper" streamlining healthcare access and optimizing resource allocation for rural communities.</em>
</p>

---

## 📖 Introduction
**GaavSvaasthy** utilizes an AI-powered initial consultation engine to analyze patient symptoms and predict disease criticality in real-time. Built to optimize resource allocation, the platform automatically routes high-risk cases for immediate doctor appointments while decongesting hospital queues by providing instant remedial advice for low-risk patients. 

*Developed by team **Neural Knights** | Lead Developer: **Abhijith Pratheesh***

---

## ⚠️ The Problem
Rural healthcare systems are often overburdened and under-resourced. For instance, the Nabha Civil Hospital serves 173 villages with only 11 out of the required 23 doctors. 

This critical doctor shortage leads to:
* **Severe Bottlenecks:** Extremely long waiting times for basic consultations.
* **Accessibility Barriers:** Patients face long travel distances only to find doctors or medicines unavailable.
* **Infrastructure Strain:** Poor existing infrastructure worsens the overall access to healthcare.
* **Socio-economic Impact:** Ultimately leads to preventable health issues and severe financial stress for rural families.

---

## 💡 The Solution
Our approach bridges the gap between rural patients and medical professionals using an intelligent triage pipeline:

1. **AI Disease Predictor:** An AI doctor steps in to detect illnesses based on reported symptoms, operating with a calibrated **95% target accuracy** to ensure safe and reliable initial assessments.
2. **Automated Triage Routing:** High-risk cases are immediately escalated and referred to a qualified doctor. 
3. **Instant Remedial Action:** Low-risk cases receive AI-prescribed basic medicines along with clear usage instructions and rest advice directly through the portal.
4. **Smart Scheduling:** Digital tokens eliminate physical queues, ensuring a smooth, organized flow of patients.

---

## ✨ Key Features
* 🤖 **AI-Driven Medical Assessment:** Real-time symptom analysis and risk categorization.
* 📱 **Mobile Station for Non-Digital Users:** Accessible interface designed for community health workers or local kiosks.
* 📉 **Queue Decongestion:** Drastically reduces unnecessary hospital visits for minor ailments.
* 👨‍⚕️ **Workload Management:** Supports doctors by filtering out low-risk cases, allowing them to focus on critical patients.
* ⚡ **Faster Access:** Speeds up the healthcare delivery pipeline for entire communities.

---

## 👥 User Personas & Experience

### 1. The Patient
* **Quick Assessment:** Seamlessly assess health risks via the AI triage system.
* **Effortless Booking:** Book advance appointments or receive immediate low-risk prescriptions.
* **Key Experience:** Optimized resources, eliminated physical waiting lines, and reduced unnecessary travel.

### 2. The Doctor
* **Unified Dashboard:** View live, organized appointment schedules.
* **Prioritized Care:** Focus time and energy exclusively on high-risk patients who need urgent intervention.
* **Key Experience:** Live updates for patient flow and manageable, stress-free workload distribution.

---

## 🛠️ Tech Stack
The project is split into a modern web frontend and a robust Python backend.

* **Frontend:** React, Vite, Tailwind CSS
* **Backend:** Python, Flask
* **Database & Auth:** Supabase (PostgreSQL)
* **AI Integration:** Google Gemini Pro

---

## 🚀 Getting Started

### Prerequisites
* Node.js & npm
* Python 3.x
* Supabase Account
* **Gemini API Key** (Obtain your key from [Google AI Studio](https://aistudio.google.com/))

### Installation

1. **Clone the repository:**
```bash
   git clone https://github.com/Abhijith314/GaavSvaasthy.git
   cd GaavSvaasthy
```

2. **Frontend Setup:**
```bash
cd frontend
npm install
npm run dev

```


3. **Backend Setup:**
```bash
cd ../backend
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
pip install -r requirements.txt
```

4. **Environment Variables:**
Create a `.env` file in the `backend` directory with the following variables:
```env
GEMINI_API_KEY=your_api_key_here
```

5. **Run the Backend:**
```bash
flask run
```
## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://www.google.com/search?q=https://github.com/Abhijith314/GaavSvaasthy/issues) if you want to contribute.

---

*Building a healthier tomorrow, one village at a time.*
