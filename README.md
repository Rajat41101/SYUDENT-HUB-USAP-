# 🎓 Unified Student Academic Portal (USAP)

> A centralized Student Resource Portal designed to bridge the gap between classroom teaching and digital accessibility.

## 📖 About The Project
Website Link- https://rajat41101.github.io/SYUDENT-HUB-USAP-/

In the current academic environment, students often face challenges in organizing physical notes and accessing updated class information. The **Unified Student Academic Portal (USAP)** is an integrated web-based application where students can register, log in, and manage their academic workflow seamlessly. 

The primary objective is to provide a platform that allows users to view class details, download PDF books, and upload peer-reviewed notes. By digitizing these resources, USAP reduces the manual effort of distributing materials, improves the accuracy of information sharing, and enhances study efficiency for all students.

### ✨ Key Features & Role-Based Access Control (RBAC)

To maintain the quality of the study materials, the portal features a strict role-based access system:

* **👤 General Student:** * Create an account and log in securely.
    * View class schedules and details.
    * Browse and download PDF books, study materials, and peer-reviewed notes.
* **✍️ Verified Contributor:**
    * *Criteria:* A special role granted to students who maintain clean, correct notes and possess exceptionally good handwriting.
    * *Permissions:* Includes all General Student features, plus the exclusive ability to **upload** new peer-reviewed notes and documents to the platform.
* **🛡️ Administrator:**
    * Manage user accounts and oversee platform activity.
    * Approve or moderate uploaded study materials.
    * Manually evaluate and assign the "Verified Contributor" role to qualifying students.

## 🛠️ Built With

This project is built using a modern Full-Stack web development architecture:

**Frontend:**
* HTML5
* CSS3
* JavaScript (ES6+)

**Backend & Database:**
* Node.js with Express.js
* MongoDB (Mongoose for schema modeling)

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing.

### Prerequisites

Make sure you have the following installed on your machine:
* [Node.js](https://nodejs.org/) (v14 or higher)
* [MongoDB](https://www.mongodb.com/try/download/community) (Local instance or MongoDB Atlas URI)

### Installation

1.  **Clone the repository**
    ```sh
    git clone [https://github.com/your-username/usap-portal.git](https://github.com/your-username/usap-portal.git)
    ```
2.  **Navigate to the project directory**
    ```sh
    cd usap-portal
    ```
3.  **Install NPM packages**
    ```sh
    npm install
    ```
4.  **Set up environment variables**
    Create a `.env` file in the root directory and add your configuration details:
    ```env
    PORT=3000
    MONGODB_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret_key
    ```
5.  **Start the development server**
    ```sh
    npm start
    ```
    The application will be running at `http://localhost:3000`.

## 🔮 Future Enhancements

As the project scales, the following features are planned for future updates:
* Automated student attendance tracking.
* Integrated discussion forums for real-time peer-to-peer doubt solving.
* Notification system for newly uploaded notes and announcements.

## 👥 Submitted By

This project was developed by:
* **Rajat Baroi** (Roll No: 72324504)
* **Bhabesh Das** (Roll No: 72324520)
* **Subhashish Palei** (Roll No: 72324522)

---
*Built for the students, by the students.*