# Wildlife Ledger: Dynamic Animal & Category Management App
What is Wildlife Ledger?
Wildlife Ledger is a dynamic web application for managing animal listings and categories. It enables users to add new categories, upload animal details with images, and filter animals by category. The app is built with Next.js and integrates a backend API using Node.js, Express, and MongoDB, with file uploads handled by Cloudinary.

Features
Built with Next.js, Tailwind CSS, Axios, Express, MongoDB
Dynamic category management and animal listing
File uploads handled by Cloudinary for animal images
Filtering functionality for animals by category
Reusable form components for easy data entry
Tools
Next.js: A React framework for server-rendered applications.
Axios: A promise-based HTTP client for making API requests.
Tailwind CSS: A utility-first CSS framework for rapid UI development.
Express.js: A minimal Node.js web application framework.
MongoDB: A NoSQL database for flexible data management.
Cloudinary: A cloud-based image and video management service.
Installation
To set up and run the Wildlife Ledger app, follow these steps:

Note: Ensure you have Node.js and MongoDB installed on your system!

npm install or npm i
create a .env file in the server root with your connection strings

MONGO_URI=your-mongo-connection-string

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name

CLOUDINARY_API_KEY=your_cloudinary_api_key

CLOUDINARY_API_SECRET=your_cloudinary_api_secret

In the client root, create a .env file with the example variable

NEXT_PUBLIC_BASE_URL=http://localhost:8000

Start the Frontend & Backend development server

npm run dev
Links
Front-End Repository
Back-End Repository
Thank you for checking out WildLife Ledger!
