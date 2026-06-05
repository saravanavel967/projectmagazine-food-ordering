# 🍔 Food Ordering Web App (MERN Stack)

## 📖 Introduction

The Food Ordering Web App is a full-stack web application developed using the MERN Stack (MongoDB, Express.js, React.js, and Node.js). The platform enables customers to browse food items, place orders, make secure online payments, and track their orders. An integrated admin dashboard allows administrators to manage menu items, customer orders, and overall system operations efficiently.

---

## ✨ Features

### Customer Features

* User Registration and Login
* JWT-based Authentication & Authorization
* Browse Food Menu
* Search and Filter Food Items
* Add/Remove Items from Cart
* Place Orders Online
* Secure Stripe Payment Integration
* Order History and Tracking
* Responsive User Interface

### Admin Features

* Admin Dashboard
* Add New Food Items
* Update Food Details
* Delete Food Items
* Manage Customer Orders
* Update Order Status

---

## 🛠️ Technologies Used

### Frontend

* React.js
* React Router
* React Context API
* CSS3

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### Authentication

* JSON Web Tokens (JWT)

### Payment Gateway

* Stripe

### Version Control

* Git & GitHub

---

## 📂 Project Structure

```
Food-Ordering-System/
│
├── frontend/
│   ├── src/
│   └── public/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── middleware/
│
├── admin/
│   ├── src/
│   └── public/
│
└── README.md
```

---

## ⚙️ Installation

### Prerequisites

* Node.js
* MongoDB
* Git

### Clone Repository

```bash
git clone <repository-url>
cd Food-Ordering-System
```

### Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file:

```env
JWT_SECRET=your_secret_key
STRIPE_SECRET_KEY=your_stripe_secret_key
MONGODB_URI=your_mongodb_connection_string
```

Run Backend:

```bash
npm run server
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

### Admin Panel Setup

```bash
cd admin
npm install
npm start
```

---

## 🚀 Usage

1. Open Customer Application:

   ```
   http://localhost:5173
   ```

2. Open Admin Dashboard:

   ```
   http://localhost:5174
   ```

3. Register/Login.

4. Browse available food items.

5. Add items to cart.

6. Place orders securely through Stripe.

7. Track order status.

8. Admin can manage menu items and customer orders.

---

## 📸 Screenshots

### Home Page

<img width="1348" height="588" alt="image" src="https://github.com/user-attachments/assets/e4b60e5a-bda3-406e-86cd-8a8bbff708dd" />
<img width="1353" height="595" alt="image" src="https://github.com/user-attachments/assets/6fc576c5-a755-400b-bcad-e4d64f473e04" />
<img width="1349" height="596" alt="image" src="https://github.com/user-attachments/assets/beab77f6-523f-44a7-9e4f-781645bd7447" />

### Food Menu

<img width="1351" height="613" alt="image" src="https://github.com/user-attachments/assets/4120ffc5-f631-4799-b533-7ecb62ac325f" />
<img width="1345" height="611" alt="image" src="https://github.com/user-attachments/assets/b2d5bb15-688a-4a56-a5ef-dce00493a6c4" />
<img width="1345" height="607" alt="image" src="https://github.com/user-attachments/assets/408f8479-19bd-40b5-a466-81ce95bcf255" />
<img width="1347" height="611" alt="image" src="https://github.com/user-attachments/assets/8b456982-b51d-437e-9847-a68ac3179080" />

### Cart Page

<img width="1350" height="613" alt="image" src="https://github.com/user-attachments/assets/1af7b279-ad90-4838-81cd-16e5a1a441e8" />
<img width="1346" height="611" alt="image" src="https://github.com/user-attachments/assets/708beda5-e1d9-423c-b209-b98beacd305b" />

### Payment Page

<img width="1360" height="613" alt="image" src="https://github.com/user-attachments/assets/a22dfe6b-efc6-47d9-8ade-54e81d75665b" />

---

## 🔌 API Documentation

### Authentication

| Method | Endpoint           | Description   |
| ------ | ------------------ | ------------- |
| POST   | /api/user/register | Register User |
| POST   | /api/user/login    | Login User    |

### Food

| Method | Endpoint       | Description   |
| ------ | -------------- | ------------- |
| GET    | /api/food/list | Get All Foods |
| POST   | /api/food/add  | Add Food Item |

### Orders

| Method | Endpoint              | Description    |
| ------ | --------------------- | -------------- |
| POST   | /api/order/place      | Place Order    |
| POST   | /api/order/verify     | Verify Payment |
| GET    | /api/order/userorders | User Orders    |

---

## 🔒 Security Features

* JWT Authentication
* Password Encryption
* Protected Routes
* Secure Stripe Transactions
* Environment Variable Protection

---

## 🌟 Future Enhancements

* Real-Time Order Tracking
* AI-Based Food Recommendations
* Email Notifications
* Mobile Application
* Multi-Vendor Support

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push the branch.
5. Create a Pull Request.

---

## 📧 Contact

For questions, suggestions, or collaboration opportunities, feel free to contact me.

---

⭐ If you like this project, don't forget to star the repository.


