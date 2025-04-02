# VTube – Over the Top (OTT) Platform

## 📌 Project Description
VTube is a full-stack OTT (Over the Top) platform that enables users to browse, upload, and interact with videos based on their subscription plans. The platform is built using **React** for the frontend, **Node.js** and **Express** for the backend, and **MongoDB** for database management, ensuring a seamless and scalable video streaming experience.

### 🔹 Key Integrations:
- **Cloudinary** for cloud-based video storage.
- **Razorpay** for secure payment processing and subscription management (Gold, Silver, Bronze plans).
- **JWT & Bcrypt** for authentication and authorization.
- **OTP verification** for secure account access.
- **NodeMailer** for email notifications, including OTP verification, account updates, and transactional emails.

## 🚀 Key Features
✅ **User Authentication & Authorization** (JWT, Bcrypt, OTP verification)  
✅ **Secure Subscription-Based Access** with Razorpay payment integration  
✅ **Cloud-Based Video Storage** using Cloudinary  
✅ **Video Uploading, Browsing & Interaction** (Likes & Comments)  
✅ **Email Notifications** via NodeMailer (OTP verification & account updates)  
✅ **Role-Based Access Control** for secure content management  
✅ **MVC Architecture** for scalability and maintainability  

---

## 🛠 Tech Stack

### 🎨 Frontend:
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

### 🏗 Backend:
[![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)

### 🗄 Database:
[![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)

### ☁ Cloud Storage:
[![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)](https://cloudinary.com/)

### 💳 Payment Integration:
[![Razorpay](https://img.shields.io/badge/Razorpay-007AFF?style=for-the-badge&logo=razorpay&logoColor=white)](https://razorpay.com/)

### 🔑 Authentication & Security:
[![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)](https://jwt.io/)
[![Bcrypt](https://img.shields.io/badge/Bcrypt-4A90E2?style=for-the-badge&logoColor=white)](https://www.npmjs.com/package/bcrypt)

---

## 📜 Installation & Setup
### Prerequisites:
- **Node.js** installed
- **MongoDB** setup (local or cloud-based)
- **Razorpay Account** for payment gateway
- **Cloudinary Account** for video storage

### Steps:
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/VTube.git
   cd VTube
   ```

2. **Install Dependencies:**
   ```bash
   npm install   # Install backend dependencies
   cd client && npm install   # Install frontend dependencies
   ```

3. **Set Up Environment Variables:**
   - Create a `.env` file in the root directory.
   - Add the required credentials (MongoDB URI, JWT Secret, Razorpay keys, Cloudinary keys, etc.)

4. **Run the Backend Server:**
   ```bash
   npm start
   ```

5. **Run the Frontend:**
   ```bash
   cd client
   npm start
   ```

6. **Access the Application:**
   - Visit `http://localhost:3000` in your browser.

---

## 🎯 Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to improve the platform.

---

## 📧 Contact
For any queries or suggestions, feel free to reach out:
- **Email:** your.email@example.com
- **GitHub:** [yourusername](https://github.com/yourusername)

---

## 📜 License
This project is licensed under the **MIT License**. Feel free to modify and use it as needed!

