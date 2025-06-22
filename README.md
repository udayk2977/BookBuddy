# BookBuddy
**🤖📚 Textbook Chatbot**

This project is a chatbot designed to assist students in interacting with their textbooks in a conversational manner. The chatbot has been developed using the RAG (Retrieval-Augmented Generation) model, which enables it to understand and respond to natural language queries. It can be run locally on a machine using LM Studio or accessed via the internet using the Hugging Face API.

**🌐 Features:**

* *Select a textbook of your choice and initiate a conversation with it.*
* *Accessible via a user-friendly interface created with Streamlit.*
* *Contains chat memory: reponse of each chat is based on previous chats.*
* *View chat history to keep track of conversations.*
* *Select LLM of your own.*
* *Runs on both local machine and via internet.*

A detailed list of resources used in this project can be found in the `Resources.pdf` 


## Workflow
![Flowchart](https://github.com/breakthe-rule/AB_TOH_PADHLE/assets/114070578/bdf8d899-0e98-46a3-9f06-98cf02a3cb05)

## Setup

1. `Clone this repo to your PC.`
2. `Install LM studio and download LLM which satisfy your hardware requirements.`
3. `Setup gpu on your PC based on your hardware.`
    * `Setup GPU on LM studio`
    * `In vectordb.py, Line 21; Ab-toh-padhle.py, Line 58 and 2_Huggingface.py, Line 73 change device to cuda`
3. `Add your huggingface token with read access in:- pages\2_Huggingface.py`
4. `Add required textbook in pdf format inside 'Material' folder.`
5. `streamlit run Ab-toh-padhle.py`
6. `In sidebar select book and click 'Create Requirements' (need to do only once if new textbook is added)`
7. `Whooo 🎉 Your setup is completed !!`




