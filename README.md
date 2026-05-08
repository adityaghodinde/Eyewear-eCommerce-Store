# Eyewear-eCommerce-Store
The Eyewear eCommerce Store is a modern full-stack web application developed to provide customers with a seamless online shopping experience for premium eyewear products.
# SpectraVista eCommerce Application

A premium, modern, and responsive full-stack eCommerce web application built with React, Node.js, Express, and MongoDB.

## Features
- **Frontend**: Vite + React, React Router v6, Lucide Icons, Vanilla CSS (Premium Design System).
- **Backend**: Express.js REST API.
- **Database**: Mongoose Schemas ready for MongoDB integration.
- **Pages Included**: Home, Shop All, Product Details, Cart, Login.
- **Responsive**: Fully responsive design for mobile, tablet, and desktop.
- **Mock Data**: Includes realistic mock data for immediate preview without needing a database connection.

## Project Structure
- `/frontend` - Vite React Application
- `/backend` - Node.js Express Server

## Getting Started

### 1. Run the Backend
Navigate to the backend directory and start the server:
```bash
cd backend
npm install
node server.js
```
The server will start on `http://localhost:5000` serving the mock product data via the `/api/products` endpoint.

### 2. Run the Frontend
Open a new terminal, navigate to the frontend directory, and start the Vite dev server:
```bash
cd frontend
npm install
npm run dev
```
The application will be accessible at `http://localhost:5173`.

### 3. Database Setup (Optional for Demo)
To connect to a real MongoDB instance:
1. Inside `/backend/server.js`, import and configure mongoose:
   `mongoose.connect('your_mongodb_uri')`
2. Update the routes to query from the Mongoose models instead of the mock `data/products.js` file. 
