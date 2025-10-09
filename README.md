# 🔐 Password Management System in AWS (Passbolt)

## 🎯 Objective
To securely host and manage complex passwords in the cloud using **Passbolt**, leveraging **AWS infrastructure** for scalability, security, and accessibility.

---

## 🧰 Tools & Technologies Used
- **Passbolt** (self-hosted password manager)
- **AWS EC2** (virtual server hosting)
- **AWS Route 53** (domain hosting and DNS management)
- **Nginx** (web server)
- **Let’s Encrypt / Certbot** (SSL certificate setup)
- **HTTPS Encryption**

---

## ⚙️ Steps Performed

1. **Provisioned an EC2 Instance**
   - Launched an Ubuntu-based EC2 instance on AWS.
   - Configured inbound security groups for HTTP (80), HTTPS (443), and SSH (22).

2. **Installed and Configured Passbolt**
   - Deployed **Passbolt CE (Community Edition)** on the EC2 instance.
   - Configured the database, PHP, and Nginx dependencies.
   - Verified successful installation and access through the server’s public IP.

3. **Secured with HTTPS**
   - Installed **Certbot** to enable **SSL encryption** for the Passbolt domain.
   - Enforced HTTPS redirection in Nginx configuration.

4. **Configured Domain and DNS**
   - Purchased or configured a domain name via **AWS Route 53**.
   - Linked the EC2 instance’s public IP to the domain’s A record.
   - Ensured accessibility via the domain (e.g., `https://passwordvault.example.com`).

5. **Implemented Password Management Features**
   - Configured user accounts and groups within Passbolt.
   - Demonstrated secure creation, storage, and sharing of complex passwords.
   - Verified encryption during transmission and storage.

6. **Maintenance and Monitoring**
   - Set up instance monitoring through AWS CloudWatch.
   - Regularly updated the Passbolt instance and SSL certificates for continued security.

---

## 📸 Screenshots

Include **4–5 concise screenshots** showing the most relevant parts of your project:

| Screenshot | Description |
|-------------|--------------|
| ![EC2 Dashboard](./images/aws-ec2-instance.png) | AWS EC2 instance running Passbolt |
| ![Passbolt Login Page](./images/passbolt-login.png) | Secure login interface via HTTPS |
| ![Passbolt Dashboard](./images/passbolt-dashboard.png) | Password management dashboard |
| ![Certbot SSL Confirmation](./images/ssl-setup.png) | SSL/HTTPS successfully configured |
| ![AWS Route 53 Configuration](./images/aws-route53.png) | Domain pointing to Passbolt instance |

💡 *Avoid showing sensitive data such as domain names, internal IPs, or credentials.*

---

## 🔒 Security Highlights

- Enforced HTTPS encryption for secure communication.
- Hosted Passbolt in a controlled AWS environment with strict security group rules.
- Used **self-hosted** architecture to eliminate third-party password storage risks.
- Enhanced data protection and operational availability via AWS services.

---

## 🧩 Key Takeaways

- Gained practical experience deploying and securing a self-hosted web application in AWS.
- Strengthened understanding of encryption, domain configuration, and cloud resource management.
- Built confidence in maintaining secure, accessible cloud-based applications.

---

## 🧰 Next Steps (Optional Improvements)

- Automate SSL renewal with a cron job.  
- Implement AWS Backup for EC2 snapshots.  
- Integrate AWS IAM for user-based access control.  
- Add MFA and logging to enhance overall system security.
