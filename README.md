# AI-Powered-QA-system-using-LangChain-and-Dynamic-Feedback-Mechanism
Welcome to the FAQ Assistant! This tool is your go-to solution for quickly finding answers to frequently asked questions. It combines powerful AI with a simple, user-friendly interface to make your search fast and effective.

🚀 Features
Smart Search: Uses advanced AI to understand your questions and find the best answers.
Easy to Use: Just type a question and get an answer !
Feedback Options: Let the assistant know if the answers are helpful.
Customizable: Add your own FAQ data to make it work for your needs.
🛠️ How It Works
You Ask: Type a question in the search box.
AI Searches: The assistant uses AI to find the most relevant answer from the FAQ database.
You Get Answers: View the response in an easy-to-read format.
Provide Feedback: Help improve the assistant by rating the answers.
📦 Installation
Step 1: Install Python
Make sure you have Python 3.10 or later installed. You can download it from python.org.

Step 2: Clone the Project
Download the FAQ Assistant files:

bash
Copy code
git clone https://github.com/TejashreeBetgar/AI-Powered-QA-system-using-LangChain-and-Dynamic-Feedback-Mechanism.git
cd faq-assistant
Step 3: Install Dependencies
Run this command to install all the required tools:

bash
Copy code
pip install streamlit
pip install faiss-cpu
pip install sentence-transformers
pip install google-generativeai
pip install pyngrok
Step 4: Add Your Google API Key
Get a Google Generative AI API key and add it to the code by replacing "your-google-palm-api-key" with your actual key in the app.py file.

🏃‍♂️ Running the App
Start the app with this command:

bash
Copy code
streamlit run app.py
Open your web browser and go to http://localhost:8501.

Start asking your questions and enjoy!

📋 Adding Your FAQs
Create a CSV file with two columns:

Question: The common question someone might ask.
Answer: The response to the question.
Save it as codebasics_faqs.csv and place it in the project folder.

🛠️ Troubleshooting
Nothing Happens When I Run the App: Make sure Python and all required tools are installed.
Getting Incorrect Answers: Add more relevant FAQs to the dataset for better results.
Port is Busy: Try a different port:
bash
Copy code
streamlit run app.py --server.port=8502
