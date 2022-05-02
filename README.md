# Personal Assistant/Voice Assistant 
## Modules Required:

SpeechRecognition  (for speech to text) (run `python -m speech_recognition` for a quick test)

pyttsx3            (for text to speech)

pillow             (imaging library)

pynput             (to control and monitor input devices) 

psutil             (to access system details and process utilities)

bs4                (to scrape information from web pages)

smtplib            (for sending emails using the Simple Mail Transfer Protocol SMPT)

geopy              (to locate the coordinates of addresses, cities, countries, and landmarks across the globe using third-party geocoders and other data sources)

playsound  

pyscreenshot

wikipedia  

youtube_search  

wmi  

googletrans==3.1.0a0

webbrowser

## Common Installation Issue : pyaudio
### Use Wheel
1. Go to [pyaudio unofficial binaries](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio) and download any of the previous versions.

1. For more information refer the [details](http://people.csail.mit.edu/hubert/pyaudio/).

1. Open the powershell window in the diretory where you have downloaded it.

1. Then use `pip` to install the pyaudio file.

example:
>  pip install .\PyAudio‑0.2.11‑cp310‑cp310‑win_amd64.whl

## OR

### Use pipwin
``` pip install pipwin ```

``` pip install pyaudio ```

## Possible exception/Error
If the system is offline the `record()` function may raise error because we are using google speech recognition engine.
To fix that, install [pocketsphinx](https://pypi.org/project/pocketsphinx/) module or [snowboydetect](https://pypi.org/project/snowboy/)
Then go to `GUIASSISTANT.py` and edit the `record()` function



## Features added:

### YouTube  
- Play Hello by Adele on YouTube

### Wikipedia Result  
- Who is Sundar Pichai?  
- Who is Satya Nadella?

### Google Search  
- Search for new technologies  
- Search for data structures and algorithms  

### Google Maps  
- India on Google Maps  
- Washington DC on Google Maps  

### Random Joke  
- Tell me a joke  
- Tell me a funny joke  

### News  
- Give me some news  
- Get the latest news  

### Weather  
- What is the weather?    

### System Apps  
- Open Paint  
- Open Notepad  
- Open Calculator  
  
### Coin / Dice  
- Toss a coin  
- Roll a dice  

### Time / Date  
- What is the time?  
- What is the date today?  

### Opening Websites  
- Open GeekForGeeks  
- Open GitHub  
- Open CodeChef  

### Game  
- Let's play a game  
  - Rock Paper Scissor
  - Online Games (BETA)

## Image Result
- Show the images of Germany
- Show the images of Seafood

## Math Calculations 
- What is the binary of 142?  
- 2 + 4 - 3 x 9  
- Right shift 4  
- What is the value of factorial 10?  
- What is the value of Sin 90?  
- 9 power 5  
- what is the log of 1000

## Files Creation  
- Create an empty file  
- Create a Python file  
- Create a Java file  
- Create a PowerPoint file  

## Google Maps Directions  
- Give me directions -> Starting Location -> Destination Location  


## Timer  
- Set a timer for 10 seconds  
- Set a timer for 2 minutes  
- Set a timer for 1 minute 10 seconds  
## Volume Control  
- Increase the Volume  
- Decrease the Volume  
- Mute the Volume  
- Full Volume  

## OS Info  
- Give my System Information  
- What's my battery life  

## Typing Automation 
- Open Notepad -> Say type " I'm currently not typing the text which I'm saying clearly right now "

## Smart Dictionary  
- What is the definition of Machine Learning?  
- What is the meaning of Natural Language Processing?  


# In BETA Stage  

### Smart Reply
- How are you?  
- Who are you?  
- Tell me something  
- When is your birthday?  
- You're so funny  
- Thank You  
- I'm sorry


## Web Automation (HTML Project)  
- Create a HTML project -> Project Name  
(It will create Empty Project for you with HTML, CSS and JavaScript file with some important codes)  

## Email  
- Send an email -> Receiver Email -> Subject -> Message  


## COVID Tracker  
- What is the covid statistics?  
- What are the total covid cases in Inida?  
- What are the total deaths due to coronavirus?  
- What are the symptoms of covid-19?  
- What precautions can we take from coronavirus?  

## Translator  
- Translate a sentence -> "Hello, how are you?" -> Hindi  


## ToDo List  
- Add an item to my list -> "This is my first Item in my list"  
- Show my list  
