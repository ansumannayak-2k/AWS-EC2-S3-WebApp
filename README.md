# AWS EC2 + S3 Static Web App

This project demonstrates a simple static website deployed on an AWS EC2 instance using Node.js and Express.js, while serving images from an Amazon S3 bucket. The goal is to showcase foundational AWS Cloud Engineer skills including EC2 provisioning, S3 integration, IAM configuration, and remote server access using a key pair.

---

## 🚀 Features

* Deployed Node.js application on an EC2 instance (Ubuntu 22.04)
* Hosted static HTML content (`completion.html`) served using Express
* Linked 3 publicly accessible images hosted on Amazon S3
* Configured EC2 instance with custom security group and IAM role
* Connected and deployed via SSH using a key pair
* Project files tracked and version-controlled with Git & GitHub

---

## 🧰 Technologies & AWS Services Used

* **Amazon EC2** (Ubuntu 22.04)
* **Amazon S3** (Image Hosting)
* **IAM Roles & Security Groups**
* **Node.js + Express.js**
* **SSH + Key Pair Access**
* **Git & GitHub**

---

## 📁 Folder Structure

```
AWS-EC2-S3-WebApp/
├── app.js                 # Node.js server
├── completion.html       # HTML frontend with image gallery
├── package.json
├── package-lock.json
├── .gitignore            # Excludes node_modules
└── README.md             # Project overview
```

---

## 🌐 Live Access

To view the app, visit:

```
http://54.167.159.56
```

---

## 📸 Screenshots

### Terminal: Node & npm Versions  
![Node Versions](https://github.com/user-attachments/assets/bbc8488d-e511-43b9-a1b7-4ea858ff0b25)

### Web App on EC2  
![Web App](https://github.com/user-attachments/assets/84fe817d-0a8e-4df9-8f89-143ab59bfe57)

### EC2 Dashboard  
![EC2 Running](https://github.com/user-attachments/assets/00c175c0-b00e-47f8-8067-50e37d1021de)

### S3 Images Loaded  
![S3 Images](https://github.com/user-attachments/assets/f5d0104e-207c-4db0-be21-7b96778ad0ab)

---



## ✅ Steps Followed (Quick Summary)

1. Setup local Node.js app with HTML gallery
2. Launch EC2 instance and SSH into it
3. Upload project files and run the app
4. Create S3 bucket, upload images, set public access
5. Link image URLs to `completion.html`
6. Push code to GitHub repository

---

## ✍️ Author

**Ansuman Nayak**
GitHub: [@ansumannayak-2k](https://github.com/ansumannayak-2k)

---

## 📢 License

This project is for educational and portfolio purposes. Free to use and adapt.

