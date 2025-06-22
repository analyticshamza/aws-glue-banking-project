# aws-glue-banking-project
This project demonstrates how to set up a simple data management infrastructure using **AWS Glue**, **S3**, and **IAM** for processing and transforming banking transaction data.

---

## 📌 Objective

Set up an AWS-based data pipeline to manage customer transaction data:
- Use Amazon S3 for data storage
- Use IAM for secure access control
- Use AWS Glue for potential transformation and analysis

---

## 🚀 Steps Performed

### 1. S3 Setup
- Created bucket: `transactiondatamanagement`
- Created two folders: `rawdata` and `processeddata`
- Uploaded sample csv data `banking-txn.csv`  to `processeddata`

### 2. IAM Role for Glue
- Created IAM Role `BankAdmin`
- Assigned AWS Glue as trusted service
- Granted `AdministratorAccess` permissions

---

## 🖼️ Screenshots

All key steps are documented below:

| Step | Screenshot |
|------|------------|
| S3 Bucket Creation | ![Image](https://github.com/user-attachments/assets/45fe85e6-c3ba-4bef-a99d-e2c86755cbca) |
| Folder Creation | ![Image](https://github.com/user-attachments/assets/ba90b8a3-026c-4fd3-b804-689c0c14a531) |
| File Upload | ![Image](https://github.com/user-attachments/assets/cf61cf1a-422e-49b9-81a7-facfe5915b87) |
| IAM Console Start | ![Image](https://github.com/user-attachments/assets/ff399572-4449-4990-8eba-869a9cc63648) |
| IAM Glue Role Setup | ![Image](https://github.com/user-attachments/assets/7ea34129-a8b9-4a4b-bac3-38f80f8d7b78) ![Image](https://github.com/user-attachments/assets/7f0dfdda-28ae-4462-95e5-8495b745548a) |
| BankAdmin Role Created | ![Image](https://github.com/user-attachments/assets/e43c70ec-38ca-4850-ac88-c195342be772) |
