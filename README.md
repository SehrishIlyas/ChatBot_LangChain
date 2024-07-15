# Custom Chatbot using LangChain, LLaMa3 and Chainlit

## Overview
This repo contains the code for Scoopsie, a custom chatbot that answers ice-cream-related questions and fetches information from a fictional ice-cream store's API. Using LangChain and OpenAI's text model, alongside a Flask web service, Scoopsie can provide users with details on flavors, toppings, and store offers. Everything is put together with Chainlit for easy web application integration.

## Getting Started

### Prerequisites
- Python 3.8 or later
- LLaMA 3

### Installation

1. **Clone the Repository**
   ```bash
   git clone git@github.com:tahreemrasul/simple_chatbot_langchain.git
   cd ./simple_chatbot_langchain

2. **Install Dependencies**
* Install the required packages using the `requirements.txt` file:
   ```bash
   pip install -r requirements.txt

### Usage
To run the fictional store's API, execute the following command:
   ```bash
   python ice_cream_store_app.py
```
The fictional store's API will be accessible at http://localhost:5000/{endpoint_name}

Make sure the fictional store's application is running before running the chatbot. To run Scoopsie, 
simply execute the `chatbot.py` script:
   ```bash
   chainlit run chatbot.py -w --port 8000
```

To run the chatbot application, navigate to  http://localhost:8000

