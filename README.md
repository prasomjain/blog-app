# MERN Blog App

A full-stack **MERN (MongoDB, Express.js, React, Node.js) blog application** with authentication, CRUD functionalities, and a rich text editor.

## Features

- **User Authentication**: Secure login & registration using JWT.
- **Create, Read, Update, Delete (CRUD)**: Users can create, edit, delete, and read blog posts.
- **Rich Text Editor**: Integrated text editor for formatting blog content.
- **Image Upload**: Users can upload images for blog posts.
- **Comment System**: Users can comment on blog posts.
- **Responsive UI**: Optimized for mobile and desktop.
- **Mongoose ORM**: Simplifies MongoDB interactions.

## Tech Stack

- **Frontend**: React, Redux, Tailwind CSS
- **Backend**: Node.js, Express.js, JWT Authentication
- **Database**: MongoDB (Mongoose ORM)
- **Storage**: Cloudinary (for image uploads)
- **Deployment**: Vercel (Frontend), Render/Heroku (Backend)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/mern-blog-app.git
   cd mern-blog-app
   ```

2. **Backend Setup:**
   ```bash
   cd backend
   npm install
   npm start
   ```

3. **Frontend Setup:**
   ```bash
   cd frontend
   npm install
   npm start
   ```

4. **Environment Variables:**
   Create a `.env` file in the backend directory and add:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   CLOUDINARY_URL=your_cloudinary_api_url
   ```

## Usage

- Run the backend server: `npm start` (inside `/backend` folder)
- Run the frontend server: `npm start` (inside `/frontend` folder)
- Open `http://localhost:3000` in your browser.

## Deployment

- **Frontend**: Deploy on Vercel or Netlify
- **Backend**: Deploy on Render, Heroku, or DigitalOcean
- **Database**: Use MongoDB Atlas for cloud storage

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.

---

Feel free to customize the README with additional project details! 🚀
