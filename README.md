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

---

## ⚙️ Setup Instructions

### 1. Clone Repository

```bash
git clone https://github.com/AkhilaGundeti/Smart-crop-market-place.git
cd Smart-crop-market-place
```
###2. Environment Variables

Create a .env file inside backend and add:

```text
MONGO_URI=your_mongodb_connection_string
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

This project was built as part of learning full-stack development, DevOps, and deployment practices.
