# AWS-hosted Virtual Classroom and Learning Platform

## Project Overview

This project is a **cloud-native virtual classroom** web application built using the Flask framework and hosted on AWS. It demonstrates the integration of core AWS services (EC2, S3, and RDS) to provide a secure, scalable, and responsive platform for digital learning.


Students can register, log in, and access course materials, while administrators can upload and manage content. The project emphasizes modern cloud deployment practices and full-stack development.

---

## Folder Structure

```
AWS-hosted-Virtual-Classroom-and-Learning-Platform/
├── Documentation/
│   └── Final document.pdf
├── static/
├── templates/
│   ├── content.html
│   ├── home.html
│   ├── login.html
│   └── register.html
├── app.py
├── README.md
├── requirements.txt
└── tempCodeRunnerFile.py
```

---

## Technologies Used

- **Backend:** Python, Flask  
- **Frontend:** HTML, CSS, JavaScript, Bootstrap  
- **Database:** MySQL (AWS RDS)  
- **Cloud Services:** AWS EC2, S3, RDS  
- **Other Tools:** Git & GitHub, MySQL Workbench, boto3

---

## Screen Shots

### Home Page:
![Home Page](https://drive.google.com/file/d/1Fkf7EaEOVU4aEnIghNhLh1g3LgzDwvPY/view?usp=drive_link)

### Registration Page:
![Registration Page](https://drive.google.com/file/d/1iBa6t61ZnNmeEYPdiXOdgCLEYb_K-Hvn/view?usp=drive_link)

### Login Page:
![Login Page](https://drive.google.com/file/d/1WbT0Z1VokSl8llHCh_a4IT_hGIjha2x2/view?usp=drive_link)

### Content Page:
![Content Page](https://drive.google.com/file/d/1eoSSBu0e9Thwir0HYvlVUC54bPC710qh/view?usp=drive_link)


---

## System Architecture

1. **Frontend:** HTML/CSS/JS served via Flask templates
2. **Backend:** Flask APIs managing user and file routes
3. **Storage:** PDFs stored in S3
4. **Database:** User and file metadata stored in RDS (MySQL)
5. **Deployment:** Flask app hosted on EC2 

---

## Project Workflow

1. **Create and Configure AWS Services:**
   - AWS Account, S3 Bucket, RDS MySQL, EC2 Instance
2. **Develop Flask App:**
   - Build register/login routes
   - Create templates: `home.html`, `register.html`, `login.html`, `content.html`
   - Connect to S3 using `boto3` and to RDS using `pymysql`
3. **Deploy Application:**
   - SSH into EC2, clone GitHub repo, install dependencies
   - Run Flask app using evelopment server
4. **Push Code to GitHub**

---

## 👨‍🏫 User Scenarios

### Student Registration and Login
- Registers via web form, logs in, accesses course content stored on S3.

### Admin Uploads Content
- Uploads PDFs or videos to S3 with metadata stored in RDS.

### Student Downloads Content
- Clicks a file link to download directly from S3.
  
---

## ✅ Conclusion

This project showcases how web applications can be effectively deployed and scaled using AWS. With Flask at its core and AWS services powering the backend, it provides a modern, secure, and user-friendly experience for online learning platforms.

---

## 🔗 Demo and Source Code

- 🎥 [Demo Video](https://drive.google.com/file/d/1U5NBc5tMXtcSPINr82e8SfLwHIV9WtaZ/view?usp=drive_link)
- 🧾 [GitHub Repository](https://github.com/sanika0304/AWS-hosted-Virtual-Classroom-and-Learning-Platform.git)
