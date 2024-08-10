# SmartBot

This repository features a sophisticated chatbot named SmartBot created with Gemini AI and Streamlit. The chatbot uses Gemini AI's advanced natural language processing to provide intelligent and context-aware responses to various queries. One of the standout features of this chatbot is the ability to export conversation responses as PDF files to share the chatbot's responses in a professional format or keep a record of the conversation for future reference. 

## Website's URL

You can access the deployed chatbot application at the following URL:
https://smartbot-3.onrender.com/

## Output

https://github.com/user-attachments/assets/bae5c137-12fc-4793-98eb-17ea2fc9e67a

## Table of Contents

- **Features**
- **Requirements**
- **Installation**
- **Usage**
- **Contributing**
- **License**
  
## Features

- **Intelligent Responses:** The chatbot uses Gemini AI to provide accurate and relevant responses to user queries.
- **User-Friendly Interface:** Built with Streamlit, the interface is easy to navigate and interact with, providing a seamless user experience.
- **Real-Time Conversation:** Handles conversations in real-time, making it responsive and interactive.
- **PDF Export:** Users can export chatbot responses as PDFs to share anywhere.

## Requirements

- Python 3.6 or higher
- Gemini AI API key
- Streamlit
  
## Installation

- Clone the repository:
```bash
  git clone https://github.com/Vedant804/SmartBot.git
  cd SmartBot
 
```
- Create a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate
```
- Install the required packages:
```bash
pip install -r requirements.txt
```

- Set up your environment variables:
Create a file named .env in the root directory and add your environment variables:

```bash
GEMINI_API_KEY=your_gemini_api_key
```

## Usage

- Run the Streamlit app:
```
streamlit run chat.py
```    

- Open your browser: Go to http://localhost:8501 to interact with the chatbot.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

- Fork the repository
- Create your feature branch (git checkout -b feature/your-feature)
- Commit your changes (git commit -am 'Add some feature')
- Push to the branch (git push origin feature/your-feature)
- Create a new Pull Request

