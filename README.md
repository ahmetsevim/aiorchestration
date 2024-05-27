**Steps to Run**
1. Fork this repository (optional) and clone it locally.

```
git clone 
cd 
```

2. Create a virtualenv and activate it.

`python3 -m venv .venv && source .venv/bin/activate`

3. OPTIONAL - Rename example.env to .env with `cp example.env .env` and input the environment variables from LangSmith. You need to create an account in LangSmith website if you haven't already. Also, you need to get api key for groq from this link: https://console.groq.com/keys.

```
LANGCHAIN_TRACING_V2=true
LANGCHAIN_ENDPOINT="https://api.smith.langchain.com"
LANGCHAIN_API_KEY="your-api-key"
LANGCHAIN_PROJECT="your-project"
GROQ_API_KEY="YOUR_GROQ_API_KEY"
```

4. Run the following command in the terminal to install necessary python packages:

`pip install -r requirements.txt`

5. Run the following command in your terminal to start the chat UI:

`chainlit run main.py`

