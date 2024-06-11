# Basic Chatbot using Llama3

Using a local LLM with the help of Ollama, have created a basic chatbot.

Some steps to do before you run these
1. create a file as ".env" at the location and add the following variables to be used later.
   LANGCHAIN_API_KEY = "your_unique_key_here"
   LANGCHAIN_PROJECT = "project_name_here"
   LANGCHAIN_ENDPOINT="https://api.smith.langchain.com"
2. install Ollama
3. after installing Ollama, open CMD and run "ollama pull llama3". (you can replace llama3 here with the model you want to use, will have to make the change inside app.py as well)
4. after the model has been downloaded locally, type "ollama run llama3" to run the model locally.
5. then finally run your application using "streamlit run app.py"

NOTE : have added a LANGCHAIN_TRACING_V2 variable to true, so you can use Langsmith to track your project and check the details there.
