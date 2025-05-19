# PDF_Summarizer 

A smart PDF summarization and Q&A application built using **Python**, **Streamlit**, and **Gemini API**. Upload a PDF or paste text, and the app will generate a summary and answer questions based on the content using Gemini's powerful AI capabilities.

---

##  Features

-  Upload PDF files or enter raw text
-  Get summarized content
-  Ask questions related to the uploaded content
-  Powered by Google's Gemini API
-  Interactive and simple UI powered by **Streamlit**

---

##  Requirements

- Python 3.7 or above
- Gemini API Key

---

##  Setup Instructions

### 1. Install Python

Make sure Python 3.7+ is installed on your system.  
Download it from: [https://www.python.org/downloads/](https://www.python.org/downloads/)

---

### 2. Create and Activate a Virtual Environment

### Create the environment:

```bash
python -m venv venv
```
### Install the dependencies
```
pip install streamlit
pip install google-generativeai
```
### Activate the virtual environment:
On Windows:
```
.\venv\Scripts\activate.bat
```
On macOS/Linux:
```
source venv/bin/activate
```
### 3.Add Gemini API Key
Before running the application, open the gemini_app2.py (or your main Streamlit file) and replace the placeholder with your Gemini API Key 
```
api_key = "YOUR_GEMINI_API_KEY"
```
##  Running the Application
To start the application, use the following command:

```bash
streamlit run gemini_app2.py
```
This will open the application in your default web browser, where you can:

- Upload a PDF file or enter custom text
- View a summary of the content
- Ask questions and receive precise answers powered by Gemini AI

##  How It Works
1. Upload a PDF file or enter text manually.
2. The app extracts the content using PyMuPDF.
3. Gemini API generates a summary and handles follow-up questions.
4. Everything is displayed interactively using Streamlit.

##  Notes
- Keep your Gemini API key private and secure.
- Ensure your internet connection is active.
- Clean, well-formatted PDFs provide better summarization results.

##  Acknowledgements
- Google Gemini API
- Python
- Streamlit

## Credits
Sana KS , Swapnil Sharma, Rishikesh Raj, Om Desai
