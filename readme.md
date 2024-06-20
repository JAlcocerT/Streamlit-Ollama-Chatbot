[![CI/CD Pipeline](https://github.com/JAlcocerT/Streamlit-Ollama-Chatbot/actions/workflows/streamlit_GH_Actions.yml/badge.svg)](https://github.com/JAlcocerT/Streamlit-Ollama-Chatbot/actions/workflows/streamlit_GH_Actions.yml)

Try the Project quickly with Python Venv's:

```sh
python -m venv streamllama #create it

streamllama\Scripts\activate #activate venv (windows)
source streamllama/bin/activate #(linux)
```

```sh
pip install -r requirements.txt #all at once
streamlit run ollama_chatbot.py
```

Make sure to have [ollama ready](https://fossengineer.com/selfhosting-llms-ollama/) and running your desired model!

---

# Streamlit Ollama Chatbot

This repo contains the completed code for the YouTube tutorial video series:

<a href="https://www.youtube.com/playlist?list=PL39czAYesA5ckKIohbmfL6Bq8X4JwV1Ge" target="_blank"> Build Your Own AI Chatbot with Streamlit and Ollama: A Step-by-Step Tutorial</a>

### Completed Code

Run the command below to clone the completed project code.

```
git clone https://github.com/DevTechBytes/Streamlit-Ollama-Chatbot.git
```

### Getting Starter Project Code

Run the command below to clone the starter project.

```
git clone --single-branch --branch starter_project https://github.com/DevTechBytes/Streamlit-Ollama-Chatbot.git
```

### Chatbot Features include:
- Ability to select different Ollama models to be used by the chatbot
- Streaming output when responding to users like ChatGPT

### Ollama 
<a href="https://ollama.com/download">Download ollama</a>

### Ollama Commands

#### Start Ollama Server
```
ollama serve
```

#### Run Ollama Model
```
ollama run <model_name>
```

```
ollama run llama2-uncensored
```

#### Download Ollama Model
```
ollama pull <model_name>
```

```
ollama pull llama2-uncensored
```

#### List Installed Ollama Models
```
ollama list
```

#### Delete Installed Ollama Models
```
ollama rm <model_name>
```

```
ollama rm llama2-uncensored
```