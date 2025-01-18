# Wanderlust

Wanderlust is a full-stack listing website that allows users to create, manage, and explore various listings. Users can add, edit, and delete listings, leave reviews, and interact with map functionality to enhance their experience.

## Features

- **User Authentication:**
  - Sign-up functionality saves user data to the database.
  - Login redirects users to the main site upon successful authentication.

- **Listing Management:**
  - Add, edit, and delete listings seamlessly.

- **Review System:**
  - Users can leave reviews for listings to share their experiences.

- **Map Integration:**
  - Explore listings with interactive maps for better navigation and context.

## Tech Stack

- **Frontend:** Ejs Templates
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Deployment:** Render ([Live Link](https://wanderlust-listings-f6oy.onrender.com/listings))

## Deployment

The application is live and accessible at the following URL:  
[https://wanderlust-listings-f6oy.onrender.com/listings](https://wanderlust-listings-f6oy.onrender.com/listings)

## Installation and Setup

To run this project locally, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone <repository-link>
   cd wanderlust
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Configure Environment Variables:**
   Create a `.env` file in the root directory and include the following:
   ```
   MONGO_URI=<your-mongodb-connection-string>
   PORT=3000
   ```

4. **Run the Application:**
   ```bash
   npm start
   ```

5. **Access the Application:**
   Open your browser and navigate to `http://localhost:3000`.

## Unique Features

- **Reviews:** A dynamic review system to share user experiences for each listing.
- **Map Functionality:** Integrated maps for better navigation and listing exploration.

## Future Enhancements

- Enhanced search functionality.
- Additional filtering options for listings.
- Mobile-friendly responsive design.
- A expanded and more advanced authentication where you can get otp or such methods by forgotting the password.

## Contributing

Feel free to contribute to this project by submitting issues or pull requests.

---

*Explore, create, and review with Wanderlust — your gateway to discovering amazing listings!*

