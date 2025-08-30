# 📊 **CAAD Information Management System - Admin Dashboard**

Welcome to the **CAAD Information Management System - Admin Dashboard**, a React-powered administrative interface designed for managing employee-related data and HR operations. This system integrates various modules, from proforma management to late-sitting and internship tracking, with a robust Django backend.

---

## 🚀 **Project Structure**

* **`caad_hr_admin/`**: React-based admin dashboard (frontend)
* **`caad_hr_backend/`**: Django backend API and services
* **`caad_hr_frontend/`**: Additional React components (if applicable)

---

## ✨ **Features**

### **Admin Dashboard Features:**

* 🔑 **User Authentication & Account Management**: Secure login and user management.
* 📊 **HR Analytics Dashboard**: Real-time statistics and HR insights.
* 📑 **Proforma Management**: Manage documents (Accommodation, Clearance, Evaluation, etc.).
* 🆔 **Identity Card & Billing Management**: Admin tools for managing employee IDs and billing details.
* ⏱️ **Late Sitting & Internship Tracking**: Track employee work hours and internship status.

### **User Dashboard Features:**

* 📝 **Profile Management**: View and edit personal details.
* 📚 **Registration and Document Management**: Access documents for accommodation, extension, etc.
* 🏢 **Transport Management**: View and update transport details.
* 📊 **Generate Reports**: Customizable reports for employee data and performance.

---

## 🖼️ **Project Screenshots**

Here are some key screenshots showcasing the functionality of both the **Admin** and **User Dashboards**:

### **Admin Dashboard:**

* **Admin Dashboard**:
  ![Admin Dashboard](CAAD%20Information%20Management%20System/Dashboard.png)

  * The **Admin Dashboard** gives an overview of all HR operations and system performance.

* **Clearance Management**:
  ![Clearance Management](CAAD%20Information%20Management%20System/clearnce.png)

  * Manage employee clearance processes through the admin interface.

* **Evaluation Management**:
  ![Evaluation Management](CAAD%20Information%20Management%20System/evaluation.png)

  * Admin tools for managing employee evaluations and feedback.

* **Extension Management**:
  ![Extension Management](CAAD%20Information%20Management%20System/extension.png)

  * Handle extension requests and approvals.

* **Generate Report**:
  ![Generate Report](CAAD%20Information%20Management%20System/GENERATE%20REport%2C%20seprate%20module.png)

  * Admins can generate custom reports for HR data.

* **Identity Card Management**:
  ![Identity Card](CAAD%20Information%20Management%20System/identity%20card.png)

  * Admin interface for managing and issuing identity cards to employees.

* **Late Sitting Management**:
  ![Late Sitting](CAAD%20Information%20Management%20System/late%20sitting.png)

  * Track employee late sittings and manage attendance.

---

### **User Dashboard:**

* **User Profile**:
  ![User Profile](CAAD%20Information%20Management%20System/profile.png)

  * The **User Profile** section allows employees to view and edit their personal information.

* **User Registration**:
  ![User Registration](CAAD%20Information%20Management%20System/registrtion.png)

  * Users can register and submit their required documentation.

* **Sign In/Sign Up**:
  ![Sign In/Sign Up](CAAD%20Information%20Management%20System/sign%20in-up.png)

  * The sign-in and sign-up pages for user authentication.

* **Transport Management**:
  ![Transport Management](CAAD%20Information%20Management%20System/transport.png)

  * Manage transport details directly from the user dashboard.

---

## ⚡ **Getting Started**

### **Prerequisites**

Before you begin, ensure you have the following installed:

* **Node.js** (for frontend)
* **Python 3.x** (for backend)
* **npm** or **yarn** (for frontend dependencies)
* **pip** (for Python package manager)

### **Installation**

#### 1. **Frontend (caad\_hr\_admin)**

First, navigate to the **caad\_hr\_admin** directory, install the dependencies, and start the frontend:

```bash
cd caad_hr_admin
npm install
npm start
```

#### 2. **Backend (caad\_hr\_backend)**

Next, navigate to the **caad\_hr\_backend** directory, install the backend dependencies, run migrations, and start the server:

```bash
cd caad_hr_backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

---

## 🌍 **Usage**

* Visit the **frontend** at `http://localhost:3000` (React default port).
* Access the **backend API** at `http://localhost:8000` (Django default port).

---

## 🗂️ **Folder Structure**

* **`src/components/`**: React components for the dashboard.
* **`src/views/`**: Main views/pages for the application.
* **`src/router/`**: React Router configuration for navigation.
* **`src/store/`**: State management (using React Context or Redux).
* **`caad_api/`**: Django app for the backend API.

---

## 🤝 **Contributing**

Contributions are always welcome! To suggest a major change, please open an issue first to discuss it with the team.

---

## 📝 **License**

This project is licensed under the [MIT License](LICENSE).

---

## 👥 **Authors/Superviosr**

* **adeelurrahman**
* **Contributors welcome!**

---

