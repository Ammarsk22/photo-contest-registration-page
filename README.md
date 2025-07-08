✅ Updated & Polished README.md
markdown
Copy
Edit
# 📸 Photo Contest Registration Page

**Developer:** Ammar Shaikh  
**Project Type:** Photo Contest Registration with Certificate Generation  
**Hosted on:** [GitHub Pages](https://ammarsk22.github.io/photo-contest-registration-page/)  

---

## 📖 Overview

A modern, responsive **Photo Contest Registration Website** where users can register by submitting their photo and personal details.  
After successful registration, users can **instantly download a personalized certificate** (PDF) featuring their name, category, and photo title — all dynamically generated using JavaScript and jsPDF.

---

## 🎯 Features

- 🖼️ Real-time photo preview
- 📱 Responsive and user-friendly UI
- 📞 Form validation (phone, email, age, photo size, etc.)
- 🗂️ LocalStorage-based participant table with delete option
- 🧾 Dynamic certificate generation using `jsPDF`
- 📄 Certificate includes full name, category, and photo title

---

## 📂 Folder Structure

photo-contest-registration-page/
│
├── index.html # Main HTML page
├── style.css # Custom styling
├── bg.jpg # Background image
├── images/
│ └── certificate-template.png.jpg # Photoshop-designed certificate

yaml
Copy
Edit

---

## 🧰 Tech Stack

| Technology | Purpose                             |
|------------|-------------------------------------|
| HTML5      | Page Structure                      |
| CSS3       | Layout & Styling                    |
| JavaScript | Interactivity, Validation, jsPDF    |
| jsPDF      | Generate downloadable certificate   |
| Git & GitHub | Version Control + Hosting         |

---

## 📜 How it Works

1. 📋 User fills out the registration form (with all details).
2. ✅ On form submit:
   - Entry is added to participant table.
   - A success message is shown.
   - A **“Download Certificate”** button appears.
3. 🧾 User clicks the button → Personalized PDF certificate is generated and downloaded.

---
🖼️ Screenshots

🧾 Registration Form
![image](https://github.com/user-attachments/assets/f62d321b-8a32-4105-abad-d6dfddafc384)

Certificate Download

---
## 🚀 Deployment Instructions

To run locally:

```bash
git clone https://github.com/ammarsk22/photo-contest-registration-page.git
cd photo-contest-registration-page
Open index.html in your browser
🌐 Live Demo
🔗 Click Here to View on GitHub Pages

✍️ Author
Ammar Shaikh
📧 ammarsk200422@gmail.com
🌐 GitHub Profile

📌 Future Enhancements
🎯 Add certificate email delivery

🗃️ Backend database for participant storage (e.g. Firebase)

🎨 Upload preview gallery

🥇 Auto-winner selection & special certificate

📄 License
This project is for educational and portfolio purposes only.
