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

![WhatsApp Image 2025-04-12 at 11 20 44_24c4bf77](https://github.com/user-attachments/assets/b83c4b85-359f-4d64-b88c-5282c9f992b0)
Fig - 1 

![WhatsApp Image 2025-04-12 at 11 21 18_d6deaf28](https://github.com/user-attachments/assets/5100fa41-c487-42b2-81a2-1c54d8f1d139)
Fig - 2

![WhatsApp Image 2025-04-12 at 11 22 10_ca63c357](https://github.com/user-attachments/assets/71509890-51a6-40c4-a133-8ad303683ac7)
Fig - 3



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
