# 🌾 Fertilizer Management System

A role-based web application designed to digitize and streamline fertilizer distribution across rural and semi-urban regions. The system supports **officers** and **farmers** with separate dashboards for managing stock, requests, and distribution workflows.

## 🔧 Tech Stack

- **Backend:** Flask (Python)
- **Frontend:** HTML, CSS, Bootstrap
- **Database:** MySQL (normalized to 3NF)
- **Authentication:** Secure login for officers and farmers
- **ORM/Querying:** Raw SQL queries with input validation

---

## 🎯 Features

### 👨‍🌾 Farmer Dashboard
- Submit fertilizer requests
- Track request status
- View announcements and notifications

### 🧑‍💼 Officer Dashboard
- Manage fertilizer stock
- Approve or reject farmer requests
- Add announcements
- Monitor distribution records

### 🗃️ Database Design
- ER-modeled and normalized to **3NF**
- Role-based access control
- Tables for users, requests, stock, announcements, and logs

---

## 📸 Screenshots

> Add screenshots here showing both dashboards  
> *(e.g. login page, officer panel, farmer request form, stock view)*

---

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- MySQL Server
- pip (Python package installer)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fertilizer-management-system.git
   cd fertilizer-management-system
