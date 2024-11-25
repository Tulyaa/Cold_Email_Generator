# 📧 Cold Email Generator

**Cold Email Generator** is a Streamlit-based application that automates the creation of personalized and professional emails. It is designed for job applications, follow-ups, and professional networking, leveraging AI and ChromaDB to create highly relevant and engaging email drafts.

## Features

- **Dynamic Email Purposes**: Generate emails for:
  - Job Inquiries
  - Application Follow-ups
  - Professional Networking
- **Customizable Email Tone**: Choose from `Formal`, `Casual`, or `Friendly` tones for a personalized communication style.
- **Job Description Parsing**: Extracts structured job details from URLs for precise email generation (for Job Inquiry and Application Follow-up purposes).
- **Portfolio Integration**: Uses ChromaDB to match skills and projects from your portfolio to the email's purpose.
- **Networking Emails**: Generate professional networking emails without requiring a Job URL.

## Technologies Used

- **Python**: Core programming language.
- **Streamlit**: For an interactive user interface.
- **LangChain**: Manages the AI pipeline for text generation.
- **LLM (Large Language Models)**: Generates email content.
- **WebBaseLoader**: Parses content from job pages (for Job Inquiry and Application Follow-up).
- **ChromaDB**: Vector database for efficient portfolio queries.

## Prerequisites

Ensure the following are installed:

- **Python 3.8+**
- **pip** (Python package manager)
- **Streamlit**
- **LangChain**
- **ChromaDB**
- **dotenv**

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Tulyaa/Cold_Email_Generator.git
   cd cold-email-generator
   
2.Install required dependencies:
pip install -r requirements.txt

3.Set up environment variables:
Create a .env file in the project directory.
Add your API key for the language model:
GROQ_API_KEY=your_groq_api_key

## Screenshots
![Screenshot (315)](https://github.com/user-attachments/assets/21422328-8a06-4266-a80c-63b0d0785e83)
![Screenshot (316)](https://github.com/user-attachments/assets/ef8e2f88-22f9-4e06-9fac-9dec3b0095c8)


