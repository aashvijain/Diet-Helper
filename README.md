# Diet Helper

> **Note:** This project is still a work in progress and I plan to enhance it in the future.

This is a Streamlit web application that analyzes images of nutrition charts and helps users choose the right diet using OpenAI's GPT-4o model via LangChain.

## Features
- Upload two images of nutrition charts.
- Enter a question about your diet or nutrition.
- Get AI-powered analysis and suggestions based on the uploaded images and your question.
- Powered by OpenAI and LangChain.

## Requirements
- Python 3.8+
- [Streamlit](https://streamlit.io/)
- [LangChain](https://python.langchain.com/)
- [langchain-openai](https://python.langchain.com/docs/integrations/llms/openai)
- [python-dotenv](https://pypi.org/project/python-dotenv/)

## Setup
1. **Clone the repository**
2. **Install dependencies:**
   ```bash
   pip install streamlit langchain langchain-openai python-dotenv
   ```
3. **Create a `.env` file** in the project root with your OpenAI API key:
   ```env
   OPENAI_API_KEY=your_openai_api_key_here
   ```
4. **Run the app:**
   ```bash
   streamlit run diet_helper.py
   ```

## Usage
- Upload two nutrition chart images (JPG, JPEG, or PNG).
- Enter your diet or nutrition question.
- The app will display AI-generated analysis and suggestions.

