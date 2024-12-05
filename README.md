# Food-Machine-Management-System
this is a homework for Advanced Programming 2 Labs 

#### **Objective**:
To develop a simple **Food Machine Management System** using **C programming**, enabling administrators and customers to interact with the system for managing and purchasing food items.

---

### **System Features**:

1. **User Management (Login & Registration)**:
   - **Registration**:
     - Users can register with a unique username, password, and role (Admin or Customer).
     - User credentials are stored persistently in a file (`users.txt`).
   - **Login**:
     - Users log in using their credentials, validated against `users.txt`.
     - User roles (Admin or Customer) determine their privileges.

2. **CRUD Operations**:
   - **Admin Capabilities**:
     - **Create**: Add new food items to the inventory.
     - **Read**: View all available food products.
     - **Update**: Modify product details (name, price, quantity).
     - **Delete**: Remove products from the system.
   - **Customer Capabilities**:
     - **Read**: Browse available products.
     - **Purchase**: Buy products, which reduces their quantity in stock.

3. **Data Persistence**:
   - **Users Data**:
     - Stored in `users.txt`, including username, password, and role.
   - **Product Data**:
     - Stored in `products.txt`, containing product ID, name, price, and quantity.
   - Both files use a clear and readable format for easy maintenance.

4. **Privileges**:
   - **Admins**: Full access to all features, including managing users and products.
   - **Customers**: Limited to viewing and purchasing products.

5. **Formatted Input/Output**:
   - Data is displayed in a well-organized and clear format to enhance user experience and code maintainability.

---

### **Technical Details**:

- **Programming Language**: C.
- **Data Storage**: Persistent storage via plain text files (`users.txt` and `products.txt`).
- **Authentication**: Secure validation of user credentials and role-based access control.
- **File Operations**: Reading from and writing to files for persistent data handling.
- **User Interface**: Command-line interface (CLI).

---

### **Project Goals**:
1. Implement robust **user authentication** and **role-based access control**.
2. Enable seamless **inventory management** for admins.
3. Ensure intuitive and secure product browsing and purchasing for customers.
4. Use efficient file handling techniques for data persistence.
5. Collaborate effectively as a team to achieve modular and maintainable code.

---
