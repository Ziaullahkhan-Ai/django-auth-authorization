# Django User Authentication & Authorization

## 🔹 Objective
Build a secure authentication system with role-based access control in Django.

## 🔹 Features
✅ Custom authentication system in Django.  
✅ Implement role-based permissions and user groups.  
✅ Secure views and API endpoints based on user roles.

## 🔹 Implementation Steps
1. **User Authentication**
   - Created custom user model if needed.  
   - Configured login, logout, and registration views.  
   - Used **Django’s built-in authentication** for password hashing and security.  

2. **Role-Based Access Control**
   - Defined user roles (Admin, Staff, Regular User).  
   - Applied **permissions and groups** to control access to views and APIs.  
   - Decorators and mixins added for role-specific access restrictions.  

3. **API Security**
   - Protected API endpoints using authentication classes.  
   - Implemented **Token or JWT Authentication** for secure API access.  

4. **Testing**
   - Verified role restrictions for all user types.  
   - Ensured unauthorized users cannot access protected resources.

## 🔹 Outcomes
This assignment improved my understanding of:  
- Secure user authentication and management in Django.  
- Role-based access control for applications and APIs.  
- Implementing safe and scalable backend security practices.
