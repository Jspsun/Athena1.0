# A python voice controller

## A Bit of Inspiration
We set out with the goal of being able to automate the tedious tasks that one does on a day-to-day basis. Really just the simple things that can just be done a lot more conveniently. This meant opening web pages, applications etc. Gradually, we realized that we had stumbled upon a great way to enable the differently abled to access computers. At this point, we began to prioritize the ease of use on part of the user. By incorporating an OCR, we were able to locate (and click) elements like buttons that traditional web page analyzers cannot. By the end, We had extended to the ability to control computer peripherals beyond just a mouse to the keyboard as well. To top it all off, we created a variety of "voice-triggerable" scripts that make computer usage even more of a breeze!

PyVoiceControl is a Python based tool used to navigate a computer using only one's voice. With just your voice, you can move the mouse around the screen, click on elements, type characters and navigate programs and webpages. This was created at Electric City Hacks 2016.  



Everything was programmed in Python. A simple script was used to handle mouse and keyboard controls. The GUI was created using Tkinter. The speech to text was generated using Google Cloud. The text to speech was generated with MacOS's built in terminal commands. The mouse tracking works by having the user say the text on the screen at which to move the cursor. The text is then search for by taking a screenshot and then running an OCR (with Tesseract) to find the exact locations. Overall, the project is intended as either an assistive program for those who need it, or a simple handy tool.   


## Required tools to run:
-Gcloud  
-PyAudio      
-portaudio  
-tesseract  
-PIL  
-Pillow  
-pyautogui    
-libtif  
-libpng  
-jpeg  
-Tkinter  
-SpeechRecognition  


## Things we would like to add in the future   
-Optimize speech-to-text engine to work faster and in more varied environments in terms of "loudness"   
-Bundle all the frameworks and dependancies into a compiled package   
-Improve UI so that users can write and toggle their own commands   
-Make the GUI less aggressive and automatically hidden unless triggered   

## List of Commands   
### Open an App   
-App   
-Application   
-launch   
-launch  

### Search
-google   
-search   
-look up   

### Go to URL   
-open   
-goto   
-website   

### Move Mouse   
-move   
-cursor   

### Scroll   
-scroll   
-up   
-down   

### Click   
-click   
-press   

### Type   
-type   
-input   
