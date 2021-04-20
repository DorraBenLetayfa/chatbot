# chatbot

First you have to install python 3.8.7 from https://www.python.org/downloads/windows/ "download Windows installer 64-bit. (before installing please check set path option) 
Second, you have to install chatterbot 1.0.2 : pip install chatterbot==1.0.2
third, install pytz : pip install pytz

fourth, Go to C:\Users\yourUser\AppData\Local\Programs\Python\Python38\Lib\site-packages\ (or the path where python is installed on your machine) 
find "sqlalchemy" folder then "util" folder and open the file compat.py in text editor and change time.clock with time.time.

now, run the script chatbot.py.
That's All.
Enjoy.
