# Introduction to LLM Agents

### Presentation: [Slides](https://github.com/mkmbader/pydata_workshop_September2024/blob/main/workshop_slides.pdf)

## Workshop description

Welcome to the workshop on building LLM agents!

With this repository you will familiarize yourself with the key concepts of an LLM agent using LangChain and from scratch using the chatgpt chat completion endpoints. At the end, you will have all the code you need for your very own agent and you will be able to build custom tools for your own use-case. 

## Requirements

- Python 3.8 or higher
- Jupyter notebook or jupyter-lab

## Setting up your environment

- The notebooks guide you how to set up the repo with Google Colab. 
- If you prefer to run it locally instead please follow the steps below: 
    - Clone the repository with `git clone https://github.com/mkmbader/pydata_workshop_September2024.git`
    - Set up a virtual environment using `virtualenv`:
        - `pip install virtualenv`
        - Install environment: `python3 -m venv venv`
        - Activate enviroment: `source venv/bin/activate`   
        - Install dependencies in environment: `pip install -r requirements.txt`
        - Select `venv` kernel in your notebook

## API keys

OpenAI API key can abe accessed via this [privatebin](https://privatebin.molops.io/?b0b74a12fdc3a326#4tdRk8yiazMsEnKgsc4D2Tq3GWF7KVWkGPmTiFdAH2m5). The password will be shared during the workshop. 

Make sure to paste the API keys into the file `helper_functions/keys.py` before running the notebook. You are ready to go now!

## Credits

This workshop was set up by **Ana Chaloska** ([Git](https://github.com/anachaloska), [LinkedIn](https://www.linkedin.com/in/ana-chaloska-809486149/)) and **Maria Bader, PhD,** ([Git](https://github.com/mkmbader), [LinkedIn](https://www.linkedin.com/in/mkmbader/)).