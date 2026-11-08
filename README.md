# 🍽️ Smart Hostel Mess Management System

A web-based application designed to simplify and automate hostel mess operations through digital meal booking, menu management, student feedback, and kitchen management.

## 📌 Project Overview

The **Smart Hostel Mess Management System** is developed to overcome the challenges of traditional hostel mess management, such as manual meal booking, food wastage, menu confusion, and inefficient communication between students and mess staff.

The application provides separate dashboards for Students, Administrators, and Mess Staff, making hostel food management easier, faster, and more organized.

## 🎯 Objectives

- Digitize hostel mess operations.
- Reduce food wastage through online meal booking.
- Simplify daily menu management.
- Improve communication between students and mess staff.
- Manage complaints and student feedback.
- Monitor meal preparation and booking details.

## ✨ Key Features

### 👨‍🎓 Student Dashboard
- View daily and upcoming meal menus.
- Book and cancel meals.
- Submit complaints.
- Provide ratings and feedback.
- Receive notifications and announcements.
- Check meal preparation status.

### 👨‍💼 Admin Dashboard
- View total student details.
- Monitor meal bookings.
- Manage hostel menus.
- View and manage student complaints.
- Publish announcements.
- Monitor student feedback and mess analytics.

### 👨‍🍳 Mess Staff Dashboard
- View meal booking counts.
- Manage breakfast, lunch, and dinner menus.
- Monitor meal preparation status.
- Update food preparation information.

## 🛠️ Technologies Used

| Category | Technologies |
|---|---|
| Frontend | React.js, TypeScript |
| Styling | CSS, Tailwind CSS |
| Backend | Python, Flask |
| API | REST API |
| Build Tool | Vite |
| Icons | Lucide React |
| Version Control | Git, GitHub |

## 🏗️ System Architecture

```text
          User Interface
                |
       React.js + TypeScript
                |
          REST API Calls
                |
          Python Flask
                |
        Backend Data Handling
                |
       Student / Admin / Staff
```

## 📂 Project Structure

```text
Smart-Hostel-Mess-Management/
│
├── src/
│   ├── components/
│   │   ├── AdminDashboard.tsx
│   │   ├── StudentDashboard.tsx
│   │   ├── StaffDashboard.tsx
│   │   └── modals/
│   │
│   ├── context/
│   ├── data/
│   ├── services/
│   ├── App.tsx
│   ├── main.tsx
│   └── index.css
│
├── app.py
├── package.json
├── requirements.txt
├── index.html
├── vite.config.ts
├── tsconfig.json
├── .env.example
├── .gitignore
└── README.md
```

## ⚙️ Installation and Execution

### Prerequisites

- Node.js and npm
- Python 3
- Git

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/Smart-Hostel-Mess-Management.git
```

### Step 2: Open the Project

```bash
cd Smart-Hostel-Mess-Management
```

### Step 3: Install Frontend Dependencies

```bash
npm install
```

### Step 4: Install Backend Dependencies

```bash
python -m venv venv
```

Activate the virtual environment on Windows:

```bash
venv\Scripts\activate
```

Install required packages:

```bash
pip install -r requirements.txt
```

### Step 5: Start the Backend

```bash
python app.py
```

Backend runs at:

`http://localhost:5000`

### Step 6: Start the Frontend

Open another terminal:

```bash
npm run dev
```

Frontend runs at:

`http://localhost:3000`



## 🚀 Future Enhancements

- Integration with a cloud database.
- Secure student authentication using college email IDs.
- Online payment integration.
- AI-based food demand prediction.
- Cloud deployment and scalability.
- Automated notifications for meal bookings.
- Advanced food wastage analysis.


