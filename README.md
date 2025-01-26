# Virtual Healthcare Companion Chatbot

The **Virtual Healthcare Companion Chatbot** is a healthcare-focused, AI-powered conversational assistant designed to assist users with medical queries, provide health advice, and deliver personalized responses based on user interaction history. This chatbot incorporates voice interaction, autocorrect for input, and dynamic conversation history to offer an advanced, engaging user experience. It also integrates with the Google Gemini API for enhanced functionality.

## Project Overview

- **Technology Stack**: 
  - Frontend: HTML, CSS, JavaScript, Bootstrap
  - Backend: Django, Node.js, SQL/MongoDB
  - AI/NLP Libraries: NLTK, Gradio, Torch
  - External Integrations: Google Gemini API
- **Languages**: Python, JavaScript
- **Features**:
  - Personalized responses with chat history
  - Health-related greetings and responses
  - Error correction for user input
  - Separate modes for basic and advanced chat functions


## Features

1. **Chat History & User Profile**: Tracks previous interactions and tailors responses based on the user’s chat history.
2. **Text & Voice Interaction**: The chatbot can communicate via text or voice, making it accessible to a broader range of users.
3. **Health Recommendations**: Offers health-related advice based on symptoms.
4. **Error Correction**: Automatically corrects minor typos or mistakes in user input.
5. **Google Gemini Integration**: Provides enhanced responses using Google’s generative AI capabilities.
6. **AI-Driven Disease Prediction**: Leverages an RNN model to suggest possible conditions based on input symptoms.

## Getting Started

### Prerequisites

- Python 3.9 or higher
- Node.js
- MongoDB or SQL database
- Django framework
- Install dependencies from `requirements.txt`

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Naveen-YN/Virtual-Healthcare-Companion-Chatbot-Utilizing-NLTK.git
   cd virtual-healthcare-chatbot
   ```

2. **Install required packages**:

   ```bash
   pip install -r requirements.txt
   ```

3. **Set up the .env file**:

   Create a `.env` file in the root directory to securely store your API keys. Add the following:

   ```plaintext
   API_KEY=your-google-api-key
   ```

4. **Run database migrations**:

   ```bash
   python manage.py migrate
   ```

5. **Start the Django server**:

   ```bash
   python manage.py runserver
   ```

6. **Access the chatbot**:

   Open `http://127.0.0.1:8000` in your browser.

## Usage

1. Start chatting with the chatbot on the chat page.
2. Switch to **Advanced Mode** for enhanced chatbot capabilities.
3. **View Profile and Chat History** for personalized responses.

## API Usage

The project integrates with Google’s Gemini API. To use it, ensure your API key is correctly set up in the `.env` file.

## Future Scope

- **Enhanced Voice Interaction**: Further development for more intuitive voice-based responses.
- **Multilingual Support**: Expanding chatbot capabilities to support additional languages.
- **Mobile Application**: Developing a mobile version for increased accessibility.
- **Additional Health Metrics**: Incorporating additional health metrics for more precise predictions.

## Contact

For questions or collaboration opportunities, please contact [Naveen Yanamadala](mailto:naveenyd06@gmail.com) .
