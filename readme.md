# US Traffic Congestion Analysis (2016–2022)

## 📥 Download Dataset
🔗 [US Traffic Congestions (2016-2022)]([link_to_your_file_here](https://www.kaggle.com/datasets/sobhanmoosavi/us-traffic-congestions-2016-2022/data))  

## 🔄 Reproduction Guide

### 1. Create GCP Project
- Log in to the **Google Cloud Platform (GCP)** Console.
- Create a new project and save the **Project ID**.

### 2. Configure Service Account
- Navigate to **IAM & Admin > Service Accounts**.
- Create a service account and grant the following roles:
  - `BigQuery Data Editor`
  - `BigQuery User`

### 3. Export & Store Credentials
- Generate a **JSON Key** for the service account.
- Save the JSON file securely. It will be used for both local script execution and **Tableau** authentication.

### 4. Set Environment Variable
```bash
export GOOGLE_APPLICATION_CREDENTIALS="/path/to/your/service-account-key.json"
```
- Also setup Google Colab Secret 
'GCP_PROJECT_ID' -> Your_GCP_Project_ID
