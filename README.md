cd ..
python -m venv .venv
.\.venv\Scripts\activate.ps1
pip install -r .\langchain-llm-app\requirements.txt
cd langchain-llm-app
pip install ...
pip install youtube-transcript-api
pip install -U langchain-community faiss-cpu langchain-openai tiktoken
python -m pip freeze > requirements.txt

 git config --global user.email "ivanchinook@gmail.com"
  git config --global user.name "ivanchinook"
