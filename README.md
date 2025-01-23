# Email Template Builder

A modern web application for designing and managing customizable email templates with an intuitive interface.

## Features

- 🌐 Create responsive email templates easily
- 🖱️ Intuitive drag-and-drop editor
- 📂 Save, edit, and manage multiple templates
- 🖼️ Image upload support integrated with Cloudinary
- ✏️ Advanced rich text editing features
- 👀 Live preview of email templates
- 🔄 HTML code export for seamless integration
- 📱 Optimized for mobile and desktop use

## Tech Stack

### Frontend

- **React.js** for building a dynamic user interface
- **Tailwind CSS** for styling
- **Radix UI** for accessible components
- **Konva.js** for drag-and-drop canvas functionality
- **Axios** for communicating with APIs

### Backend

- **Node.js** for server-side logic
- **Express.js** as the web framework
- **MongoDB** with Mongoose for database operations
- **Cloudinary** for image storage and management
- **Multer** for handling file uploads

## Getting Started

### Prerequisites

- Install [Node.js](https://nodejs.org/) (v14 or higher recommended)
- Set up a [MongoDB](https://www.mongodb.com/) instance
- Create a [Cloudinary](https://cloudinary.com/) account

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/SumitGohil17/Email_Builder.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Email_Builder
   ```

3. Install dependencies for the backend:

   ```bash
   cd backend
   npm install
   ```

4. Install dependencies for the frontend:
   ```bash
   cd ../frontend
   npm install
   ```

### Configuration

1. Create a `.env` file in the `backend` directory with the following keys:
   ```env
   MONGO_URI=<your-mongodb-connection-string>
   CLOUDINARY_NAME=<your-cloudinary-cloud-name>
   CLOUDINARY_API_KEY=<your-cloudinary-api-key>
   CLOUDINARY_API_SECRET=<your-cloudinary-api-secret>
   PORT=5000
   ```

### Running the Application

1. Start the backend server:

   ```bash
   cd backend
   npm run server
   ```

2. Start the frontend application:

   ```bash
   cd ../frontend
   npm start
   ```

3. Access the application at [http://localhost:3000](http://localhost:3000).

## Deployment

### Backend Deployment

- Use services like **Render**, **Heroku**, or **AWS** to host the backend.

### Frontend Deployment

- Deploy the React application using **Vercel**, **Netlify**, or **GitHub Pages**.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to share your feedback and ideas to make this project even better!
