# KFC Chatbot — Your Friendly KFC Ordering Assistant

This is an interactive Streamlit-based chatbot for KFC, built using LangChain and Azure OpenAI. The chatbot helps users explore the menu, inquire about prices and descriptions, and even place an order — all powered by a local CSV menu file.

## Features

- Menu Lookup — Ask to see the full menu at any time.
- Price Queries — Ask for the price of any item.
- Item Descriptions — Wondering what’s in a Zinger burger? Just ask.
- Order System — Add, remove, and view items in your order.
- Download Summary — Save your final order as a CSV.

## Powered By

- LangChain: For structured prompt routing and LLM chains.
- Azure OpenAI: GPT-3.5 model deployed via Azure.
- Streamlit: For building the chatbot interface.
- Pandas: For data manipulation and order summary generation.
- Tenacity: For reliable retry handling with exponential backoff.


## Setup Instructions

1. ##Install Dependencies

```bash
pip install streamlit langchain openai pandas tenacity
```
2. ##Update Credentials
openai.api_key = "YOUR_AZURE_API_KEY"
deployment_name = "YOUR_DEPLOYMENT_NAME"
azure_endpoint = "YOUR_AZURE_ENDPOINT"

3. ##Add Your Menu
   Ensure kfc_menu.csv is in the same directory with columns:
   - price
   - products
   - description

5. ##Run the App
      streamlit run kfc_chatbot.py

6. ##Accessing the App
     You can now view your Streamlit app in your browser.

  Local URL: http://localhost:8501
  Network URL: http://172.28.0.12:8501
  External URL: http://34.83.44.218:8501

your url is: https://better-horses-stare.loca.lt

How to Use It:
  1. Open the External URL in your browser:
  2. https://better-horses-stare.loca.lt
  3. Or copy the IP Address from the External URL, for example:
     http://34.83.44.218:8501
     Paste this in your browser if the LocalTunnel link doesn’t work.


7.## Example Queries
Just type your queries in natural language, such as:
- Show me the menu  
- How much is the Zinger Burger?  
- What’s in a Krusher?  
- I want to order Popcorn Chicken  
- Remove fries from my order  
- Show order summary  
- Place the order

   

