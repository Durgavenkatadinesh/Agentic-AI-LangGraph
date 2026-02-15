sudo su
python3 --version
python3-pip --version
apt install python3.12-venv
sudo apt install python3-pip  (may or may not work ask gpt)
mkdir test
cd test
cd Agentic-AI-LangGraph/
git clone ---link
python3.12 -m venv myenv
source myenv/bin/activate
pip3 install streamlit
pip3 install langgraph --- install all rest
ll to list all files
vi .env
i, :wq!
cat .env
streamlit run AI_streamlit_frontend_threading.py


inorder to kill port:
lsof -t -i:8501
kill xxxxx
