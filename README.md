# Virtual-Dektop-MiniProject (Free-OpenSource no APIs reqired, Just Scroll Down and Follow the Instructions)

1. Developed a voice-enabled AI system with VUI (Voice User Interface), integrating advanced speech recognition and text-to-speech features for seamless user interaction.
2. Created an LLM-powered chatbot for real-time, meaningful conversations and WhatsApp automation for efficient communication.
3. Implemented face authentication to enhance security and streamlined user experience.
4. Applied Natural Language Processing (NLP) techniques like stemming, stopword removal, and POS tagging for accurate language understanding and data processing.
5. Built a dynamic user interface using HTML, CSS, and JavaScript for the frontend, with Python handling backend logic and SQLite3 for database management.

   Technologies Used : Advaned Python modules - Eel , playsound , os , speechrecognition , pyttsx3 , pywhatkit etc.
                       Natural Language Techniques - Stemming , StopWord removal , POS Tagging  etc 
                       Features - Face Authenticarion, LLM-Powered chatbot , WhatsApp Automation , VUI (Voice User Interface)


Installations Required :-
Python (version 3.10.7 - as it is last vesion which supports Eel module )
VScode
In VS code Extensions:
  Python
	Live server
	JQuery code snippet
	SQLite Viewer   

 After all the above installations, Select the Python Interpreter
Step 1. Open Terminal and Enter the Following Commands(as it is):

 python -m venv envjarvis
Step 2. Now change interpreter to python('enjarvis':vennv) ,Go back to Terminal, and Continue the below commands
	d:/jarvis-main/envjarvis/Scripts/Activate.ps1
  pip install Eel
	pip install playsound==1.2.2
	pip install pyttsx3
	pip install SpeechRecognition
	pip install PyAudio
	pip install pywhatkit	
	pip install pvporcupine==1.9.5
(Now insert contact.csv file with db in Jarvis folder and link with db.py )[Note- You can skip this step and manullay Insert Contacts into DataBase (from db.py file)]
Step 3. (Come Back to Terminal and Continue the below commands)
  pip install hugchat
	pip install opencv-python
	& d:/jarvis-main/envjarvis/Scripts/python.exe d:/jarvis-main/main.py
	& d:/jarvis-main/envjarvis/Scripts/python.exe d:/jarvis-main/run.py
Step 4. ( GO to sample.py and run the file (To register Your Face inputs) or [Note - You can just simply use below Command in terminal )
	d:/jarvis-main/envjarvis/Scripts/python.exe d:/jarvis-main/engine/auth/sample.py
  pip install opencv.contrib.python
Step 5. ( With below command you will be Training Your Face Data )
  d:/jarvis-main/envjarvis/Scripts/python.exe d:/jarvis-main/engine/auth/trainer.py	
Step 6. ( GO to recoganize.py and run(Multi Face inputs(Remeber to give a Face no. [eg. 2] ))
( Also give name in new variable and now run the below command)
	d:/jarvis-main/envjarvis/Scripts/python.exe d:/jarvis-main/engine/auth/recoganize.py 
Step 7. Now we will be Integrating our AI Chatbot into our Project
        Follow the Below Steps
        > Open Chrome
        > install 'cookie-Editor' chrome extention
        > Goto https://huggingface.co/chat/
        > Signnup
        > Select any Llama Model You want
        > Now Find cookie-Editor extention (On top Right of Your page- in 'Extensions'),Click on cookie-Editor, Select This site,Click Export,JSON
Step 8. (Come back to our code ), Create 'Cookies.json' file in 'engine' folder and paste the content (the Json Cookies that You just copied) 

Final Step : Run below Command in the Terminal
  & d:/jarvis-main/envjarvis/Scripts/python.exe d:/jarvis-main/main.py


Note: In some cases Chatbot is not working , to solve this, Delete the 'Cookies.json' file 
    (Open Terminal and run)      > pip uninstall hugchat
    (Now Reinstall by running)   > pip install hugchat
    (Finally Repeat the Step 7, Step 8)
    Hopefully the issue is Resolved.....


Congratulation for your dedication , and Do follow Me.   
