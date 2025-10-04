# 🌊 Sahaara – A Unified Disaster Response Platform

---

## 🏷️ Team Information
- **Team Name:** Just-us  
- **Team ID:** T054  

---

## 👥 Team Members & Roles
- **Prince** – Frontend & Backend Development  
- **Gurvardaan Singh** – Frontend & Backend Development  
- **Varinder Sidhu** – UI/UX Design  
- **Ajay Kumar Yadav** – Presentation & Coordination  

---

## ❗ Problem Statement
Disasters such as floods, droughts, and earthquakes create massive disruption.  
Current relief operations are often:
- Fragmented, delayed, and uncoordinated  
- Communities struggle to report urgent needs in real time  
- NGOs work in silos, leading to duplication of efforts  
- Donors lack transparency on how contributions are utilized  

---

## 🛠️ Tech Stack
- **Frontend:** React / Next.js  
- **Backend:** Node.js / Express  
- **Database:** MongoDB / PostgreSQL  
- **Mapping & Forecast APIs:** OpenStreetMap, Weather/Disaster APIs  
- **Deployment:** Vercel / Docker (optional)  
- **Package Manager:** pnpm  

---

## 💡 Our Solution – **Sahaara**
Sahaara is a **centralized community-based disaster response platform** that bridges the gap between affected people, NGOs, volunteers, donors, and authorities.

### Key Features:
- **Community Side**  
  - Post urgent needs (food, water, medicine, shelter, volunteers) with **location + timestamp**  
  - Offline-first support using **SMS, USSD, and IVR hotlines**  
  - Mobile app syncs once connectivity is restored  

- **NGO Side (Secured with Authentication)**  
  - Dashboard showing community needs, aid storage, survey data, and meeting notes  
  - Collaborative board for NGOs to coordinate actions  
  - **AI-powered verification** to remove duplicate/spam requests  

- **Advanced Capabilities**  
  - Predictive heatmaps using **weather forecasts + GIS data** to pre-position aid  
  - Cross-NGO volunteer registry with **skill-based pull system**  
  - Donation tracker providing **transparent updates** to donors  

- **Future Roadmap**  
  - Integration with State Disaster Management Authorities  
  - AI + satellite-driven predictive planning  
  - Scaling across multiple geographies and disaster types  


---

## 🚀 How to Run the Project

### Prerequisites:
- Install **pnpm** first (for Linux/MacOS):  
  ```bash
  sudo npm install -g pnpm
  ```
  
- Install **pnpm** first (for Windows):  
  ```bash
  npm install -g pnpm
  ```
  
- Run command:
```bash
curl -fsSL https://get.pnpm.io/install.sh | sh -
```

- Then run this:
  ```bash
  pnpm i
  ```
  
- Lastly, run this:
  ```bash
  pnpm dev
  ```

  ---

  ## Limitations:

This project is Internet dependent (but can be resolve in future versions). With future development → Offline-first system with SMS/IVR/offline apps to reduce internet dependency, making it much more disaster-resilient.
   
