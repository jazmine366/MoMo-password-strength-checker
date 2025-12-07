# Password Strength Checker 🔐

A password examing tool that analyzes password strength using regex rules, detects weak patterns, and generates secure random passwords. Built under 3 hours during a cybersecurity hackathon.

The project includes:
- A Python backend password analysis engine  
- A Streamlit based frontend UI  
- Deployment on an Amazon EC2 (Amazon Linux) instance during the hackathon  

**The EC2-hosted demo may no longer be active due to free tier limits,  
but the full source code is included in this repository and can be run locally.**

---

## Features

- **Password strength evaluation**  
  Checks length, uppercase/lowercase letters, digits, and special characters (!@#$%&?)

- **Weak pattern detection**  
  - Common passwords (0000)
  - Repeating characters  
  - Consecutive sequences (abcd, 1234, 0123456789)  
  - Same as username  

- **Security validation**  
  - ASCII-only (english only) 
  - No spaces  
  - Rejects easily guessable patterns

- **Color bar (terminal only not UI version)**
  - Red = Weak
  - Yellow = Medium
  - Green = Strong
 
- **Strong random password generator**  
  Generates strong and secure 12 character passwords

- **Frontend built using Streamlit**  
  Simple interactive UI that displays password strength and generates suggested passwords

- **Cloud deployment on AWS EC2 (Amazon Linux)**  
  Configured during the hackathon for live demo access  

---
## 📸 Demo

### **1. Terminal Password Checker**
<img width="514" height="193" alt="Screenshot 2025-12-06 at 8 57 10 PM" src="https://github.com/user-attachments/assets/c3810d62-d93c-4916-83d5-b3be55243937" />
<img width="845" height="156" alt="Screenshot 2025-12-06 at 9 01 18 PM" src="https://github.com/user-attachments/assets/834d8b16-c902-4ef0-b421-3e3671059e17" />

### **2. Streamlit Frontend UI**
<img width="1440" height="900" alt="Screenshot 2025-12-06 at 9 03 22 PM" src="https://github.com/user-attachments/assets/61759a09-0c20-4d4f-a1eb-95239d2b2216" />

### **3. 5–10 second GIF Demo**
Generating a strong alternative + ps can not be same as username
![demo](https://github.com/user-attachments/assets/f6c23e08-3676-4a86-979c-93021c5abbd6)

