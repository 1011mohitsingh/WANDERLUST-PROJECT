# 🌍 Wanderlust  

🔗 **Live Demo:** [Wanderlust on Render](https://wanderlust-listings-f6oy.onrender.com/listings)  

Wanderlust is a full-stack web application inspired by Airbnb, built using the **MERN stack**.  
It allows users to explore, create, and review travel destinations (listings) with authentication, authorization, and seamless UI/UX.  

---

## 🚀 Features  

- 🔑 **User Authentication & Authorization**  
  - Sign up, log in, log out using secure sessions.  
  - Only logged-in users can create, edit, or delete listings.  
  - Role-based permissions for users and admins.  

- 🏡 **Listings Management**  
  - Create, edit, and delete listings.  
  - Upload multiple images for a listing.  
  - Add price, location, and description details.  

- ⭐ **Reviews & Ratings**  
  - Users can leave reviews and star ratings on listings.  
  - Edit or delete their own reviews.  

- 🗺 **Map Integration**  
  - Interactive maps to view listing locations.  
  - Powered by **Mapbox API**.  

- 📱 **Responsive UI**  
  - Mobile-friendly and intuitive design using **Bootstrap**.  

---

## 🛠 Tech Stack  

**Frontend**  
- HTML, CSS, JavaScript  
- Bootstrap  
- EJS (templating)  

**Backend**  
- Node.js, Express.js  

**Database**  
- MongoDB, Mongoose  

**Other Tools & APIs**  
- Passport.js (Authentication)  
- Cloudinary & Multer (Image Uploads)  
- Mapbox API (Maps & Geolocation)  

---

## ⚙️ Installation  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/wanderlust.git
   cd wanderlust
   
2. **Install dependencies**  
   ```bash
   npm install
   
3. Set up environment variables
Create a .env file in the root directory with the following:
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_KEY=your_cloud_key
CLOUDINARY_SECRET=your_cloud_secret
MAPBOX_TOKEN=your_mapbox_token
MONGO_URL=mongodb://127.0.0.1:27017/wanderlust
SECRET=your_session_secret

4. Run the application
node app.js
OR using nodemon (if installed):
nodemon app.js

🤝 Contributing
Contributions are welcome! Feel free to fork this repo, make changes, and submit a pull request.

📜 License
This project is licensed under the MIT License.


