# PhotoVista

PhotoVista is a modern and intuitive photo-sharing application designed to help users connect, share, and explore beautiful moments. Built with a focus on simplicity, performance, and scalability, PhotoVista empowers users to upload, share, and interact with photos in real-time.

## Features

- **User Profiles**: Create customizable profiles to showcase your best moments.
- **Photo Upload**: Easily upload high-quality images with drag-and-drop functionality.
- **Social Interaction**: Like, comment, and share photos within the community.
- **Real-Time Notifications**: Get updates on likes, comments, and follows instantly.
- **Explore Feed**: Discover trending photos and follow your favorite users.
- **Privacy Controls**: Manage who can view your photos with robust privacy settings.
- **Search & Tags**: Find photos and users using hashtags or keywords.
- **Responsive Design**: Enjoy a seamless experience on desktop, tablet, and mobile devices.

## Technologies Used

### Frontend
- React.js
- Tailwind CSS
- Axios

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)

### Cloud & Storage
- AWS S3 for image storage
- Cloudinary for image optimization
- Firebase for real-time notifications

### DevOps
- Docker
- CI/CD pipelines with GitHub Actions
- Deployment via AWS Elastic Beanstalk

## Getting Started

### Prerequisites

Ensure you have the following installed on your system:
- Node.js v16+
- MongoDB
- Docker (optional for containerized setup)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/PhotoVista.git
   cd PhotoVista
   ```

2. Install dependencies for both frontend and backend:
   ```bash
   cd frontend && npm install
   cd ../backend && npm install
   ```

3. Set up environment variables:
   - Create `.env` files in the `frontend` and `backend` directories.
   - Add the necessary environment variables (e.g., API keys, database URIs).

4. Start the development servers:
   ```bash
   # Start backend server
   cd backend && npm run dev

   # Start frontend server
   cd frontend && npm start
   ```

5. Open your browser and navigate to `http://localhost:3000` to explore the app.

## Project Structure

```
PhotoVista/
├── frontend/       # React.js application
├── backend/        # Node.js API server
├── docs/           # Documentation and assets
└── README.md       # Project README file
```

## API Documentation

The backend API is documented using Swagger. Access the Swagger UI at `http://localhost:5000/api-docs` when the server is running.

### Example Endpoints

- **GET /api/photos**: Fetch all photos.
- **POST /api/photos**: Upload a new photo.
- **GET /api/users/:id**: Retrieve user details.
- **POST /api/auth/login**: Authenticate a user.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature description"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For inquiries or support, please contact:
- **Developer**: John Doe
- **Email**: johndoe@example.com
- **GitHub**: [yourusername](https://github.com/yourusername)
