# An-AI-Chatbot-in-Python-and-Flask
An AI Chatbot using Python and Flask REST API 

## Requirements (libraries)
1. TensorFlow
1. Flask

## VsCode SetUp
1. Clone the repository-> cd into the cloned repository folder
2. Create a python virtual environment 
```
# macOS/Linux
# You may need to run sudo apt-get install python3-venv first
python3 -m venv .venv

# Windows
# You can also use py -3 -m venv .venv
python -m venv .venv
```
When you create a new virtual environment, a prompt will be displayed to allow you to select it for the workspace.

3. Activate the virtual environment
```
#linux
source ./venv/bin/activate  # sh, bash, or zsh

#windows
.\venv\Scripts\activate
```
4. Run ```pip install --upgrade tensorflow``` to install ```Tensorflow```
5. Run ```pip install -U nltk``` to install ```nltk```
6. Run ```pip install -U Flask``` to install ```flask```
7. To expose your bot via Ngrok, run ```pip install flask-ngrok``` to install ```flask-ngrok``` Then you'll need to configure your ngrok credentials(login: email + password) Then uncomment this line ```run_with_ngrok(app) ``` and comment the last two lines ```if __name__ == "__main__": app.run() ``` Notice that ngrok is not used by default.
8. To access your bot on localhost, go to ```http://127.0.0.1:5000/ ``` If you're on Ngrok your url will be ```some-text.ngrok.io```
