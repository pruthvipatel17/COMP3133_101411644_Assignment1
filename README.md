### 📌 **Employee Management System**
A GraphQL-based backend application for managing employees, built using **Node.js**, **Express**, **GraphQL**, **MongoDB**, and **Apollo Server**.

---

## 🚀 **Technologies Used**
### Backend:
- **Node.js** – JavaScript runtime for backend development.
- **Express.js** – Web framework for Node.js.
- **GraphQL** – API query language used for flexible data retrieval.
- **Apollo Server** – GraphQL implementation for Express.
- **MongoDB Atlas** – NoSQL database for storing user and employee data.
- **Mongoose** – ODM (Object Data Modeling) for MongoDB.

### Security:
- **bcryptjs** – Password hashing for secure storage.
- **jsonwebtoken (JWT)** – User authentication and authorization.

### Development Tools:
- **dotenv** – Manages environment variables securely.
- **Postman** – API testing.
- **Git & GitHub** – Version control.

---

## 📚 **Project Overview**
The **Employee Management System** provides a GraphQL API for managing employee records, allowing users to:
- **Sign up** and **log in** securely.
- **Add, update, delete, and retrieve employee records**.
- **Search employees** by ID, designation, or department.
- **Use JWT authentication** to protect sensitive operations.

---

## 🛠 **Setup Instructions**
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/pruthvipatel17/COMP3133_101411644_Assignment1.git
cd COMP3133_101411644_Assignment1
```

### 2️⃣ Install Dependencies
```sh
npm install
```

### 3️⃣ Configure Environment Variables
Create a **.env** file in the project root and add:
```env
PORT=4000
MONGODB_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/comp3133_StudentID_assignment1?retryWrites=true&w=majority
JWT_SECRET=your_secret_key
```

### 4️⃣ Start the Server
```sh
node index.js
```
or for development:
```sh
nodemon index.js
```

---

## 🔥 **GraphQL API Endpoints**
The API is accessible at:
```
http://localhost:4000/graphql
```
It provides the following **Queries** and **Mutations**:

### 🔹 Queries:
- Login
- Get All Employees
- Search Employee by ID
- Search Employee by Designation or Department

### 🔹 Mutations:
- Signup
- Add Employee
- Update Employee
- Delete Employee

---

## 🧪 **Testing the API**
1. Open **Postman** or **GraphiQL**.
2. Test queries and mutations using GraphQL playground.
3. Authenticate using JWT and include it in API requests for protected operations.

---

## 📁 **Project Structure**
```
/src
  ├── config/        # Database connection
  ├── models/        # Mongoose models (User, Employee)
  ├── resolvers/     # GraphQL resolver functions
  ├── schema/        # GraphQL schema definitions
  ├── middleware/    # Authentication middleware (JWT)
index.js             # Entry point
.env                 # Environment variables
README.md            # Project documentation
```

---

## 👉 **GitHub Repository**
[GitHub Link](https://github.com/pruthvipatel17/COMP3133_101411644_Assignment1.git)

---

## 📄 **Sample User Credentials**
```
{
  "username": "testuser",
  "email": "testuser@example.com",
  "password": "test@123"
}
```

## 👨 **Author**
**Pruthvi Patel**  
**COMP3133 - Full Stack Development II**

