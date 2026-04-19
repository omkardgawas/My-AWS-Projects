# 📦 AWS S3 Advanced (Versioning + Lifecycle Policy)

## 📌 Project Overview

This project demonstrates advanced S3 features like versioning and lifecycle rules for backup and cost optimization.

---

## 🛠️ Services Used

* AWS S3

---

## 🚀 Steps Performed

1. Created S3 bucket
2. Uploaded file
3. Enabled versioning
4. Uploaded updated file (multiple versions created)
5. Configured lifecycle rule
6. Transitioned data to Glacier

---

🛠️ Steps to Restore
Go to the S3 bucket
Select the object (e.g., data.txt)
Enable "Show versions"
Locate the delete marker
Delete the delete marker

---

✅ Result
The previous version of the file becomes active again
The file is successfully restored

## 🔐 Key Features

* Version control for objects
* Data backup and recovery
* Cost optimization using lifecycle rules

---

## 📸 Screenshots

* Bucket creation
  <img width="1918" height="956" alt="image" src="https://github.com/user-attachments/assets/98d38c78-8a4a-49e8-8a6e-95d6da0281c0" />

* Versioning enabled
  <img width="1896" height="967" alt="image" src="https://github.com/user-attachments/assets/a3420f6f-1037-455d-88cf-a159f8767ebd" />

* Multiple versions
  <img width="1913" height="960" alt="image" src="https://github.com/user-attachments/assets/1bfe921e-8154-4299-b6a5-afe836e55679" />

* Lifecycle rule setup
  <img width="1901" height="963" alt="image" src="https://github.com/user-attachments/assets/f93e2093-b173-48f3-a7d5-4e4dcf0bfded" />

* Versioning (Delete and restore)
  Delete the file first then enable the toggle of Show Versions
  <img width="1918" height="922" alt="image" src="https://github.com/user-attachments/assets/900be8fc-c23a-43a1-babb-50e3dad519a9" />

Once you enable the toggle you will the 2 versions of file - 1. Delete marker, 2. verion 1
* Delete marker
  <img width="1918" height="927" alt="image" src="https://github.com/user-attachments/assets/9c3b69e3-e459-47f9-b725-91ad999eac27" />

* Multiple versions
  <img width="1918" height="918" alt="image" src="https://github.com/user-attachments/assets/3cd63966-b5a4-4f7d-8c47-50628133e9d3" />

* Restore action (Once we delete the marker version, the file gets restored)
  <img width="1918" height="965" alt="image" src="https://github.com/user-attachments/assets/f3bde196-fc54-4778-a30f-cea7bd0bb41c" />

---

## ⚠️ Challenges Faced

* Understanding version IDs
* Lifecycle configuration

---

## ✅ Learnings

* Data protection using versioning
* Cost-saving strategies in AWS
* Storage class management

---

## 🔥 Future Improvements

* Cross-region replication
* Automate backups
* Integrate with Lambda

---
