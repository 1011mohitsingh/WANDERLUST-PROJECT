# 🏕️ Wanderlust - Property Listing Web App

Wanderlust is a full-stack web application that allows users to list, explore, and review properties — similar to Airbnb. It features user authentication, review systems, and a map interface for location-based listings.

## 🚀 Live Demo

👉 [Wanderlust on Render](https://wanderlust-listings-f6oy.onrender.com/listings)

---

## 🔧 Tech Stack

- **Backend:** Node.js, Express.js
- **Frontend:** EJS, HTML, CSS, Bootstrap
- **Database:** MongoDB, Mongoose
- **Authentication:** Passport.js (local strategy)
- **Map Integration:** Mapbox
- **Image Storage:** Cloudinary
- **Deployment:** Render

---

## 📂 Features

- 🧾 Create, read, update, and delete property listings
- 👥 User authentication (signup/login/logout)
- ⭐ Add and delete reviews on listings
- 🗺️ Interactive Mapbox integration to show property locations
- 🖼️ Image upload for listings via Cloudinary

---

## 🛠️ How to Run Locally

Follow these steps to run the project on your local machine:

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/wanderlust.git
cd wanderlust
npm install

you have to crate your own env file with the following content:
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET=your_cloudinary_api_secret
MAPBOX_TOKEN=your_mapbox_token
DB_URL=mongodb://localhost:27017/wanderlust
SECRET=session_secret

npm start



