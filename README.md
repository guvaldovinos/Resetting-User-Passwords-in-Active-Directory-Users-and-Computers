## 🔑 Lab 3: Resetting User Passwords in Active Directory (ADUC)

### 🧭 Overview
This lab demonstrates how to **reset user passwords** and **unlock accounts** using **Active Directory Users and Computers (ADUC)** — one of the most essential Help Desk tasks.  
Resetting passwords is a daily responsibility for IT support technicians and system administrators.

---

### ⚙️ Steps Performed

1. **Opened ADUC**
   - Navigated to `Tools → Active Directory Users and Computers` in Server Manager.
   - Located the domain and expanded the Organizational Units (OUs).

2. **Searched for the User Account**
   - Clicked **Find** and searched for the user **Guillermo Valdovinos**.
   - Verified the username to ensure the correct account was selected before performing any changes.

3. **Reset the User’s Password**
   - Right-clicked the user account → **Reset Password**.
   - Entered a temporary password
   - Checked the box **“User must change password at next logon.”**  
     *Purpose: Forces the user to set a new password upon first login.*

4. **Handled Locked Accounts (If Applicable)**
   - Noted that accounts can become locked after multiple failed login attempts.
   - If locked, selected **“Unlock account”** before clicking **OK**.
   - This ensures the user can sign in immediately after the reset.

5. **Verified the Reset**
   - Confirmed the message:  
     ✅ *“The password for Guillermo Valdovinos has been changed.”*
   - The user was then able to log in and set a new password successfully.

---

### 🖼️ Screenshots

1. **Searching for the User in ADUC**  
   🔍<img width="1711" height="894" alt="Screenshot 2025-10-08 112658" src="https://github.com/user-attachments/assets/1ba0648c-88e7-4006-ac03-b2906caec4da" />
   *Screenshot showing the “Find Users, Contacts, and Groups” dialog with “Guillermo Valdovinos” searched.*  
   **Caption:** Confirms you can locate user accounts in Active Directory.

3. **User Properties Window**
   ⚙️<img width="1330" height="880" alt="Screenshot 2025-10-08 114815" src="https://github.com/user-attachments/assets/38be1fc2-39d1-42c1-9996-743a86ccf7bd" />
   *Screenshot of the user properties panel verifying username and details.*  
   **Caption:** Demonstrates proper user verification before performing a reset.

4. **Reset Password Dialog**  
   🔑<img width="1706" height="884" alt="Screenshot 2025-10-08 113230" src="https://github.com/user-attachments/assets/1df2846f-6121-47c9-aaa0-c408d853bb5a" />
   *Screenshot of the “Reset Password” window showing password fields and checkbox selections.*  
   **Caption:** Shows correct procedure for assigning temporary passwords.

5. **Account Tab Showing Unlock Option**  
   🔓<img width="1342" height="876" alt="Screenshot 2025-10-08 113441" src="https://github.com/user-attachments/assets/7ab4c023-29e2-4e1a-a79c-fefda657b95e" />
   *Screenshot of the “Account” tab displaying the “Unlock account” checkbox.*  
   **Caption:** Demonstrates awareness of account lockout recovery.

6. **Confirmation Message / Successful Login**  
   ✅<img width="1253" height="814" alt="Screenshot 2025-10-08 113246" src="https://github.com/user-attachments/assets/1fe2910c-ad96-4fe1-8a48-fbe9a92822f6" />
*Screenshot showing confirmation message or successful login screen after password reset.*  
   **Purpose:** Verifies that the reset process was completed successfully.

---

### 💡 Skills Demonstrated
- Password reset procedures  
- Account unlocking and verification  
- Communication best practices for user password issues  
- Core Active Directory Help Desk workflow  

---
