# mini_RAG_app

this is a minimal implementation of the RAG for question answering.

## Requirements 

- Pythob 3.8 or later

### Install Python using MiniConda

1) Download and install MiniConda from [here](https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh)
2) Create a New environment using the following command :
```bash
$ conda create -n mini-rag-app python=3.8
```
3) Activate the environment:
```bash
$ conda activate mini-rag-app 
```

### (optional) Setup your command line for better readability
```bash
export PS1="\[\033[01;32m\]\u@\h:\w\n\[\033[00m\]\$ "
```

## Installation

### INstall the required packages

```bash
$ pip install -r requirements.txt
```

### Setup the environment variables

```bash
$ cp .env.example .env
```

Set your environment variables in the `.env` file. like `OPENAI_API_KEY` value
