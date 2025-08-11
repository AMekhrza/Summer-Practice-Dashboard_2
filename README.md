# 📊 MERN React Admin Dashboard

A full-stack admin dashboard built with **MERN Stack** (MongoDB, Express.js, React, Node.js) featuring comprehensive data visualization, user management, and analytics.

## ✨ Features

### 📈 **Analytics & Visualizations**
- Interactive charts with Nivo
- Sales performance tracking
- Geographic data visualization
- Revenue breakdown analysis

### 👥 **User Management**
- User dashboard and profiles
- Customer management system
- Admin panel with role-based access
- Performance tracking

### 🛍️ **E-commerce Features**
- Product catalog management
- Transaction monitoring
- Sales analytics
- Inventory tracking

### 🎨 **Modern UI/UX**
- Material-UI components
- Responsive design
- Dark/Light theme support
- Professional admin interface

## 🚀 Quick Start

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/AMekhrza/MERN-React-Admin-Dashboard_2.git
   cd MERN-React-Admin-Dashboard-main
   ```

2. **Install server dependencies**
   ```bash
   cd server
   npm install
   ```

3. **Install client dependencies**
   ```bash
   cd ../client
   npm install
   ```

4. **Environment Setup**
   
   Create `.env` file in the server directory:
   ```env
   NODE_ENV=development
   PORT=5001
   MONGO_URL=mongodb://localhost:27017/admin-dashboard
   ```

5. **Start the application**

   **Server (Backend):**
   ```bash
   cd server
   npm start
   ```

   **Client (Frontend):**
   ```bash
   cd client
   npm start
   ```

6. **Access the application**
   - Frontend: `http://localhost:3000`
   - Backend API: `http://localhost:5001`

## 📁 Project Structure

```
MERN-React-Admin-Dashboard-main/
├── client/                 # React frontend
│   ├── public/
│   ├── src/
│   │   ├── components/     # Reusable components
│   │   ├── scenes/         # Page components
│   │   ├── state/          # Redux store & API
│   │   └── assets/         # Images and static files
│   └── package.json
├── server/                 # Node.js backend
│   ├── src/
│   │   ├── controllers/    # Route controllers
│   │   ├── models/         # Database models
│   │   ├── routes/         # API routes
│   │   ├── data/           # Sample data
│   │   └── middleware/     # Custom middleware
│   └── package.json
└── README.md
```

## 🛠️ Tech Stack

### Frontend
- **React 18** - UI library
- **Material-UI (MUI)** - Component library
- **Redux Toolkit** - State management
- **Nivo** - Data visualization
- **React Router** - Navigation

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **MongoDB** - Database
- **Mongoose** - ODM

## 📊 API Endpoints

### General
- `GET /general/user/:id` - Get user information
- `GET /general/dashboard` - Get dashboard stats

### Client
- `GET /client/products` - Get all products
- `GET /client/customers` - Get customers list
- `GET /client/transactions` - Get transactions
- `GET /client/geography` - Get geographic data

### Sales
- `GET /sales/overview` - Sales overview
- `GET /sales/daily` - Daily sales data
- `GET /sales/monthly` - Monthly sales data
- `GET /sales/breakdown` - Sales breakdown

### Management
- `GET /management/admins` - Get admin users
- `GET /management/performance/:id` - User performance

## 🎨 Customization

### Themes
The application supports custom theming through Material-UI. Edit `src/theme.js` to customize colors and typography.

### Components
All components are modular and can be easily customized or extended.

## 🔧 Development

### Available Scripts

**Client:**
- `npm start` - Start development server
- `npm build` - Build for production
- `npm test` - Run tests

**Server:**
- `npm start` - Start server
- `npm run dev` - Start with nodemon

