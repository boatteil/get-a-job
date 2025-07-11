# 🧑‍💼 Get-a-Job

**Get-a-Job** is a full-stack job portal web application that enables users to search for jobs, post new listings, and manage job applications. Built with the MERN stack and modern React ecosystem tools, it provides a seamless, responsive, and secure user experience for job seekers and recruiters alike.

---

## 🚀 Features

- 🔐 JWT-based user authentication and authorization
- 📝 Create, view, update, and delete job listings
- 🔍 Search/filter job postings by keywords, location, or date
- 🌙 Fully responsive UI with light/dark themes
- 📊 Dashboard and stats for users/employers
- 🛡️ Secure backend using Helmet, XSS Clean, Rate Limiting, and Mongo Sanitize
- 📦 Modular folder structure with clean code separation

---

## 🧰 Tech Stack

### 🔧 Client
- **React 19**, **React Router v7**
- **Redux Toolkit** for state management
- **Tailwind CSS** for styling
- **React Hook Form** for form handling
- **Axios** for HTTP requests
- **Vite** for lightning-fast development

### 🔧 Server
- **Node.js**, **Express.js**
- **MongoDB** with **Mongoose**
- **JWT** for authentication
- **BcryptJS** for password hashing
- **Express Middleware**: `xss-clean`, `mongo-sanitize`, `rate-limit`, `morgan`

---


## ⚙️ Getting Started

Follow these steps to run the app locally:


1. Clone the repository: `git clone https://github.com/your-username/get-a-job.git`
2. Navigate to the project directory: `cd get-a-job`
3. Install the dependencies:
   - Front-end: `cd client && npm install`
   - Back-end: `cd server && npm install`
4. Set up the environment variables:
   - Create a `.env` file in the `server` directory.
   - Add the following environment variables:
     - `MONGODB_URI`: The connection string for your MongoDB database.
     - `JWT_SECRET`: A secret key for generating JSON Web Tokens.
5. Start the development server:
   - Front-end: `cd client && npm start`
   - Back-end: `cd server && npm start`
6. Open your browser and navigate to `http://localhost:8800` to access the application.
##  Contributions

Got an idea to improve this project? Whether it's feature suggestions, reporting bugs, or creating pull requests — all contributions are greatly appreciated. Feel free to fork the repo and help make it better!

---

##  Get in Touch

For any questions, feedback, or collaboration opportunities, feel free to reach out:  
 [vaibhavrajvardhan866@gmail.com](mailto:vaibhavrajvardhan866@gmail.com)
---


