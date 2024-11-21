## This script uses the local PC to run the application instead of Hugginface environment

0. git clone <url to github repo> and open a powershell terminal in the App dir
1. Create the Python env in the App dir
 python -m venv .venv
 .venv\Scripts\Activate.ps1 (for windows powershell)
2. Import all the PIP packages
  pip install openai
  pip install os
  pip install langchain 
  pip install langchain-community 
  pip install streamlit
  or pip install -r requirements.txt

3.streamlit run app.py