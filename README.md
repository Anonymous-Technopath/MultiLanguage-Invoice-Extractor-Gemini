# MultiLanguage Invoice Extractor

A basic Multilanguage Invoice Extractor using Google's Gemini Pro LLM.

### Step 1- Create a virtual environment and install the required packages

    $ python3 -m venv .venv
    $ source .venv/bin/activate
    $ pip install -r requirements.txt 

### Step 2- Create `.env` file with following variables
```
GOOGLE_API_KEY = [ENTER YOUR GEMINI PRO'S GOOGLE API KEY HERE]
```

### Step 3- Run the application using

    $ streamlit run app.py
