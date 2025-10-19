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
1. **AWS EC2 instance dashboard** *(instance running and accessible)*  
2. **SSH terminal connection to Ubuntu server**  
3. **Passbolt setup interface**  
4. **Password manager dashboard** *(showing stored credentials)*  

---

## 🧩 Key Takeaways
- Gained hands-on experience hosting a web application securely on AWS.  
- Understood cloud instance management, key-based SSH authentication, and domain configuration.  
- Learned how self-hosted password managers like Passbolt enhance data protection and credential control.  
- Identified the importance of implementing HTTPS for secure data transmission in production.

