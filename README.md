# py_streamlit

2024.05 streamlit learning repository
2024.05 @glyk0n GH repo

## Create an environment using venv

1. Type inside `py_streamlit` directory

```
python -m venv .venv
```

2. A folder named `.venv` will appear in your project. This directory is where your virtual environment and its dependencies are installed.

## Activate your environment

```
# Windows command prompt
.venv\Scripts\activate.bat

# Windows PowerShell
.venv\Scripts\Activate.ps1

# macOS and Linux
source .venv/bin/activate
```

When you're done using this environment, return to your normal shell by typing:

```
deactivate
```

## Install Streamlit

```
pip install streamlit

<<FAIL>>
DO http_proxy = https_proxy = no_proxy = ""
```

Test that the installation worked by launching the Streamlit Hello example app

```
streamlit hello

# If this doesn't work, use the long-form command
python -m streamlit hello
```

Streamlit's Hello app should appear in a new tab in your web browser. To wsl use `localhost:8501`.

## Create a "Hola Mundo" app and run it

1. Create a file named `app.py` in your project

```
import streamlit as st

st.write("Hola Mundo")
```

2. Run your Streamlit app.

```
streamlit run app.py

# If this doesn't work, use the long-form command
python -m streamlit run app.py
```



----
https://docs.streamlit.io/get-started/installation/command-line
