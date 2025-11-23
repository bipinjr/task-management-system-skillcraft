# Task Management System - SkillCraft Technology Internship

## 📋 Project Overview
A full-stack Task Management System built with Node.js, Express, and vanilla JavaScript. This project features user authentication, CRUD operations for tasks, and a modern responsive UI. Developed as part of the SkillCraft Technology internship program.

## ✨ Features
- **User Authentication**: Secure JWT-based authentication system
- **Task Management**: Create, read, update, and delete tasks
- **User-specific Tasks**: Each user can manage their own tasks
- **Modern UI**: Responsive gradient-based design
- **RESTful API**: Clean API architecture with Express.js
- **In-memory Storage**: Fast data access for development

## 🛠️ Technologies Used
- **Backend**: Node.js, Express.js
- **Authentication**: JSON Web Tokens (JWT)
- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **API**: RESTful architecture
- **Runtime**: WebContainer (StackBlitz)

## 🚀 Live Demo
[View Live Demo on StackBlitz](https://stackblitz.com/edit/stackblitz-starters-bsh77naj)

## 📦 Installation
```bash
# Clone the repository
git clone https://github.com/bipinjr/task-management-system-skillcraft.git

# Navigate to project directory
cd task-management-system-skillcraft

# Install dependencies
npm install

# Start the server
npm start
```

## 🔧 API Endpoints

### Authentication
- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - Login user

### Tasks
- `GET /api/tasks` - Get all tasks for logged-in user
- `POST /api/tasks` - Create a new task
- `PUT /api/tasks/:id` - Update a task
- `DELETE /api/tasks/:id` - Delete a task
- `PATCH /api/tasks/:id/complete` - Mark task as complete

## 📱 Screenshots
![Task Management System](https://via.placeholder.com/800x400?text=Task+Management+System)

## 👨‍💻 Author
**Bipin**
- GitHub: [@bipinjr](https://github.com/bipinjr)
- Internship: SkillCraft Technology

## 📝 License
This project is created for educational purposes as part of an internship program.

## 🙏 Acknowledgments
- SkillCraft Technology for the internship opportunity
- Express.js community for excellent documentation

---
*Developed with ❤️ during SkillCraft Technology Internship - November 2025*
