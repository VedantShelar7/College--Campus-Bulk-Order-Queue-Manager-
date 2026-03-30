# 🖨️ PrintShop – Campus Bulk Order & Queue Manager

![PrintShop Banner](sandbox:/mnt/data/65cf3485-524c-47e6-b5b3-135a1480fd58.png)

---

## 🚀 Overview
PrintShop is a smart web-based platform designed to simplify bulk printing in college environments. It eliminates long queues, manual coordination, and payment confusion by providing a centralized system for order management, payments, and real-time tracking.

---

## 💡 Problem Statement
College print shops often face:
- Overcrowding during submissions
- Manual cash handling issues  
- No proper queue or order tracking  
- Fake or unverified payment proofs  

---

## ✅ Solution
PrintShop digitizes the entire workflow:
- Students place bulk print orders via polls  
- Payments handled via demo gateway or QR  
- Screenshot proof upload system  
- Shopkeeper dashboard for full control  
- AI-based verification for payment authenticity  

---

## ✨ Key Features

### 👨‍🎓 Student Side
- Join print polls created by CR  
- Pay via:
  - Demo Payment (simulated)
  - QR Code (real UPI flow)
- Upload payment screenshot  
- Real-time status tracking  

---

### 🧑‍💼 Shopkeeper / CR Dashboard
- Create and manage print polls  
- View all orders in one place  
- Payment Tracker & Transaction History  
- AI Verification Panel  
- Real-time dashboard updates  

---

### 💳 Payment System
- Razorpay-inspired UI (fake gateway)  
- QR-based real payment flow  
- Screenshot upload with preview  
- Centralized payment data system  

---

### 🤖 AI-Based Verification (Simulated)
- "Verify with AI" feature in dashboard  
- Checks:
  - Upload timing  
  - Duplicate images  
  - Basic validation  
- Outputs:
  - ✅ Verified  
  - ⚠ Suspicious  
  - ❌ Rejected  

---

### 📊 Smart Dashboard Analytics
- Total Orders  
- Verified Payments  
- Pending / Rejected Payments  
- Total Revenue  
- Live updates across all sections  

---

### 🔐 Authentication System
- Email & password login/signup  
- Smart email validation (no fake emails like abc/xyz/test)  
- Google Sign-In integration  
- Session management using localStorage  

---

### 🎨 UI/UX Highlights
- Dark, professional dashboard theme  
- Crisp bordered cards and sections  
- Smooth animations and transitions  
- Razorpay-style payment interface  
- Fully responsive design  

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **Storage:** localStorage (JSON-based data handling)  
- **Authentication:** Custom + Google OAuth  
- **UI Design:** Modern dark theme with animations  

---

## 🧠 How It Works

1. CR creates a print poll  
2. Students join and make payment  
3. Upload payment proof (if QR used)  
4. Data is stored centrally  
5. Shopkeeper verifies payments using AI  
6. Dashboard updates in real-time  
7. Orders are processed efficiently  

---

## 🔥 Unique Selling Points

- Hybrid payment system (demo + real QR)  
- AI-based verification (innovative feature)  
- Real-time synchronized dashboard  
- Smart email validation system  
- Clean and professional UI  

---

## 📈 Future Improvements

- Real payment gateway integration (Razorpay API)  
- OCR-based screenshot verification  
- Notification system (email/SMS)  
- Database integration (MongoDB/MySQL)  
- Mobile app version  

---

## 🧪 Demo Note
This project uses a **simulated payment system** for demonstration purposes.  
No real transactions are processed unless QR is used manually.

---

## 👨‍💻 Team & Hackathon
Built as part of a hackathon project to solve real-world campus inefficiencies in print management.

---

## ⭐ Final Thought
> PrintShop transforms chaotic college printing into a smooth, intelligent, and digital-first experience.
