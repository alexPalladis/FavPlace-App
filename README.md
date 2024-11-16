# FavPlace App

FavPlace App is a full-stack application built using **React**, **Node.js**, **Express**, and **MongoDB**. This app allows users to create accounts, upload images of their favorite places, and display these locations on an interactive Google Map.

---

## Features

- **User Authentication**: Secure sign-up and log-in functionality.
- **Image Uploads**: Upload images of favorite places and display them.
- **Google Maps Integration**: View locations on an interactive map with markers.
- **Responsive Design**: Fully responsive UI for a seamless experience across devices.
- **RESTful API**: Built with Express and MongoDB to handle all backend operations.

---

## Technologies Used

### Frontend
- **React.js**: For building the user interface.
- **React Router**: For managing navigation.
- **Google Maps API**: For rendering maps and markers.
- **CSS/SCSS**: For styling.

### Backend
- **Node.js**: Runtime environment for the server.
- **Express.js**: Framework for creating the API.
- **MongoDB**: Database to store user data and places.
- **Mongoose**: MongoDB object modeling.

### Authentication
- **JWT (JSON Web Tokens)**: For secure authentication.
- **BCrypt**: For hashing passwords.

---

## Project Setup

### Prerequisites

- [Node.js](https://nodejs.org/) (v14+)
- [MongoDB](https://www.mongodb.com/) (local or cloud instance, e.g., MongoDB Atlas)
- [Google Maps API Key](https://developers.google.com/maps/documentation/javascript/get-api-key)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/alexPalladis/FavPlace-App.git
   cd FavPlace-App

### Install dependencies for both frontend and backend:

```bash
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd frontend
npm install

###Set up Environment Variables:
```bash

Create a `.env` file in both the `frontend` and `backend` directories.


PORT=5000
MONGO_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/myDatabase?retryWrites=true&w=majority
JWT_SECRET=your_jwt_secret
