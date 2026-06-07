🚀 QR Code Generator

A modern and user-friendly QR Code Generator built using HTML, CSS, JavaScript, PHP, MySQL, and QRCode.js. Users can generate QR codes from text or URLs, download them instantly, and manage QR history stored in a MySQL database.

🌐 Live Demo

https://iriteshtech.github.io/QR-Code-Generator/

---

📌 Features

✅ Generate QR Codes from Text or URLs

✅ Multiple QR Size Options

✅ Instant QR Preview

✅ Download Current QR Code

✅ QR History Management

✅ Store QR History using PHP & MySQL Database

✅ Show QR Preview in History Table

✅ Save Date & Time of Generated QR Codes

✅ Download QR Codes from History

✅ Clear QR History

✅ Responsive and Modern UI

✅ Unique Filename for Downloaded QR Codes

---

🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- PHP
- MySQL
- QRCode.js Library

---

## 📷 Screenshots

### 🏠 Home Page

![Home Page](screenshots/home-page.png)

### ⚡ QR Generated

![QR Generated](screenshots/qr-generated.png)

### 📜 QR History

![QR History](screenshots/qr-history.png)

---

⚙️ How to Run

Method 1: Run Locally

1. Clone the Repository

git clone https://github.com/iRiteshTech/QR-Code-Generator.git

2. Open Project Folder

QR-Code-Generator

3. Start XAMPP

Start:

- Apache
- MySQL

4. Create Database

Database Name:

qr_generator

5. Create Table

CREATE TABLE qr_history (
    id INT AUTO_INCREMENT PRIMARY KEY,
    text_url VARCHAR(500) NOT NULL,
    qr_image LONGTEXT NOT NULL,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);

6. Move Project to htdocs

C:\xampp\htdocs\QR-Code-Generator

7. Open Browser

http://localhost/QR-Code-Generator/

8. Generate QR

- Enter any Text or URL
- Select QR Size
- Click Generate QR
- Download QR Code
- View QR History

---

📂 Project Structure

QR-Code-Generator/
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── backend/
│   ├── db.php
│   ├── save_qr.php
│   ├── get_history.php
│   ├── clear_history.php
│   └── index.php
│
├── screenshots/
│   ├── home-page.png
│   ├── qr-generated.png
│   └── qr-history.png
│
├── README.md
│
└── .gitattributes

---

🎯 Future Improvements

- User Login & Registration
- QR Logo Support
- Custom QR Colors
- Dark Mode
- Export History as CSV
- QR Scan Feature

---

👨‍💻 Author

Ritesh Raj Tiwary

Computer Science Student | Power BI Developer | Java Developer | Web Developer

GitHub: https://github.com/iRiteshTech

---

⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

📊 Project Status

✅ Frontend Completed

✅ Backend Completed

✅ MySQL Database Integrated

✅ QR History Implemented

✅ Download Functionality Added

✅ GitHub Repository Published

✅ GitHub Pages Deployed

✅ README Documentation Completed

🚀 Project Ready for Internship Submission
