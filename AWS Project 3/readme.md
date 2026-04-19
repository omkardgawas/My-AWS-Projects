# 🔐 AWS IAM Security Setup (Users, Groups, Policies)

## 📌 Project Overview

This project demonstrates how to securely manage access in AWS using IAM.

---

## 🛠️ Services Used

* AWS IAM (Identity and Access Management)

---

## 🚀 Steps Performed

1. Created IAM user
2. Created IAM group (Developers)
3. Attached policy (AmazonS3FullAccess)
4. Added user to group
5. Logged in as IAM user
6. Tested permissions

---

## 🔐 Key Concepts

* Least Privilege Principle
* Role-based access control
* Secure AWS account management

---

## 📸 Screenshots

* IAM user creation
  <img width="1898" height="966" alt="image" src="https://github.com/user-attachments/assets/d0f01e15-f0b7-4835-898b-dfadde3cec3c" />

* Group creation
  <img width="1918" height="962" alt="image" src="https://github.com/user-attachments/assets/999d30b7-9af8-47aa-bc77-04cadb3324ef" />

* Policy attachment
  <img width="1895" height="961" alt="image" src="https://github.com/user-attachments/assets/ac35d094-abdc-412e-85b0-54670719ea7c" />

* Login as IAM user
  <img width="1918" height="960" alt="image" src="https://github.com/user-attachments/assets/5f779278-f86d-40bd-a968-53d9bf5b017d" />

  User can only access Amazon S3, not other services like EC2 as it doesn't have the permissions/access
   * Can access S3, can create S3 bucket
     <img width="1918" height="960" alt="image" src="https://github.com/user-attachments/assets/326a48fe-fbb6-4dc0-8995-a943a065902d" />
     
     ---
     <img width="1918" height="953" alt="image" src="https://github.com/user-attachments/assets/bab8a7d0-c826-4de3-9d20-2f340eae0264" />

   * Cannot access any other services of AWS, for example - EC2
     <img width="1916" height="962" alt="image" src="https://github.com/user-attachments/assets/93b8da53-b159-42ca-bd53-a3fdbbf1fdfa" />



---

## ⚠️ Challenges Faced

* Understanding policies vs roles
* Permission testing

---

## ✅ Learnings

* Secure access management
* Difference between users, groups, and roles
* Importance of IAM in real-world AWS

---

## 🔥 Future Improvements

* Create custom policies
* Implement IAM roles for EC2
* Enable MFA (Multi-Factor Authentication)

---
