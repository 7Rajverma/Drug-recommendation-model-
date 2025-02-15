# Disease Prediction and Chatbot Web App

This is a Flask-based web application that predicts diseases based on user-inputted symptoms and provides additional information such as precautions, medications, diets, and workouts. The application also features an AI-powered chatbot.

## Features
- **Disease Prediction**: Predicts diseases based on symptoms using an SVM model.
- **Symptom Database**: Uses a dataset containing disease descriptions, precautions, medications, diets, and workouts.
- **AI Chatbot**: Integrated chatbot powered by Google Gemini AI for general health-related queries.
- **Flask Web App**: Built with Flask and deployed using Vercel.
- ![Screenshot 2025-02-15 235732](https://github.com/user-attachments/assets/f1d5b854-643c-4ea7-80c1-1128163fd7bd)
- ![Screenshot 2025-02-15 235747](https://github.com/user-attachments/assets/24694f15-b090-437a-bb04-01c2938aa6d9)
- ![Screenshot 2025-02-15 235832](https://github.com/user-attachments/assets/deb22284-5ad5-4492-a89d-3eedb07d1a86)
  ![Screenshot 2025-02-15 235846](https://github.com/user-attachments/assets/7efbaf40-a40e-4b9c-9ea0-0ff2450b1268)
  ![Screenshot 2025-02-15 235900](https://github.com/user-attachments/assets/fff9194f-41c0-40e3-a835-7963313f37a2)
  ![Screenshot 2025-02-15 235914](https://github.com/user-attachments/assets/a85e607e-e114-43dc-a3e4-569a074f07ab)
  ![Screenshot 2025-02-15 235926](https://github.com/user-attachments/assets/5f8d50bc-1842-4c04-930d-1a37344ed676),![Screenshot 2025-02-16 000004](https://github.com/user-attachments/assets/b5f92516-7fe6-431f-988b-4e320f09f1bf)









## Tech Stack
- **Backend**: Flask, Python
- **Frontend**: HTML, CSS (via templates)
- **Machine Learning**: SVM (Support Vector Machine) model
- **AI Model**: Google Gemini
- **Deployment**: Vercel

## Installation

### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Flask
- Pandas
- NumPy
- Pickle
- Google Generative AI SDK (`google-generativeai`)

### Steps
1. Clone this repository:
   git clone https://github.com/your-username/repository-name.git
   cd repository-name
   
2.Install dependencies:
   pip install -r requirements.txt
   Download or place the necessary dataset files inside the datasets folder.
   Ensure the trained model (svm.pkl) is placed inside the model directory.
   
3.Download or place the necessary dataset files inside the datasets folder.

4.Ensure the trained model (svm.pkl) is placed inside the model directory.

5.Run the Flask application:
   python app.py

6.Access the application at http://127.0.0.1:5000/.

### API Endpoints
  • / - Home page (disease prediction form)
  • /predict - Handles symptom input and returns a predicted disease
  • /chat_bot - Chatbot page
  • /chat - API endpoint for chatbot interaction
  • /about, /contact, /developer, /blog - Static informational pages

### Environment Variables
      You need to set up the API key for Google Generative AI: export GOOGLE_API_KEY="your-api-key-here"
      Alternatively, modify app.py and replace api_key="your-api-key-here".

### Contributing
      Contributions are welcome! Please open an issue or submit a pull request.

### License
      This project is licensed under the MIT License.



