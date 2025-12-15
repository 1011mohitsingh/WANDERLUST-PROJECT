# ✈️ Wanderlust  

Check out the live application deployed on Render:
👉 **[View Deployed Site](https://wanderlust-listings-f6oy.onrender.com/listings)**

Wanderlust is a full-stack web application inspired by Airbnb, built using the **MERN stack**.  
It allows users to explore, create, and review travel destinations (listings) with authentication, authorization, and seamless UI/UX.  

---

## 📸 Screenshots
Home-Wanderlust (Image)
<img width="1902" height="967" alt="Image" src="https://github.com/user-attachments/assets/305a222a-f325-4ec4-868b-1b6e431c39b4" />

Listing-Wanderlust (Image)
<img width="1898" height="872" alt="Image" src="https://github.com/user-attachments/assets/a6b9a62c-d5f8-4831-8910-b8ab5f87fbde" />

Edit-Listing-Wanderlust (Image)
<img width="1915" height="869" alt="Image" src="https://github.com/user-attachments/assets/405d38ce-0126-4999-a21a-620842df269e" />

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

**Frontend:**
* HTML5, CSS3
* JavaScript (ES6+)
* EJS (Embedded JavaScript Templates)
* Bootstrap 5

**Backend:**
* Node.js
* Express.js

**Database**  
* MongoDB, Mongoose

**Services & APIs:**
* Mapbox API (Geocoding & Maps)
* Cloudinary
* Render(Deployment)
  
---

## ⚙️ **Installation**

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/wanderlust.git
   cd wanderlust
   
2. **Install dependencies**  
   ```bash
   npm install
   
3. **Set up environment variables**
Create a .env file in the root directory with the following:
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_KEY=your_cloud_key
CLOUDINARY_SECRET=your_cloud_secret
MAPBOX_TOKEN=your_mapbox_token
MONGO_URL=mongodb://127.0.0.1:27017/wanderlust
SECRET=your_session_secret

4. **Run the application**
node app.js
OR using nodemon (if installed):
nodemon app.js

5. **Visit the App**
   Open your browser and go to: `http://localhost:8080/listings`

---

🤝 Contributing
Contributions are welcome! Feel free to fork this repo, make changes, and submit a pull request.
- Created by **MOHIT SINGH**
