# Llama 2 Chat

This chatbot is created using the open-source Llama 2 LLM model from Meta. The models are hosted on the [Replicate](https://replicate.com/) platform. The app is built with [Streamlit](https://streamlit.io/) and deployed on [Streamlit Community Cloud](https://share.streamlit.io/).

The code is adapted from [this repository](https://github.com/dataprofessor/llama2).

## Demo App

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://llama2.streamlitapp.com/)

## Local Installation

```
pip install -r requirements.txt
streamlit run app.py
```

## Installation with Docker

```
docker build -t llama2 .
docker run -p 8501:8501 -v $(pwd):/app llama2
```

## Getting your own Replicate API token

To use this app, you'll need to get your own [Replicate](https://replicate.com/) API token.

After signing up to Replicate, you can access your API token from [this page](https://replicate.com/account/api-tokens).

## Llama 2 models

- [**Llama2-7B**](https://replicate.com/a16z-infra/llama7b-v2-chat)
- [Llama2-13B](https://replicate.com/a16z-infra/llama13b-v2-chat)
- [Llama2-70B](https://replicate.com/replicate/llama70b-v2-chat)

## Tutorial

Learn how to build this app in this [blog](https://blog.streamlit.io/how-to-build-a-llama-2-chatbot/)!')


