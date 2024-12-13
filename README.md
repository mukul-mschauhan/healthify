# healthify
We are creating a Healthcare Repository whose job is to advice user about Health, Disease &amp; Fitness

### Steps
1. Clone the Repository in the folder using cmd ``git clone https://github.com/mukul-mschauhan/healthify.git``
2. Create the Virtual Environment by using cmd ``python -m venv .venv``
3. Activate the virtual environment cmd ``source .venv/bin/activate``
4. Create a **requirements.txt** file and install the requirements.

### Github
1. git init
2. git add .
3. git commit - m "Final-Commit"
git push origin main

#### Healthcare Advisor

This Streamlit app leverages Google's Generative AI to provide health information and a BMI calculator.

* **Prerequisites:**

- Google GeminiAccount: Create a Google Gemini account and enable the Generative AI API.
- API Key: Obtain an API key and store it in a .env file.

* **Installation:**

- Clone this repository.
- Install required libraries:

* **Run the Application:**
``streamlit run app.py``
* How to Use:
- Ask Questions: Enter your health-related query in the text box.
- Submit: Click the "Submit" button.
- Get Answers: The AI will provide a comprehensive response.
- Calculate BMI: Input your weight and height in the sidebar.
- Interpret BMI: The app will display your BMI category.