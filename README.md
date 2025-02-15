# Task Manager API 🚀  

A powerful and secure RESTful API for a task management application built with Flask and PostgreSQL. This API supports user authentication, role-based access control, and real-time notifications through WebSocket integration. It is deployed on AWS using a CI/CD pipeline for seamless testing and deployment.  

---

## 🎯 Features  
- **User Authentication**: Secure authentication with JWT tokens.  
- **Role-Based Access Control**: Fine-grained access control for different user roles (Admin, Manager, User).  
- **Real-Time Notifications**: Instant updates on task assignments and status changes using WebSocket.  
- **Task Management**: Create, update, delete, and track tasks with detailed status and priority levels.  
- **CI/CD Integration**: Automated testing and deployment on AWS using CI/CD pipelines.  
- **Scalable Architecture**: Built to scale with increasing user and task loads.  

---

## ⚙️ Tech Stack  
- **Backend Framework**: [Flask](https://flask.palletsprojects.com/)  
- **Database**: [PostgreSQL](https://www.postgresql.org/)  
- **WebSocket**: [Flask-SocketIO](https://flask-socketio.readthedocs.io/)  
- **Authentication**: [JWT (JSON Web Tokens)](https://jwt.io/)  
- **CI/CD**: GitHub Actions for automated testing and deployment  
- **Cloud Platform**: [AWS](https://aws.amazon.com/) for deployment and scaling  

---

## 📦 Architecture Overview  
The service is designed with a modular architecture for scalability and maintainability:  
- **Flask API**: Handles CRUD operations for tasks, user authentication, and role-based access.  
- **PostgreSQL Database**: Stores user data, tasks, roles, and notification logs.  
- **WebSocket Server**: Sends real-time notifications to users for task updates.  
- **CI/CD Pipeline**: Automates testing and deployment using GitHub Actions on AWS.  

---

## 🚀 Getting Started  
### Prerequisites  
- Python 3.8+  
- PostgreSQL  
- AWS Account (for deployment)  

### Clone the Repository  
```bash
git clone https://github.com/your-username/task-manager-api.git
cd task-manager-api

