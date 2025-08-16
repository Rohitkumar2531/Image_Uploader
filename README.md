Image Uploader

A full-stack Image Uploader web application built using the MERN stack (MongoDB, Express, React, Node.js) that allows users to upload images to the cloud via Cloudinary, store metadata in MongoDB, and view uploaded images in a responsive gallery.

🚀 Features

Upload images from the local device

Store images in Cloudinary (cloud storage)

Save image metadata (e.g., URL, public_id, upload time) in MongoDB

Display uploaded images in a dynamic gallery

Drag-and-drop or file picker interface

Responsive design for desktop and mobile

🛠️ Tech Stack
Frontend:

React

Axios

Bootstrap / Tailwind CSS (or custom CSS)

Backend:

Node.js

Express.js

MongoDB (with Mongoose)

Cloudinary SDK

Multer (for handling file uploads)

API Overview
POST /api/upload

Upload an image to Cloudinary

Returns image URL and metadata

GET /api/images

Fetch all uploaded image data from MongoDB

How It Works

User selects or drags an image into the uploader UI.

Image is sent to the backend using Axios.

Backend uploads image to Cloudinary and stores image metadata in MongoDB.

Frontend fetches and displays uploaded images in a gallery.

Future Improvements

Add user authentication (e.g., upload tracking)

Support multiple image uploads

Image compression before upload

Delete images (from Cloudinary + DB)

Pagination / Infinite scroll for gallery
