
# 🛍️ E-Commerce Follow-Along Project  
**A Full-Stack E-Commerce Platform Built Step-by-Step**  

![Tech Stack](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![Node](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

---

## 📚 Table of Contents  
- [Tech Stack](#-tech-stack)  
- [Milestones](#-milestones-1-23)  
- [How to Run](#-how-to-run)  
- [Contribution](#-contribution)  
- [License](#-license)  

---

## 🛠️ Tech Stack  
| **Frontend**         | **Backend**          | **Database** | **Tools**              |  
|-----------------------|----------------------|--------------|------------------------|  
| React.js              | Node.js              | MongoDB      | Git & GitHub           |  
| Tailwind CSS          | Express.js           | Mongoose     | Multer (File Uploads)  |  
| React Router          | JWT Authentication   |              | bcrypt (Encryption)    |  

---

## 🚀 Milestones (1-23)  

### **Milestone 1: Project Setup**  
✅ **Goals:**  
- Created `README.md` with project overview.  
- Initialized GitHub repository for version control.  

---

### **Milestone 2: Frontend & Backend Initialization**  
✅ **Goals:**  
- Set up React frontend and Node.js backend.  
- Configured Tailwind CSS for styling.  
- Built login page UI.  

---

### **Milestone 3: Backend Structure & Server Setup**  
✅ **Goals:**  
- Created Express.js server.  
- Connected MongoDB database.  
- Added error handling middleware.  

---

### **Milestone 4: User Model & Controller**  
✅ **Goals:**  
- Designed `User` schema with profile picture support.  
- Integrated Multer for image uploads.  
- Created API endpoints for user registration.  

---

### **Milestone 5: Sign-Up Page & Validation**  
✅ **Goals:**  
- Built responsive sign-up form.  
- Added email/password validation.  
- Integrated form with backend API.  

---

### **Milestone 6: Secure User Registration**  
✅ **Goals:**  
- Encrypted passwords using `bcrypt`.  
- Securely stored user data in MongoDB.  

---

### **Milestone 7: User Login & Authentication**  
✅ **Goals:**  
- Created login endpoint.  
- Implemented JWT token generation.  
- Added password comparison logic.  

---

### **Milestone 8: Product Card & Homepage**  
✅ **Goals:**  
- Designed reusable `ProductCard` component.  
- Built responsive homepage grid layout.  

---

### **Milestone 9: Product Input Form**  
✅ **Goals:**  
- Created form for product details (name, price, images).  
- Added image preview functionality.  

---

### **Milestone 10: Product Schema & API**  
✅ **Goals:**  
- Defined `Product` schema with validation.  
- Built POST endpoint for product creation.  

---

### **Milestone 11: Dynamic Homepage**  
✅ **Goals:**  
- Fetched products from backend.  
- Rendered products dynamically using `.map()`.  

---

### **Milestone 12: My Products Page**  
✅ **Goals:**  
- Added endpoint to filter products by user email.  
- Built "My Products" UI with user-specific listings.  

---

### **Milestone 13: Edit Product**  
✅ **Goals:**  
- Created PUT endpoint for product updates.  
- Added auto-fill edit form with image preview.  

---

### **Milestone 14: Delete Product**  
✅ **Goals:**  
- Built DELETE endpoint for products.  
- Added confirmation dialog before deletion.  

---

### **Milestone 15: Navbar Component**  
✅ **Goals:**  
- Designed responsive navbar with links.  
- Added mobile-friendly hamburger menu.  

---

### **Milestone 16: Product Info Page**  
✅ **Goals:**  
- Created product details page with dynamic routing.  
- Added "Add to Cart" button and quantity selector.  

---

### **Milestone 17: Add to Cart**  
✅ **Goals:**  
- Updated user schema with `cart` array.  
- Built API endpoint for cart updates.  

---

### **Milestone 18: Cart Page & Checkout**  
✅ **Goals:**  
- Designed cart page with item list and total price.  
- Added checkout button with order confirmation.  

---

### **Milestone 19: Cart Quantity Management**  
✅ **Goals:**  
- Implemented +/- buttons for quantity.  
- Added backend endpoints for quantity updates.  

---

### **Milestone 20: Profile Page**  
✅ **Goals:**  
- Built profile page displaying user data.  
- Added "Add Address" button.  

---

### **Milestone 21: Address Form**  
✅ **Goals:**  
- Created address form with fields for country, city, ZIP code, etc.  
- Added navigation from profile page.  

---

### **Milestone 22: Address Storage**  
✅ **Goals:**  
- Built API endpoint to store addresses.  
- Updated user schema with `addresses` array.  

---

### **Milestone 23: Order Placement**  
✅ **Goals:**  
- Added "Place Order" button in cart.  
- Created address selection page with radio buttons.  
- Designed `Order` schema: 

---

### **Milestone 24: Order Confirmation**
✅ Goals:
- Built order confirmation page.
- Displayed ordered products, selected address, and total cart value.
- Added "Place Order" button at the bottom.

---

### **Milestone 25: Placing an Order**
 ✅ Goals:
- Created an endpoint to receive products, user details, and address.
- Retrieved the user’s _id using their email.
- Stored each product as a separate order with the same address.
- Saved order details in the MongoDB orders collection using the existing order schema.

---

  ```javascript
  const orderSchema = new Schema({
    user: { type: Schema.Types.ObjectId, ref: 'User' },
    items: [{ product: Object, quantity: Number }],
    shippingAddress: Object,
    totalAmount: Number,
    status: { type: String, default: 'Processing' }
  });
  ```
- Built order creation endpoint.  

---

## 🖥️ How to Run  
1. **Clone the repo:**  
   ```bash
   git clone https://github.com/your-username/E_Commerce_Follow_Along.git
   cd E_Commerce_Follow_Along
   ```

2. **Install dependencies:**  
   ```bash
   # Frontend
   cd frontend && npm install
   # Backend
   cd ../backend && npm install
   ```

3. **Configure environment variables:**  
   - Create `.env` in `backend` with:  
     ```
     MONGODB_URI=your_mongodb_uri
     JWT_SECRET=your_jwt_secret
     ```

4. **Run the app:**  
   ```bash
   # Backend
   cd backend && npm start
   # Frontend
   cd frontend && npm start
   ```

---

## 🤝 Contribution  
Contributions welcome! Follow these steps:  
1. Fork the repository.  
2. Create a new branch: `git checkout -b feature/your-feature`.  
3. Commit changes: `git commit -m 'Add some feature'`.  
4. Push to the branch: `git push origin feature/your-feature`.  
5. Open a pull request.  

---

## 📜 License  
This project is licensed under the MIT License - see [LICENSE](LICENSE) for details.  

---

**[⬆ Back to Top](#-e-commerce-follow-along-project)**  

