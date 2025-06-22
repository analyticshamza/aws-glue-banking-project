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
| S3 Bucket Creation | ![S3 Bucket](screenshots/01_s3_bucket_created.png) |
| Rawdata Folder | ![Rawdata](screenshots/02_rawdata_folder.png) |
| Processeddata Folder | ![Processeddata](screenshots/03_processeddata_folder.png) |
| File Upload | ![Upload](screenshots/04_file_uploaded.png) |
| IAM Console Start | ![IAM Start](screenshots/05_iam_start.png) |
| IAM Glue Role Setup | ![IAM Glue](screenshots/06_iam_glue_role.png) |
| BankAdmin Role Created | ![BankAdmin](screenshots/07_bankadmin_created.png) |
