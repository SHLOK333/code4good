How to Run the Extension
Clone the Repository

bash
Copy code
git clone https://github.com/SHLOK333/Dark-Pattern-Detector-.git
cd Dark-Pattern-Detector-
Install Dependencies
Ensure you have Python and pip installed. Then, install the required packages:

bash
Copy code
pip install -r requirements.txt
Set Up Twilio API

Sign up for a Twilio account at Twilio.
Get your API key and phone number from the Twilio console.
Configure Environment Variables
Create a .env file in the project root and add your Twilio credentials:

env
Copy code
TWILIO_ACCOUNT_SID=your_account_sid
TWILIO_AUTH_TOKEN=your_auth_token
TWILIO_PHONE_NUMBER=your_twilio_phone_number
Run the Extension Locally

bash
Copy code
python app.py
Load the Extension in Your Browser

Open your browser’s extension management page.
Enable "Developer mode."
Click "Load unpacked" and select the directory where the project is located.
Using the Extension

Navigate to any website.
Click the extension icon and press the 'Detect' button.
Receive an SMS notification on your registered phone number with the detection results.
Feel free to reach out if you need further assistance running the extension or understanding its working.

 Built with
What languages, frameworks, platforms, cloud services, databases, APIs, or other technologies did you use?

* Built with
ChatGPT
Built With
Languages:

Python: For developing the machine learning model and backend functionality.
JavaScript: For building the browser extension and handling user interactions.
HTML/CSS: For the frontend of the browser extension.
Frameworks and Libraries:

Flask: For creating the backend server to handle requests and run the machine learning model.
Scikit-learn: For implementing and training the Naive Bayes model.
Gemini AI: For integrating advanced AI capabilities to enhance detection accuracy.
Twilio API: For sending real-time SMS notifications to users.
Platforms and Cloud Services:

GitHub: For version control and project repository.
Heroku: For deploying the backend server (if needed).
Databases:

SQLite: For storing user data and logs (optional, depending on the implementation).
APIs:

Twilio API: For sending SMS notifications to users.
Gemini API: For enhancing detection capabilities with advanced AI insights.
