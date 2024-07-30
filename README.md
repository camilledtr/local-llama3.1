# Local Llama 3.1 chatbot

## Run the model

1. Download Ollama :
https://ollama.com/download

###
2. Install Ollama, open it and install the command `ollama` as indicated

###
1. Retrieve the llama3.1 model
```
ollama run llama3.1
```

##
## Run the chatbot UI

1. *(First setup)* Create a python venv
```
python3 -m venv venv
```

###
2. Activate the python venv
```
source venv/bin/activate
```

###
3. *(First setup)* Install the required packages
```
pip install -r requirements.txt
```

###
4. Run the chatbot in a browser
```
streamlit run main.py
```