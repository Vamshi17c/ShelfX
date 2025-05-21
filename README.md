# ShelfX - Book Rental and Sales Platform

ShelfX is a dynamic platform designed to connect book enthusiasts for renting and selling books. It empowers users to upload, rent, and purchase books seamlessly.Through this website seller and buyer can contact each other.

## Features

- **Book Management**: Sellers can upload books for sale or rent.
- **Request Handling**: Buyers can request books from sellers, with options to accept or decline requests.
- **User Authentication**: Secure login for sellers, buyers, and admins.
- **Responsive Design**: Mobile-friendly UI for smooth user experience.

---

## Tech Stack

- **Frontend**: ReactJS, Vite, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MySQL
- **Languages**: JavaScript

---

## Installation

### Prerequisites
Ensure the following are installed:
- Node.js (v16+)
- MySQL
- Git

### Steps to run 

1. **Clone the repository**
   ```bash
   git clone https://github.com/Neeraj3737/ShelfX.git
   cd shelfx
   ```

2. **Build and start the containers**
   ```bash
   docker-compose up -d --build
   ```

3. **Access the application**
   - Frontend: http://localhost:80
   - Backend API: https://localhost:5000
   - Swagger API Documentation: https://localhost:5000/api-docs
  
     ## Environment Variables

The application uses environment variables defined in the `.env` file. Make sure this file exists with the following variables:

```
EMAIL_USR=your-email@example.com
APP_PASS=your-app-password
CLOUD_NAME=your-cloudinary-name
API_KEY=your-api-key
API_SECRET=your-api-secret

## Stopping the Application

To stop the containers:

```bash
docker-compose down
```

To stop and remove volumes (this will delete the database data):

```bash
docker-compose down -v
```
## 🧑‍💻 Team Contributions

This project was a team effort carried out by 8 dedicated contributors. Each member handled specific responsibilities to ensure a modular, maintainable, and feature-complete application. Below is a detailed breakdown of each member’s role and contributions:

---

### 🔹 G.Nilesh(S20220010072)

*Primary Focus:* Seller Dashboard

- Developed the complete seller module including UI and backend logic.
- Implemented book upload functionality with validation and file handling.
- Enabled viewing of uploaded books with filtering and real-time updates.
- Managed history tracking for books sold or rented by the seller.
- Built full CRUD (Create, Read, Update, Delete) operations for seller management.
- Integrated notification system from seller to buyer.
- Developed secure login and signup pages for users.
---

### 🔹 K.Neeraj Kumar(S20220010116) 

*Primary Focus:* Buyer Dashboard

- Designed and implemented the buyer interface with dynamic data rendering.
- Handled book retrieval logic from the backend database.
- Implemented sorting of books based on user's pincode.
- Created functionality to maintain purchase history of buyers.
- Built full CRUD operations for buyer profile management.
- Enabled notifications from buyers to sellers for interaction or queries.
- Developed secure login and signup pages for admins.
- Integration of all codes.

---

### 🔹 K. Harsha(S20220010111) 

*Primary Focus:* Admin Controls – Buyers and Statistics

- Handled CRUD operations for buyer data through the admin dashboard.
- Developed logic to calculate and display system-wide statistics such as:
  - Revenue generated
  - Number of books sold
  - Activity reports for admin overview
---

### 🔹 R.Sai Vikas(S20220010185) 

*Primary Focus:* Chatbot (WebSocket Communication)

- Built a real-time chatbot system using WebSocket protocol.
- Enabled seamless communication between buyers and sellers inside the platform.
- Ensured message synchronization and responsive UI during live chats.

---

### 🔹 P.Sujith Kumar(S20220010214) 

*Primary Focus:* Admin Controls – Books and Sellers

- Developed admin-level CRUD operations for managing book records.
- Implemented control panel functionalities for handling seller accounts.
- Designed reusable and responsive UI components using *React.js* and *Tailwind CSS*.
---

### 🔹 P. Akshita (S20220010303)

*Primary Focus:* Authentication System

- Integrated role-based access control and route protection.
- Ensured proper session handling and error feedback for authentication events.

---

### 🔹 Pallerla Harshavardhan (S20220010161)

*Primary Focus:* Dockerization

- Dockerized both frontend and backend environments using Docker and Docker Compose.
- Enabled smooth deployment across different systems with uniform configuration.
- Facilitated efficient local and cloud-based development setups.

---

### 🔹 DUPANA GURUMURTHY (S20220010266)

*Primary Focus:* Deployment,and Slides

- Deployed the entire application on *Vercel* for production.
- Created professional slides for project presentation and documentation.

---

