# PublicBoard 📋

A community-driven issue reporting platform that enables users to report, track, and manage public issues in their neighborhood or community. Built with the MERN stack (MongoDB, Express, React, Node.js).

## 🌟 Features

- **Issue Reporting**: Users can easily report community issues with detailed descriptions
- **Issue Tracking**: Track the status of reported issues from submission to resolution
- **Admin Dashboard**: Administrative interface for managing and resolving issues
- **Statistics & Analytics**: Visual insights into community issues and trends
- **Responsive Design**: Mobile-friendly interface that works on all devices
- **Real-time Updates**: Live status updates and notifications
- **Dark/Light Theme**: Toggle between light and dark modes

## 🚀 Tech Stack

### Frontend
- **React 18** - Modern React with hooks
- **Vite** - Fast build tool and dev server
- **React Router** - Client-side routing
- **Axios** - HTTP client for API calls
- **Tailwind CSS** - Utility-first CSS framework

### Backend
- **Node.js** - JavaScript runtime
- **Express.js** - Web framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling
- **CORS** - Cross-origin resource sharing

## 📦 Installation & Setup

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn
- MongoDB (optional - app can run in demo mode without it)

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/PublicBoard.git
   cd PublicBoard
   ```

2. **Install dependencies for all packages**
   ```bash
   npm run install-all
   ```

3. **Set up environment variables**
   
   Create a `.env` file in the `backend` directory:
   ```env
   PORT=5000
   MONGODB_URI=mongodb://localhost:27017/publicboard
   NODE_ENV=development
   ```
   
   Create a `.env` file in the `frontend` directory:
   ```env
   VITE_API_URL=http://localhost:5000
   ```

4. **Start the development servers**
   ```bash
   npm run dev
   ```
   
   This will start both the backend server (port 5000) and frontend dev server (port 5173) concurrently.

### Individual Setup

If you prefer to run frontend and backend separately:

**Backend:**
```bash
cd backend
npm install
npm run dev
```

**Frontend:**
```bash
cd frontend
npm install
npm run dev
```

## 🌐 Access Points

- **Frontend**: http://localhost:5173
- **Backend API**: http://localhost:5000
- **API Health Check**: http://localhost:5000/api/health

## 📁 Project Structure

```
PublicBoard/
├── backend/                 # Express.js API server
│   ├── config/             # Database configuration
│   ├── controllers/        # Route controllers
│   ├── models/            # MongoDB models
│   ├── routes/            # API routes
│   ├── utils/             # Utility functions
│   └── server.js          # Main server file
├── frontend/               # React.js frontend
│   ├── public/            # Static assets
│   ├── src/
│   │   ├── components/    # Reusable React components
│   │   ├── context/       # React context providers
│   │   ├── pages/         # Page components
│   │   └── utils/         # Utility functions
│   └── index.html         # HTML template
├── package.json           # Root package.json with scripts
└── README.md             # This file
```

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

### How to Contribute

1. **Fork the Repository**
   - Click the "Fork" button at the top of this page
   - Clone your forked repository locally

2. **Create a Feature Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make Your Changes**
   - Follow the existing code style
   - Add tests if applicable
   - Update documentation as needed

4. **Test Your Changes**
   ```bash
   npm run dev
   ```
   - Ensure all functionality works as expected
   - Test on different screen sizes

5. **Commit and Push**
   ```bash
   git add .
   git commit -m "Add your feature description"
   git push origin feature/your-feature-name
   ```

6. **Create a Pull Request**
   - Go to your fork on GitHub
   - Click "New Pull Request"
   - Provide a clear description of your changes

### Contribution Guidelines

- Follow the existing code style and conventions
- Write clear, descriptive commit messages
- Update documentation for any new features
- Test your changes thoroughly
- Be respectful and constructive in code reviews

## 🌟 Show Your Support

If you find this project useful, please consider:

- ⭐ **Starring the repository** - It helps others discover the project
- 🐦 **Sharing on social media** - Spread the word about PublicBoard
- 🤝 **Contributing code** - Help improve the project
- 📝 **Reporting issues** - Help us identify and fix bugs
- 💡 **Suggesting features** - Share your ideas for improvements

## 📄 License

This project is licensed under the ISC License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

Have questions or suggestions? Feel free to:

- Open an issue on GitHub
- Start a discussion
- Contact the maintainers

---

**Made with ❤️ by the PublicBoard team**

*"Building better communities, one issue at a time."*
