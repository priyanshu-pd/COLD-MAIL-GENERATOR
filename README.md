

# 📧 Cold Email Generator

A cold email generator designed for service companies utilizing Groq, Langchain, and Streamlit. This tool allows users to input a company's careers page URL, extracts job listings, and generates personalized cold emails. These emails include relevant portfolio links sourced from a vector database based on specific job descriptions.

## 📝 Scenario Overview

Imagine a scenario where:

- **Company**: Nike
- **Position Needed**: Principal Software Engineer
- **Challenges**: Spending significant time and resources on the hiring process, onboarding, and training.
- **Solution Provider**: **Algosphere**, a software development company, can provide a dedicated software development engineer to Nike.
- **Contact Person**: **Priyanshu**, Business Development Executive from Algosphere, reaches out to Nike via a cold email.
- 
![Screenshot 2024-10-07 213941](https://github.com/user-attachments/assets/cff9ee0a-13ee-4e22-aff8-17f418419205)
![Screenshot 2024-10-07 214001](https://github.com/user-attachments/assets/d6b234d2-6578-4449-bd29-2e741be86948)



## 🏗️ Architecture Diagram

![Gem 42bcwe42bcwe42bc](https://github.com/user-attachments/assets/106719a0-8cec-4438-b99b-41cfbb2b9738)


## 🚀 Setup Instructions

### Step 1: Obtain API Key

To get started, you first need to obtain an API_KEY from [Groq Console](https://console.groq.com/keys). Once you have the API_KEY, update the value of `GROQ_API_KEY` in the `app/.env` file.

### Step 2: Install Dependencies

Run the following command to install the necessary dependencies:

```bash
pip install -r requirements.txt
```

### Step 3: Run the Streamlit App

Launch the application by executing:

```bash
streamlit run app/main.py
```

## 📬 Usage Instructions

- Input the URL of the desired company's careers page.
- The tool will extract job listings and generate personalized cold emails based on the specific job descriptions.
- Review and send the generated emails to potential clients.

## 🤝 Contributing

We welcome contributions to enhance this project.
