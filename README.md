# 💬 Dynamic Contact Form with MySQL Database Integration

Welcome to the **PHP Contact Form with MySQL Database Integration** project! 🚀  
This project demonstrates how to create a fully functional and stylish contact form that collects user data (Name, Email, Website, Comment, and Gender) and stores it securely into a MySQL database using **PHP with Prepared Statements**.

---

## 📌 Project Highlights

✅ Clean and responsive contact form layout using **HTML & CSS**  
✅ Backend integration with **PHP & MySQL**  
✅ Secure database operations with **prepared statements** (prevents SQL injection)  
✅ Encodes form data like emojis and links successfully  
✅ User-friendly interface with clear feedback on successful submission  
✅ All collected data displayed in a **MySQL table** (neatly organized)

---

## 🛠 Technologies Used

- 💻 Frontend: HTML5, CSS3
- ⚙️ Backend: PHP
- 🗄 Database: MySQL (with AWS RDS support)
- 🔒 Security: mysqli prepared statements

---

## 📸 Screenshots

### 📝 Form UI

![Screenshot 2025-05-16 164542](https://github.com/user-attachments/assets/81d481ae-84f5-4967-9f00-aa655221a3b4)

### 📥 Stored Data in MySQL
![Database Output](./screenshots/database_view.png)

---

## ⚙️ How it Works

1. **User fills out the contact form.**
2. **Form submits data via POST to the PHP script.**
3. **PHP connects to the MySQL database (AWS RDS in this case).**
4. **Data is inserted using a prepared SQL statement.**
5. **Confirmation message is displayed to the user.**

---

## 🔧 Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/contact-form-php-mysql.git
   cd contact-form-php-mysql
Configure database credentials in form-handler.php:

Configure database credentials in form-handler.php:
$servername = "your-database-endpoint";
$username = "your-username";
$password = "your-password";
$dbname = "your-database-name";

Import the users table structure:
CREATE TABLE users (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(100),
  email VARCHAR(100),
  website VARCHAR(100),
  comment TEXT,
  gender VARCHAR(10)
);

Run the project on a local or remote server with PHP support.

🧠 Learnings
Through this project, you’ll get hands-on experience with:

Creating interactive web forms

PHP-MySQL integration

Form validation & secure data handling

Debugging with error reporting

Using cloud-based MySQL solutions (like AWS RDS)

💡 Future Enhancements
Add CAPTCHA to prevent spam bots

Validate input data with JavaScript before submission

Add support for file attachments

Enable email notification on new submission

📫 Contact
If you liked this project or have any queries, feel free to connect!

LinkedIn: Om Aravelliwar

Email: aravelliwarom@gmail.com



