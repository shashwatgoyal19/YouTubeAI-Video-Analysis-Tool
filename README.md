# YouTubeAI Video Analysis Tool
A chatbot that analyses a YouTube video and lets you converse with it.

## Description
Built a tool to provide timestamped answers to video questions.
Integrated YouTube Transcript API and OpenAI LLM API for subtitles and text processing.

## Steps to run:
0. (Optional)i.Creating a virtual environment: python3 -m venv vn (vn is the name of the folder)
      ii. To activate: source vn/bin/activate

1. Install the required packages by running the code:
    pip install -r requirements.txt
2. Create a secret API key from https://platform.openai.com/account/api-keys and paste it in openai.api_key in the code. If the key does not seem to work, then create a new OpenAI account with a different phone number and create a new key from that account.

3. Input the secret OpenAI API key.

4. Open a terminal and run the following command: python3 yt.py
