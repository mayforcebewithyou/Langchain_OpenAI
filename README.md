# Leveraging Your Own Documents in a Langchain Pipeline
This project highlights how to leverage a ChromaDB vectorstore in a Langchain pipeline to create *drumroll please* a GPT Investment Banker (ergh, I cringed as I wrote that, but alas it's actually pretty practical). You can load in a pdf based document and use it alongside an LLM without the need for fine tuning. 

## See it live and in action 📺
[![Tutorial](https://youtu.be/u8vQyTzNGVY 'Tutorial')

# Startup 🚀
1. Create a virtual environment `python -m venv langchainenv`
2. Activate it: 
   - Windows:`.\langchainenv\Scripts\activate`
   - Mac: `source langchain/bin/activate`
3. Clone this repo `git clone https://github.com/nicknochnack/LangchainDocuments`
4. Go into the directory `cd LangchainDocuments`
5. Install the required dependencies `pip install -r requirements.txt`
6. Add your OpenAI APIKey to line 22 of `app.py`
7. Start the app `streamlit run app.py`  

