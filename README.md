# ☁️ Host a Password Manager in the Cloud (Passbolt)

## 🎯 Objective
Deploy and configure **Passbolt**, a self-hosted password manager, on AWS to demonstrate secure credential management and cloud infrastructure setup.

---

## 🧰 Tools Used
- **AWS EC2 (Ubuntu Server 22.04)**
- **Passbolt**
- **SSH**
- **Ubuntu Terminal**
- **HTTP (Local Access)**

---

## ⚙️ Steps Performed

1. **Provisioned the Cloud Environment**
   - Launched an **EC2 instance** running Ubuntu Server 22.04.
   - Configured security groups to allow inbound connections via ports **80 (HTTP)** and **22 (SSH)**.

2. **Generated SSH Key Pair**
   - Created a key pair on the local Ubuntu system.
   - Connected securely to the EC2 instance via SSH using the private key.

3. **Installed and Configured Passbolt**
   - Completed Passbolt setup through the terminal installer.
   - Accessed Passbolt using the public IP address via HTTP.

4. **Domain and Accessibility Configuration**
   - Configured hosting and DNS records for the Passbolt domain (for future HTTPS setup).
   - Verified external accessibility of the web interface.

5. **Security Considerations**
   - Chose **HTTP** temporarily for testing due to lack of domain SSL certification.
   - Noted that **HTTPS encryption** would be essential for production use to protect credentials in transit.

6. **Password Management**
   - Created and stored complex passwords within Passbolt.
   - Tested secure storage and retrieval functionality.

---

## 📸 Screenshots
1. **AWS EC2 instance dashboard** *(instance running and accessible)*  <img width="1261" height="640" alt="Screenshot 2025-10-12 003019" src="https://github.com/user-attachments/assets/4827f5a9-8ba5-4d75-92ba-24d19ec76f1c" />

2. **Generating key pair via Parrot**  <img width="1021" height="648" alt="Screenshot 2025-10-11 235940" src="https://github.com/user-attachments/assets/28900e4f-8f23-404f-ac63-f8e566c22ea8" />

3. **Passbolt access via HTTP**  <img width="1270" height="849" alt="Screenshot 2025-10-11 235655" src="https://github.com/user-attachments/assets/2d8da7de-fcf0-4725-95dc-28b3bbe4da9c" />

4. **Password manager dashboard** <img width="2067" height="815" alt="Screenshot 2025-10-11 235615" src="https://github.com/user-attachments/assets/6d4bbf25-a6d8-47f7-bd0b-b8b3cca2bf0a" />
  

---

## 🧩 Key Takeaways
- Gained hands-on experience hosting a web application securely on AWS.  
- Understood cloud instance management, key-based SSH authentication, and domain configuration.  
- Learned how self-hosted password managers like Passbolt enhance data protection and credential control.  
- Identified the importance of implementing HTTPS for secure data transmission in production.

