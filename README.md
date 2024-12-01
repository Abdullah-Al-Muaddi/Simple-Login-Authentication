# **MFA Authentication System**

This is a simple **Multi-Factor Authentication (MFA)** system built with **Streamlit** and **PyOTP**. It simulates a customer banking system with a login page, OTP verification, and basic banking features.

---

### **Features**
- **Login**: Enter email and password to log in (test credentials provided).
- **OTP Verification**: Enter the OTP generated after login.
- **Main Page**: View account summary and interact with basic banking actions like transferring funds and paying bills (features coming soon).
- **Logout**: Log out and return to the login page.

---

### **Usage**

1. **Login**:
   - Go to the login page.
   - Use the test credentials:
     - **Email**: `Test_User@gmail.com`
     - **Password**: `Test1234`

2. **OTP**:
   - After successful login, an OTP will be generated and displayed.
   - Enter the OTP in the input field to proceed.

3. **Main Page**:
   - After OTP verification, you will be redirected to the main page.
   - On the main page, you can see your account balance, initiate a fund transfer, pay bills, or view statements (currently placeholders).
   - Click "Log Out" to return to the login page.

---


### **How to use**

Run the App:
   ```bash
   streamlit run simple_login.py
   ```
---

