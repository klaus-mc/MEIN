# Fight Cancer 
Uses ChatGPT API to get customised health advise against cancer based on a health questionnaire.

# Steps to Run
1. Create a Virtual Environment in python with virtualenv `python -m venv myenv` on windows and  `python3 -m venv myenv` For MacOS and Linux
2. Activate venv with `myenv\Scripts\activate` for windows and `source myenv/bin/activate`  for macOS and Linux
3. Install requirements with `pip install -r requirements.txt`
4. Install the Google Text-to-Speech (gTTS) with `pip install gtts`
5. Run this command to install or upgrade Flask `pip install --upgrade flask` 
6. Run this command to install or upgrade werkzeug `pip install --upgrade werkzeuge`
7. Create a .env file in the root folder and add your OpenAI API key (OPENAI_API_KEY=    complete your API_kEY here) What you have to write in the .env file schould be the text in brackets and complete it with your API key.
8. Run the app with `python app.py`

 



