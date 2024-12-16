### YelpCamp: Your Gateway to the Outdoors

YelpCamp is a web application designed for camping enthusiasts to share and explore the best camping spots. It allows users to create, browse, review, and rate campgrounds in an interactive and user-friendly platform. Built using **Express.js** and **EJS**, YelpCamp is perfect for honing web development skills and exploring the outdoors digitally!

---

## Features

- **User Authentication**:  
  Secure registration and login system using Passport.js, allowing users to create personal accounts.  
- **Campground Management**:  
  Users can create, edit, and delete their campgrounds with photos and descriptions.  
- **Reviews and Ratings**:  
  Share your experiences by leaving reviews and ratings for campgrounds.  
- **Interactive Map Integration**:  
  Integrated map view using Maptiler for a visual experience of campground locations.  
- **Responsive Design**:  
  Fully responsive design, making it accessible on all devices.

---

## Tech Stack

- **Frontend**:  
  - HTML, CSS, Bootstrap, EJS (Embedded JavaScript templates).  
- **Backend**:  
  - Node.js, Express.js, MongoDB (Mongoose for database interaction).  
- **Other Tools**:  
  - Passport.js for authentication.  
  - Maptiler for location mapping.  
  - Cloudinary for image uploads.

---

## Setup Instructions

1. **Clone the Repository**:  
   ```bash  
   git clone https://github.com/Mmacan2/YelpCamp.git  
   cd YelpCamp  
   ```

2. **Install Dependencies**:  
   ```bash  
   npm install  
   ```

3. **Set Up Environment Variables**:  
   Create a `.env` file in the root directory and add the following variables:  
   ```plaintext  
   DATABASE_URL=<Your MongoDB connection string>  
   CLOUDINARY_CLOUD_NAME=<Your Cloudinary cloud name>  
   CLOUDINARY_API_KEY=<Your Cloudinary API key>  
   CLOUDINARY_API_SECRET=<Your Cloudinary API secret>  
   MAPTILER_API_KEY=<Your Maptiler token>  
   ```

4. **Run the Application**:  
   ```bash  
   node app.js  
   ```  
   The application will be available at `http://localhost:3000`.

5. **Visit the Hosted Application**:  
   You can access the live version of YelpCamp at:  
   [https://yelpcamp-idpm.onrender.com](https://yelpcamp-idpm.onrender.com)  

---

## Project Structure

- `/models`: Contains Mongoose schemas for Campgrounds and Reviews.  
- `/routes`: Houses route files for user authentication, campgrounds, and reviews.  
- `/public`: Includes static files like CSS and JavaScript.  
- `/views`: Contains EJS templates for rendering pages.

---

## Future Improvements

- Add a "Favorites" feature for users to save their favorite campgrounds.  
- Implement campground recommendations based on user preferences.  
- Add social media integration for sharing campgrounds.

---
## Idea
Idea is taken from Udemy bootcamp https://www.udemy.com/course/the-web-developer-bootcamp
