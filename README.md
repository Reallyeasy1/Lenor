# 💬 Lenor FrontEnd

A simple Streamlit app that shows how to build a chatbot using OpenAI's GPT-3.5.
This repo constitutes the frontend and its deployment of Lenor.

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://chatbot-template.streamlit.app/)

### How to run it on your own machine

1. Install the requirements

   ```
   $ pip install -r requirements.txt
   ```

2. Create a .env file and add your openAI API key.
[HELP](https://help.openai.com/en/articles/4936850-where-do-i-find-my-openai-api-key)

3. Reinstall the openai module.

   ```
   pip uninstall openai
   pip install openai
   ```
   
4. Run the app

   ```
   $ streamlit run streamlit_app.py
   ```
