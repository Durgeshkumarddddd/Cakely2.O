# 🎂 Cakely App

**Cakely App** is a full-stack web application that allows users to browse, order, and purchase cakes online.  
It also provides an **admin dashboard** where administrators can manage cake listings, update product details, and monitor orders.

The application includes **secure authentication and authorization using Passport.js**, including **Google OAuth login**, making the platform secure and user-friendly.

---

# 📌 Project Overview

Cakely App is designed to provide a convenient way for customers to order cakes online.

Users can browse cakes, view detailed information, and place orders, while administrators can manage cake products through a dedicated admin panel.

The project demonstrates **full stack web development using Node.js, Express.js, MongoDB, and EJS** with **secure authentication and role-based authorization**.

---

# 🛠️ Tech Stack

## Backend
- Node.js
- Express.js
- Passport.js (Authentication)
- Google OAuth 2.0
- Express Session

## Frontend
- EJS (Embedded JavaScript Templates)
- HTML
- CSS
- JavaScript
- Bootstrap

## Database
- MongoDB

## Tools
- Git & GitHub
- VS Code
- MongoDB Compass
- npm

---

# 🔐 Authentication & Authorization

The application implements secure login using **Passport.js**.

### Authentication Methods
- Local authentication (email & password)
- Google OAuth authentication

### Authorization
- Role-based access control
- Admin routes protected
- User-specific features protected

### Roles
- **Admin**
- **User**

Admins have permission to manage cakes and orders, while users can browse and purchase cakes.

---

# ⚙️ Key Features

### 👤 User Features
- User Registration & Login
- Google Sign-In
- Browse available cakes
- View cake details
- Add cakes to cart
- Place orders
- Responsive UI

### 👨‍💼 Admin Features
- Admin authentication
- Add new cakes
- Update cake details
- Delete cakes
- Manage cake listings
- Track customer orders

### 🎂 Cake Management
- Display cake images
- Cake price and description
- Category/type of cakes
- Dynamic cake listing

---

# 🏗️ Application Architecture

```
Client (Browser)
       │
       │ HTTP Requests
       ▼
Express.js Server
       │
       ▼
MongoDB Database
```

---

# 📂 Project Structure

```
Cakely_App
│
├── models
│   └── Cake.js
│   └── User.js
│
├── routes
│   ├── adminRoutes.js
│   ├── userRoutes.js
│   └── authRoutes.js
│
├── config
│   └── passport.js
│
├── views
│   ├── layouts
│   ├── admin
│   └── user
│
├── public
│   ├── css
│   ├── js
│   └── images
│
├── app.js
├── package.json
└── README.md
```

---

# ▶️ How to Run the Project

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/Cakely-App.git
```

---

## 2️⃣ Navigate to the Project Folder

```bash
cd Cakely-App
```

---

## 3️⃣ Install Dependencies

```bash
npm install
```

---

## 4️⃣ Configure MongoDB

Make sure MongoDB is running locally.

Example connection:

```
mongodb://localhost:27017/cakelyDB
```

---

## 5️⃣ Configure Google OAuth

Create credentials from **Google Cloud Console** and add:

```
GOOGLE_CLIENT_ID=your_client_id
GOOGLE_CLIENT_SECRET=your_client_secret
```

---

## 6️⃣ Run the Application

```bash
npm start
```

Server will start at:

```
http://localhost:3000
```

---

# 📸 Video
⭐ If you like this project, please give it a **Star on GitHub**!hments/assets/b1cdbfa4-6b84-4cc7-bf51-b439443869ce

You can add screenshots here.

Example:

```
screenshots/homepage.png
screenshots/cake-list.png
screenshots/admin-dashboard.png
screenshots/order-page.png
screenshots/login-page.png
```

---

# 🧠 Learning Outcomes

Through this project, the following concepts were implemented:

- Full Stack Web Development
- Express.js Server Architecture
- MongoDB Database Integration
- Passport.js Authentication
- Google OAuth Login
- Role-Based Authorization
- MVC Project Structure
- CRUD Operations
- EJS Template Rendering
- Responsive UI using Bootstrap

---

# 🚀 Future Improvements

- Online payment gateway integration
- Order tracking system
- Email notifications
- Product reviews and ratings
- Cake customization feature
- Deployment on cloud platforms

---

# 🤝 Contributor

👨‍💻 **Durgeshkumar**

GitHub:  
https://github.com/Durgeshkumarddddd

---



