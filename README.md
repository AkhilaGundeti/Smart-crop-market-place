# 🌾 Smart Crop Marketplace

A full-stack web application that connects farmers and buyers, enabling seamless crop trading, order management, and analytics.

---

## 🚀 Features

- 👨‍🌾 Farmer & Buyer Authentication  
- 🌱 Crop Listing & Management  
- 🛒 Order Placement & Tracking  
- ⭐ Reviews & Ratings  
- 📊 Analytics Dashboard  
- 🔐 Secure API with JWT Authentication  

---

## 🛠️ Tech Stack

### Frontend
- React (Vite)  
- Axios  
- React Router  
- Recharts  

### Backend
- Node.js  
- Express.js  
- MongoDB Atlas  
- Mongoose  

### DevOps
- Docker 🐳  
- GitHub Actions (CI/CD)  
- Vercel (Frontend Hosting)  
- Render (Backend Deployment)  

---

## 🌐 Live Application

- **Frontend (Vercel):**  
  https://smart-crop-market-place-akhilas-projects-70c8f50a.vercel.app/

- **Backend (Render):**  
  https://smart-crop-market-place.onrender.com

---

## 📂 Project Structure

```text
Smart-crop-market-place/
│
├── backend/
├── frontend/
├── docker-compose.yml
└── .github/workflows/
```


## ⚙️ Setup Instructions

### 1. Clone Repository

```bash
git clone https://github.com/AkhilaGundeti/Smart-crop-market-place.git
cd Smart-crop-market-place
```
###2. Environment Variables

Backend (backend/.env)

```text
MONGO_URI=your_mongodb_connection_string
```
Frontend (frontend/.env)
```text
VITE_API_URL=https://smart-crop-market-place.onrender.com
```
###3. Run with Docker
```text
docker-compose up --build
```
---

## 🌐 Access Application

- Frontend: http://localhost:4173  
- Backend: http://localhost:5000  

---

##🚀 Deployment

This project follows a modern production architecture:

-Frontend deployed on Vercel
-Backend deployed on Render (Docker-based)
-Database hosted on MongoDB Atlas
---

## 🔄 CI/CD Pipeline

- Automated testing using GitHub Actions  
- Backend tests executed on every push  
- Frontend build validation  

---

## 💡 Future Enhancements

- Payment Integration  
- Real-time notifications  
- Mobile app version  

---

## 👩‍💻 Author

**Akhila Gundeti**

---

## ⭐ Acknowledgements

This project was built as part of learning full-stack development, DevOps, Docker, and cloud deployment practices.
