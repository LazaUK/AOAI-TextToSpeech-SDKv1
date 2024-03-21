# Text-to-Speech (TTS) generation with Azure OpenAI TTS models
_tts-1_ and _tts-1-hd_ are TTS models from OpenAI, which can produce audio content based on your textual input (prompt). You will find a Jupyter notebook in this repo, that utilises Azure OpenAI deployment of tts-1 to generate MP3 audio for a given textual menu content.

To build this demo, I used the latest version of OpenAI Python SDK - v1.x. To upgrade your _openai_ Python package, please use the following pip command:
```
pip install --upgrade openai
```

## Table of contents:
- [Part 1: Configuring solution environment]()
- [Part 2: Generating speech through Python SDK]()
- [Part 3: Generating speech through REST API]()

## Part 1: Configuring solution environment
1. To use Azure OpenAI backend, assign the API endpoint name, key and version, along with the Azure OpenAI deployment name of TTS model to **AZURE_OPENAI_API_BASE**, **AZURE_OPENAI_API_KEY**, **AZURE_OPENAI_API_VERSION** and **AZURE_OPENAI_API_DEPLOY_TTS** environment variables respectively.
![screenshot_1.1_environment](images/environment_var.png)
2. Install the required Python packages, by using the **pip** command and the provided requirements.txt file.
```
pip install -r requirements.txt
```

## Part 2: Generating speech through Python SDK
> Note: detailed description on the code logic to be provided soon..

## Part 3: Generating speech through REST API
> Note: detailed description on the code logic to be provided soon..
