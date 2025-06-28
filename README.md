# 1SecTools 🔐  
A Privacy-First Web Toolkit — Temporary Email, Encrypted Notes, URL Shortener, PDF Tools & More

> ⚠️ This is a **restricted project**. The code is provided for reference only. Commercial use, redistribution, or modification is **not allowed** without permission.

---

## 🌐 Live Demo

🔗 [https://1sectools.infy.uk](https://1sectools.infy.uk)

---

## 🧰 About 1SecTools

**1SecTools** is a comprehensive web-based toolkit offering multiple utilities to boost privacy, productivity, and simplicity. From generating temporary emails to sharing encrypted notes and files, this suite provides fast, secure alternatives to everyday online tools — all under one unified interface.

Designed with privacy and security in mind, **some tools are fully client-side encrypted**, ensuring data stays in your hands only.

---

## 🔍 Key Features

### 🔐 Security & Privacy Tools
- **Encrypted Note Sharing** – Create self-destructing, client-side encrypted notes.
- **Encrypted Personal Drive** – Upload and retrieve encrypted files.

### 📬 Communication & Sharing
- **Temporary Email Generator** – Instantly receive throwaway emails.
- **Secure Text Sharing** – Share notes or code with encryption and expiration options.

### 🔗 URL & Cloud Utilities
- **URL Shortener** – Clean and trackable short links.
- **Google Drive Direct Download Generator** – Convert shareable links to direct downloads.

### 📄 File & Document Tools
- **Webpage to PDF Converter** – Save any website as a downloadable PDF.
- **Paste Text / Share Code Snippets** – Secure, minimal paste tool for developers or notes.

---

## 💻 Tech Stack

| Layer         | Technologies Used                      |
|---------------|----------------------------------------|
| Frontend      | HTML5, CSS3, JavaScript                    |
| Backend       | PHP         |
| Database      | MySQL       |
| Security      | Client-side |
| Hosting       |Infinity free|

---

## 📦 Installation Guide (For Self-Hosting)

```bash
# Step 1: Clone the Repository
git clone https://github.com/mdshahadath319/1sectools.git
cd 1sectools

# Step 2: Configure the Backend
- Import `database.sql` into your MySQL server
- Edit `config.php` with your DB credentials and base URLs

# Step 3: Set Permissions
Ensure your `uploads/` or `storage/` folders are writable by the web server.

# Step 4: Deploy
Upload to your PHP-supported hosting platform.
