# 🌍 WanderNest

**WanderNest** is a full-stack web application inspired by Airbnb, allowing users to list, explore, and review travel stays with interactive maps, secure authentication, and image uploads.

[🔗 Live Link](https://wandernest-bgyx.onrender.com/listings)  

---

## 🚀 Features

- 🔐 User Authentication (Register/Login/Logout)
- 🏠 Add, Edit, Delete Listings
- 📝 Review System with Add/Delete functionality
- 📍 Mapbox Integration for Location Visualization
- ☁️ Cloudinary for Image Uploads
- ⚙️ Flash Messaging, Secure Sessions, and Input Validation

---

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js
- **Frontend:** EJS, Bootstrap
- **Database:** MongoDB, Mongoose
- **Authentication:** Passport.js, Passport-Local, Passport-Local-Mongoose
- **Cloud Services:** Cloudinary (image storage), Mapbox (maps)
- **Other Packages:**  
  - Multer (file uploads)  
  - Joi (data validation)  
  - Dotenv (environment variables)  
  - Connect-Mongo (session store)  
  - Express-Session (session handling)  
  - Connect-Flash (flash messages)  
  - Cookie-Parser


## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/rohith-aryan/wanderNest.git
cd wanderNest
````

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up Environment Variables

Create a `.env` file in the root directory and add the following:

```
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_KEY=your_api_key
CLOUDINARY_SECRET=your_api_secret
MAPBOX_TOKEN=your_mapbox_token
DB_URL=your_mongodb_connection_string
SECRET=your_session_secret
```

### 4. Run the Application

```bash
node app.js
```

Or use nodemon:

```bash
nodemon app.js
```








