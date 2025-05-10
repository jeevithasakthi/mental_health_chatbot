# mental_health_chatbot
The Multilingual Mental Health Chatbot is a rule-based AI assistant designed to offer 24/7 support for individuals facing emotional or psychological challenges. Built using Python and Flask, the chatbot utilizes speech recognition for voice input and Google Translate for multilingual communication, enabling users to interact in their native language. Unlike complex neural networks, this system relies on predefined responses, ensuring fast, predictable, and consistent replies to common mental health-related queries. The chatbot is cost-effective, easy to deploy, and ideal for educational, support, or outreach purposes.
# 🧠 Multilingual Mental Health Chatbot

A rule-based, multilingual chatbot designed to provide 24/7 mental health support. This chatbot offers cost-effective and time-efficient assistance through voice and text inputs, breaking language barriers to ensure accessibility for diverse users.

## 🌟 Features

- 🌐 **Multilingual Support**: Communicates in multiple languages using Google Translate API.
- 🎤 **Voice Input**: Accepts user queries through speech recognition.
- 🕒 **24/7 Availability**: Always online to assist users at any time.
- 💸 **Cost-Effective**: Utilizes open-source tools and APIs to minimize costs.
- ⚡ **Time-Efficient**: Provides quick responses through a rule-based system.
- 🧠 **Rule-Based Responses**: Delivers predefined answers for consistent support.

## 🛠️ Tech Stack

- **Backend**: Python, Flask
- **Voice Recognition**: SpeechRecognition library
- **Translation**: googletrans==4.0.0-rc1
- **Rule-Based Logic**: Predefined intents and responses
- **Deployment**: Compatible with platforms like Heroku, Render, or local servers

## 🚀 Getting Started
### Prerequisites

- Python 3.x
- pip (Python package installer)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/mental-health-chatbot.git
   cd mental-health-chatbot
Install the required packages:

bash
Copy
Edit
pip install flask torch transformers googletrans==4.0.0-rc1
Run the application:

bash
Copy
Edit
python app.py
Access the chatbot:

Open your browser and navigate to http://localhost:5000.

🧪 How It Works
User Interaction: The user inputs a message via text or voice.

Language Detection: The input language is detected.

Translation: If necessary, the message is translated to English.

Response Generation: The system matches the input to predefined intents and retrieves the corresponding response.

Output Delivery: The response is translated back to the user's language (if needed) and presented via text or synthesized speech.

🤝 Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

📄 License
This project is licensed under the MIT License.

🙏 Acknowledgements

SpeechRecognition Library
Googletrans Library
Flask Framework

IMPLEMENTATION:
step1: copy the code
step2: put it in vs code or any other compiler
step3: run the code
step4: install googletrans
step5: run again your pcode(python ap.py)
step6: the application will run on http://localhost:5000
