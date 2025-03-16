# ChatGPT-Powered Terminal Chatbot  

A simple interactive chatbot using OpenAI’s GPT-3.5-turbo model.  

## Features  
- Chat with GPT in the terminal  
- Exit anytime by typing **"quit"**, **"exit"**, or **"bye"**  
- Lightweight and easy to use  

---

##  Installation & Setup  

### 1. Clone this repository  
```bash
git clone https://github.com/deepshika-babu/ChatGPT-Powered-Terminal-Chatbot.git
cd chatbot
```

### 2. Install dependencies  
```bash
pip install openai
```

### 3. Set up OpenAI API Key  
- Sign up at [OpenAI](https://openai.com/)
- Get your API key from [OpenAI API Keys](https://platform.openai.com/)
- Add your API key in the script:
```python
client = OpenAI(api_key="your-api-key-here")
```

## Usage

Run the chatbot:
```bash
python chatbot.py
```
Then, start chatting! Example:

![Chatbot Screenshot]()

To exit, type "quit", "exit", or "bye"

## 🔧 Future Enhancements
- Add chat history (context-aware responses
- Implement voice chat using Speech-to-Text & Text-to-Speech
- Deploy as a web app using Flask