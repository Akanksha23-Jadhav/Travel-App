GlxTrvl - Travel Booking Website

GlxTrvl is a responsive and user-friendly travel website built with the MERN stack (MongoDB, Express.js, React.js, Node.js). Users can explore destinations, browse services, and book their next adventure with ease.

Features

Browse destinations and tour packages

Book hotels, flights, and travel experiences

Interactive image sliders using Swiper

Responsive design for all screen sizes

Simple form integration for contact and booking

Modal popups for smooth user interaction

Project Structure
glxtrvl/
public/ - Static files
src/
assets/ - Images (img1.jpg, img2.jpg, etc.)
Components/ - Navbar, Footer, etc.
Pages/
Home/
Home.js
About.jsx
Services.jsx
CallToAction.jsx
Modal.jsx
Contact.js
Pricing.js
Training.js
App.js - Main app routes
index.js - React entry point
.gitignore
package.json
package-lock.json
README.md

Images
Place all images like img1.jpg, img2.jpg, etc. inside:
src/assets/

Use them like this in your components:
<img src={require('../../assets/img1.jpg')} alt="Travel Destination" />

Getting Started

Clone the Repository
git clone https://github.com/your-username/glxtrvl.git
cd glxtrvl

Install Dependencies
npm install

Run the Development Server
npm start

Visit: http://localhost:3000

Built With

Frontend: React.js, React Router, Swiper.js

Backend (optional): Node.js, Express.js

Database (optional): MongoDB

Styling: Tailwind CSS or Custom CSS

Extras: Modals, Image sliders, Responsive layout



