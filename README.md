# MERN Stack Portfolio

A modern, full-stack portfolio application built with the MERN stack (MongoDB, Express.js, React, Node.js) and TypeScript.

## Features

- 🎨 Modern UI with Tailwind CSS
- 🌍 Internationalization support
- 🔒 Authentication & Authorization
- 📊 Analytics Dashboard
- 🖼️ Dynamic Profile Management
- 📱 Responsive Design
- 🌓 Dark/Light Mode
- 🔍 SEO Optimized
- 📝 Blog/Projects Management
- 📈 Skills & Experience Tracking

## Tech Stack

### Frontend

- React with TypeScript
- Vite for build tooling
- Tailwind CSS for styling
- Framer Motion for animations
- React Router for navigation
- Context API for state management
- i18next for internationalization

### Backend

- Node.js & Express.js
- MongoDB with Mongoose
- JWT for authentication
- Multer for file uploads
- Express Validator for validation

## Project Structure

```
├── src/                      # Frontend source code
│   ├── components/           # Reusable React components
│   ├── context/             # React Context providers
│   ├── pages/               # Page components
│   ├── services/            # API service functions
│   ├── utils/               # Utility functions
│   ├── constants/           # Constants and configurations
│   ├── locales/             # Translation files
│   └── layouts/             # Layout components
│
├── backend/                  # Backend source code
│   ├── src/
│   │   ├── models/          # MongoDB models
│   │   ├── routes/          # Express routes
│   │   ├── middleware/      # Custom middleware
│   │   └── utils/           # Utility functions
│   └── uploads/             # Uploaded files
│
├── public/                   # Static files
└── uploads/                  # Uploaded files (frontend)
```

## Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/ELMACHHOUNE/MERN-Stack-portfolio
cd MERN-Stack-portfolio
```

2. Install dependencies:

```bash
# Install frontend dependencies
npm install

# Install backend dependencies
cd backend
npm install -g nodemon
npm install
```

3. Environment Setup:

Frontend (.env):

```env
VITE_API_URL=http://localhost:5000/api
```

Backend (.env):

```env
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

4. Start the development servers:

```bash
# Start frontend (from root directory)
npm run dev

# Start backend (from backend directory)
nodemon
```

## Features Documentation

### Authentication

- JWT-based authentication
- Protected routes
- Role-based access control (Admin/User)

### Profile Management

- Upload profile picture
- Update personal information
- Manage social links
- CV/Resume upload and management

### Skills & Experience

- Add/Edit/Delete skills
- Categorize skills
- Track experience and projects
- Manage core values and interests

### Analytics

- Page view tracking
- User interaction metrics
- Download statistics
- Contact form analytics

### Internationalization

- Multi-language support
- Easy language switching
- Customizable translations

### Admin Dashboard

- User management
- Content management
- Analytics overview
- Settings management

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [React](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Framer Motion](https://www.framer.com/motion/)
- [MongoDB](https://www.mongodb.com/)
- [Express.js](https://expressjs.com/)
- [Nodemon](https://nodemon.io/)

## Contact

Mohamed EL MACHHOUNE - [@ELMACHHOUNE](https://github.com/ELMACHHOUNE) - business.elmachhoune@gmail.com

Project Link: [https://github.com/ELMACHHOUNE/MERN-Stack-portfolio](https://github.com/ELMACHHOUNE/MERN-Stack-portfolio)
