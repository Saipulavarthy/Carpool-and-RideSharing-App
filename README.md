# Carpool-and-RideSharing-App

*A student-only carpool and ride-sharing platform for sustainable transportation*

RideShare UMass is a community-driven web platform that helps **UMass students coordinate carpools** to common destinations such as **Hadley, Boston, and Logan Airport**.  
The platform focuses on **sustainability, safety, and accessibility**, making it easier for students to share rides, reduce travel costs, and lower carbon emissions.

📌 Status

🚧 Active development – early stage

🤝 Contributing

This project is currently under active development.
Contribution guidelines will be added as the codebase stabilizes.

---

## 🎯 Motivation
UMass students frequently need off-campus transportation for groceries, internships, airports, and weekend travel. Existing solutions (group chats, spreadsheets, social media posts) are unstructured, unsafe, and inefficient.

RideShare UMass provides:
- a **verified, student-only** environment
- structured ride creation and matching
- privacy-first communication
- measurable sustainability impact

---

## ✨ Core Features (MVP)
- **UMass-only authentication** using `@umass.edu` email verification  
- **Ride creation** (origin, destination, time, available seats)  
- **Ride discovery & matching** with time-window filtering  
- **Join requests** with driver approval (accept/reject)  
- **Seat management** with automatic ride locking when full  
- **In-app messaging** after ride confirmation  
- **Privacy-first design** (contact info hidden until acceptance)  
- **Sustainability metrics** (estimated CO₂ savings)

---

## 🚫 Non-Goals (MVP)
- In-app payments (manual cost splitting only)
- Third-party drivers (Uber / Lyft excluded)
- Real-time GPS tracking (planned for Phase 2)

---

## 👥 User Roles
- **Rider (Student)** – search and request rides  
- **Driver (Student)** – offer rides and manage passengers  
- **Admin / Moderator** – verify users and handle reports  
- **Sustainability Viewer (Optional)** – view aggregate impact metrics

## 🧪 Planned Tech Stack
### Frontend
- React.js or Next.js  
- Tailwind CSS  
- REST API integration  

### Backend
- FastAPI (Python) or Express (Node.js)  
- PostgreSQL  
- JWT-based authentication  

### Infrastructure
- Docker (local development)
- Vercel / AWS / Heroku (deployment)

---

## 🔐 Environment Variables
This project uses environment variables for configuration.

**Do not commit `.env`.**  
Instead, copy the template:
```bash
cp .env.example .env
