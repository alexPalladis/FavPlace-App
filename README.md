# FavPlaces 🌍

FavPlaces is a full-stack web application where users can create an account, upload images of their favorite places around the world, and view them on an interactive Google Maps interface. The app is built using **React** for the frontend, **Node.js** and **Express** for the backend, and **MongoDB** with **Mongoose** for the database.

---

## Features ✨

- **User Authentication**: Register and log in securely to your account.
- **Image Upload**: Upload pictures of your favorite places.
- **Google Maps Integration**: View your favorite places on an interactive map.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **CRUD Functionality**: Edit and delete your places with ease.

---

## Tech Stack 🛠️

- **Frontend**: React, Axios
- **Backend**: Node.js, Express.js
- **Database**: MongoDB, Mongoose
- **Maps API**: Google Maps API
- **Other Tools**: Multer (file upload), JSON Web Tokens (JWT), bcrypt (password hashing)

---

## Prerequisites 🖥️

Make sure you have the following installed on your machine:

- Node.js (v14+)
- MongoDB (local or cloud-based, e.g., MongoDB Atlas)
- NPM or Yarn

---

## Getting Started 🚀

### 1. Clone the Repository
```bash
git clone https://github.com/alexPalladis/FavPlaces.git
cd FavPlaces
```

### 2. Setup Environment Variables
Create `.env` files in both the `frontend` and `backend` directories. Follow the examples below:

#### Frontend `.env`
```env
REACT_APP_API_URL=http://localhost:5000/api
REACT_APP_GOOGLE_MAPS_API_KEY=your_google_maps_api_key
```

#### Backend `.env`
```env
PORT=5000
MONGO_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/myDatabase?retryWrites=true&w=majority
JWT_SECRET=your_jwt_secret
```

### 3. Start the application

#### Start backend server
```env
cd backend
npm start
```

#### Start frontend server
```env
cd frontend
npm start
```

## How It Works

-**Sign Up: Users can create an account with their email and password.**

-**Log In: Users can log in to their account to access features.**

-**Add a Place: Users can add their favorite places by:**

   1)Providing a location name and description.

   2)Uploading an image.

   3)View on Google Maps: All uploaded places are displayed on a Google Map with markers.

## API Endpoints

#### Authentication:

-**GET /api/users:** See all the users(Home Page).

-**POST /api/users/signup:** Create a new user account.

-**POST /api/users/login:** Log in with existing credentials.

#### Places:

-**GET /api/places:** Get all places.

-**POST /api/places:** Add a new place (authenticated).

-**PATCH /api/places/:pid:** Update details of a specific place.

-**DELETE /api/places/:pid:** Delete a place (authenticated).



