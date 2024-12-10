### **RBAC Implementation Summary**

This project implements a secure **Authentication**, **Authorization**, and **Role-Based Access Control (RBAC)** system using **Node.js**, **Express**, and **MongoDB**.

#### **Features**
1. **Authentication**:  
   - User registration with **bcrypt**-hashed passwords.  
   - Login with **JWT** for secure token-based sessions.  

2. **Authorization**:  
   - Role-based permissions (Admin, User, Moderator).  
   - Middleware ensures access control for routes.

3. **RBAC**:  
   - Centralized role-permission mapping.  
   - Scalable structure for adding roles/resources.
