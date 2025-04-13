
# Status Page Web App 

A full-stack **Status Page** application that allows administrators to manage service statuses, and provides users with a public-facing page to check current system health and get notified via email for changes.

---

## 🔧 Tech Stack

- **Frontend:** React.js, CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB Atlas
- **Email Service:** Nodemailer (SMTP)
- **Deployment:** Netlify (Frontend), Render (Backend)

---

## ✨ Features

### 👩‍💻 Admin Capabilities
- Secure admin login & registration
- Add, update, and delete services
- Change service status (e.g., Operational, Major Outage, Maintenance)
- Automatically notify subscribers when a status is updated

### 🌐 Public User Experience
- View real-time status of all services
- See last updated timestamps
- "Notify Me" feature: users can enter their email and receive updates when a service changes

---

## 📦 Folder Structure

PLIVO-PROJECT/ ├── back-end/ # Express server, API routes, DB models ├── front-end/ # React app │ ├── pages/ # Admin and Public status pages │ └── api/ # Axios API calls ├── .gitignore ├── README.md


---

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/status-page-app.git
cd status-page-app

cd back-end
npm install

Create a .env file inside back-end/:

MONGO_URI=your_mongodb_connection_string
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_app_password


```
### 2. Start the backend:
```bash
node server.js
```
### 3. Setup the Frontend

```bash
cd ../front-end
npm install
npm start





