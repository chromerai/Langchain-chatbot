# Langchain-chatbot

This repository is all about creating a custom chatbot that answers questions based on your personal data using Langchain, ChatGPT, StreamLit, and Pinecone.

# Steps to Follow:

1. clone this repo with ```https://github.com/chromerai/Langchain-chatbot.git```
2. the content folder contains some sample files, one can utilize its own files. 
3. Run the ```Langchain_Pinecone_Indexing_.ipynb``` notebook to create and add vectors in your Pinecone database. Make sure that whatever index name you create, is only used in the notebook.
4. Create an open-air API
5. Now create a virtual environment keeping the Python version to 3.9 as sometimes Pdfminer library, used in the LangChain framework may give errors,```namely : NameError: name 'partition_pdf' is not defined```. Personally, I tried with 3.10.5 and got error so try once for yourself and decide.I went old school- using condas for virtual environment creation, try with poetry as well.
6. Install all the dependencies using ```pip install -r requirements.txt``` from the terminal.
7. Now run ```main.py``` from terminal using the command ```streamlit run main.py```


Finally, try to tinker with the chunk size and chunk overlap to get a better idea of your code!
