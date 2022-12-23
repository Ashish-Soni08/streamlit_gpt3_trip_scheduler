# GPT-3 Powered Streamlit Trip Scheduler Web Application

The application generates a trip schedule based on user input. We are using the text-davinci-003 model from OpenAI.

## GETTING AN OpenAI API Key

You can get one by signing up at from [beta.openai.com](https://beta.openai.com/). Once your account is created, you can go to your profile and click the "API Keys" tab and create one.

## RUN APPLICATION

- Create a .env file after cloning or forking the repository and Specify the OpenAI API key in the file.

OPEN_API_KEY=<Key Here>

Example:
OPEN_API_KEY=gf-hhdjnajdopsxsamxaxaxasxaxadfguwioajjakskanxhxsax

- create virtual environment

```bash

python3 -m venv <"Path for Environment/'name of environemnt'">

# Example
python3 -m venv /workspace/streamlit_gpt3_trip_scheduler/gpt3

```

- Activate virtual environment

```bash

source <"'Path to Environment'/bin/activate">

# Example
source /workspace/streamlit_gpt3_trip_scheduler/gpt3/bin/activate

```

- install dependencies

```bash
`pip install -r requirements.txt`

```

- Run application

```bash

streamlit run main.py
```

**App Link**: [Trip_Scheduler](https://ashish-soni08-streamlit-gpt3-trip-scheduler-main-ja4s5q.streamlit.app/)