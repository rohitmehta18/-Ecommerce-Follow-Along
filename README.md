# -Ecommerce-Follow-Along

## Milestone_1
created readme.md
pushed readme.md

## Milestone 2 🚀 

## 📌 Overview  
Welcome to **Milestone 2** of our e-commerce application development! In this phase, we focus on setting up the project structure, frontend, backend, and styling, along with developing the **Login Page**.  

## 🛠️ Key Features  
### 📁 Project Folder Structure  
- Organize files into **frontend** and **backend** directories for better maintainability.  

### ⚛️ React Frontend Setup  
- Initialize a **React.js** application using Vite for a fast development experience.  

### 🟢 Node.js Backend Setup  
- Set up a basic **Node.js** server to prepare for API integration in the next milestones.  

### 🎨 Tailwind CSS Configuration  
- Integrate and configure **Tailwind CSS** for responsive, utility-based styling.  

### 🔐 Login Page Development  
- Build a **Login Page** with a user-friendly design and authentication functionality.  

## 📂 Folder Structure  

## Milestone 3 🛠️  

## 📌 Overview  
Welcome to **Milestone 3** of our e-commerce application development! This phase focuses on setting up the backend structure, server configuration, database integration, and error handling.  

## 🛠️ Key Features  

### 📁 Backend Folder Structure  
- Organize backend files into a structured hierarchy, including **routes, controllers, models, and middleware**.  
- Introduce **utils** and **middlewares** for better code organization and maintainability.  

### 🖥️ Server Setup  
- Use **Node.js** and **Express** to create a backend server.  
- Configure the server to listen on a designated port.  

### 🗄️ Database Connection  
- Integrate **MongoDB** for efficient data storage.  
- Establish and confirm a stable connection between the server and MongoDB.  

### ⚠️ Error Handling  
- Implement clear error messages for improved debugging and user feedback.  

## 📂 Folder Structure  

## Milestone 4 📦  

## 📌 Overview  
Welcome to **Milestone 4** of our e-commerce application development! In this phase, we focus on defining the **User Model**, creating the **User Controller**, and setting up **Multer** for file uploads.  

## 🛠️ Key Features  

### 🗺️ What’s a Model?  
- A **model** acts as a detailed map or plan for structuring data.  
- The **User Model** defines how user data (e.g., name, email, password) is stored in the database.  
- In **MongoDB**, we use **Schemas** to define the structure of a model.  

### 🎯 What’s a Controller?  
- A **controller** manages how the server responds to different requests.  
- For example, the **User Controller** handles user signup by managing data flow between the frontend and database.  
- Think of it as a "manager" ensuring smooth communication between different parts of the app.  

### 📂 File Uploads with Multer  
- Users may need to upload files like profile pictures.  
- **Multer** is a Node.js middleware that helps manage file uploads efficiently.  
- It allows storing user images on the server, acting like a virtual file cabinet.  

## 📝 Steps for Milestone 4  
This milestone will be covered in a **mentor-led lesson**, where your mentor will guide you through:  
1. **Explaining and creating the User Model**  
2. **Creating the User Controller**  
3. **Setting up Multer for file uploads**  

---

## **Milestone 5 📝**  

## 📌 **Overview**  
Welcome to **Milestone 5** of our e-commerce application development! In this phase, we will focus on creating the **Sign-Up Page** and implementing **form validation** to ensure a smooth user experience.  

## 🛠️ **Key Features**  

### 📝 **What’s a Sign-Up Page?**  
- The **Sign-Up Page** allows users to enter their details to create an account.  
- It typically includes fields like:  
  - **Name**  
  - **Email**  
  - **Password**  
- Once the user fills out the form, the data is sent to the server for processing.  
- We’ll design a **clean and user-friendly** sign-up form.  

### ✅ **What is Form Validation?**  
- **Form Validation** ensures that the information users enter is in the correct format.  
- Key validation checks include:  
  - **Email format validation** (ensuring a valid email structure).  
  - **Password validation** (checking length and security criteria).  
- Validation helps prevent errors and ensures that the backend receives clean data.  

## 📝 **Steps for Milestone 5**  
In this milestone, you will work on the **frontend**, while your mentor will guide you through:  
1. **Building the Sign-Up Page using HTML and CSS**.  
2. **Adding form validation to ensure users input valid data**.  

---

Here’s your **Milestone 6** in the same format as your previous milestones:  

---

## Milestone 6 🔒  
📌 **Overview**  
Welcome to Milestone 6 of our e-commerce application development! In this phase, we focus on encrypting user passwords to enhance security and protect user data.  

🛠️ **Key Features**  

🔑 **Why Encrypt Passwords?**  
- **Protect User Data**: Keeps passwords safe if hackers access the database.  
- **Privacy**: Ensures user passwords aren’t visible to anyone.  
- **Compliance**: Follows security laws like GDPR and PCI-DSS.  
- **Stops Password Theft**: Encrypted passwords can’t be easily stolen or guessed.  

📝 **Steps for Milestone 6**  
This milestone will be covered in a mentor-led lesson, where your mentor will guide you through:  

1️⃣ **Encrypt the Password**  
- Use **bcrypt** to hash the user's password during signup.  
- Save the hashed password in the database instead of plain text.  

2️⃣ **Store Complete User Data**  
- Save all the user's data (e.g., name, email, etc.) in the database.  
- Ensure that the password remains **encrypted** for security.  

🚀 Get ready to strengthen your authentication system with **secure password encryption**!  

---


## **Milestone 7 🔑**  

### 📌 Overview  
Welcome to **Milestone 7** of our e-commerce application development! In this phase, we focus on creating a **backend login endpoint**, validating user credentials, and verifying encrypted passwords stored in the database.  

### 🛠️ Key Features  

### 📝 **Why is Login Authentication Important?**  
- **Secure Access**: Ensures only registered users can access their accounts.  
- **Data Protection**: Prevents unauthorized access to user information.  
- **User Experience**: Allows users to log in seamlessly with their credentials.  

### 🔑 **How Login Authentication Works**  

1️⃣ **User Enters Credentials**  
   - The user provides their **email/username** and **password** on the login page.  

2️⃣ **Fetch User Data from Database**  
   - The backend retrieves the user record based on the provided email/username.  
   - If the user is not found, return an error: `"User does not exist."`  

3️⃣ **Compare Encrypted Passwords**  
   - Hash the input password using **bcrypt** (same algorithm used during signup).  
   - Compare it with the **stored hashed password** in the database.  
   - If they match, the user is authenticated; if not, return an error.  

### 📝 **Steps for Milestone 7**  

1. **Create a Login Endpoint**  
   - Accept user credentials (**email/username and password**).  
   - Retrieve the corresponding user from the database.  

2. **Validate Password**  
   - Use **bcrypt** to compare the entered password with the stored hashed password.  
   - If the password matches, return a **successful login response**.  
   - If incorrect, return an **error message**.  

🚀 Get ready to implement **secure and efficient user authentication**!  

---

## **Milestone 8 🛍️**  

### 📌 Overview  
Welcome to **Milestone 8** of our e-commerce application development! In this phase, we focus on creating a **frontend card component for products** and designing the **homepage** to display these product cards dynamically.  

### 🛠️ Key Features  

### 🎨 **Why Create Card Components?**  
- **Showcase Products Effectively**: Displays product details in a clear and visually appealing format.  
- **Reusable Design**: Can be used across multiple pages, such as product listings and recommendations.  
- **Improved User Experience**: Provides an intuitive way for users to browse and interact with products.  
- **Organized Layout**: Keeps the homepage structured, clean, and user-friendly.  

### 🖼️ **How to Display a Single Card for Multiple Products?**  
1️⃣ **Create a Dynamic Component**  
   - Design a single **Product Card Component** that accepts **product details as props**.  

2️⃣ **Use Array Mapping**  
   - Fetch the product list and iterate over it using **map()** to render a card for each product.  

3️⃣ **Pass Data Dynamically**  
   - Ensure each card receives unique product information (**name, price, image, etc.**).  

4️⃣ **Maintain Consistency**  
   - Keep a uniform layout across all product cards to enhance readability and usability.  

### 📝 **Steps for Milestone 8**  

#### 1️⃣ **Create the Product Card Component**  
- Design a **reusable** card component that includes:  
  - **Product Image**  
  - **Product Name**  
  - **Price**  
  - **Add to Cart Button**  

#### 2️⃣ **Design the Homepage Layout**  
- Implement a **grid layout** or **flexbox** to display multiple product cards neatly.  
- Ensure the design is **responsive** for different screen sizes.  

🚀 Get ready to **build an interactive product showcase** for your e-commerce application!  

---  
