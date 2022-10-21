# Hackathon2022

Summary: A translator holding speech to text functionalities using speechRecognistion and GoogleTrans library. 

Keywords: Terminal, directory, libraries, Python, Visual Studio Code, PyCharm

What you need to run this: Microphone and speakers enabled, python installed.

# Method:

Step 1: Download the files from this link and save all the files to the one folder. https://drive.google.com/drive/folders/1QKoefbUrsfeeXDVDemLP2vdibbrdhk6P?usp=sharing 

Step 2: Check if your computer has pip installed by running ‘pip –version’. If not follow the guide on this link to install pip. 
https://pip.pypa.io/en/stable/installation/ 

Step 3: Open the terminal on python, ensuring you are still in the directory, same folder as your saved files. Then run the command ‘pip install -r libraries.txt’and press enter. When all the libraries have been successfully installed, then you will see ‘successfully installed’ messages on the terminal.
 
Step 4: Make sure your microphone and speakers are on and then run the translator engine by running ‘py translator.py’ if you are on windows and ‘python3 translator.py’ if you are on MacOS.

Step 5: Once you see ‘listening…’ appear on the screen, say what you would like to be translated. 
 
Step 6: If you sentence has been recognised by the computer then you will be prompted to say the language you would like to translate to. When the computer recognises the language correctly, you will see the translated text on the screen as well as hear the audio.
 
# Q & A:  potential problems:
1.	Unable to find libraries.txt
Make sure the directory you are working on has all three files: translator.py, speechtotext.py and libraries.txt in the same folder.
2.	Error raised ‘unable to find pyaudio’
 
To fix this, you need to install pyaudio. There are two ways of doing this:
1.	Run pip install pipwin, then pipwin install pyaudio
2.	Run pip3 install pyaudio for python3
