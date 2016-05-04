# Quizzler

*Quizzler* is a lightweight Command Line quiz application written in the Python language.

### Features
* Take quizzes directly from the terminal and immediately get scored based on your answers.
* Upload to and download quizzes from the [Firebase] (http://firebase.com/ service).
* List quizzes in online Firebase storage.
* Import quizzes from any external location.
* Easy to develop quiz format. You can add your own quizzes and play them or test others.

### Dependencies | Requirements
* [Python 2.7.11] (https://www.python.org/downloads/) : Python Interpreter
* [requests 2.10.0] (http://docs.python-requests.org/en/master/) : Enables connection between Quizzler and Firebase
           ```sudo pip install requests==1.1.0```
* [tqdm 4.5.0] (https://pypi.python.org/pypi/tqdm) : Enables implementation of progress bars
           ```pip install tqdm```
* [python-firebase 1.2] (https://pypi.python.org/pypi/python-firebase/1.2) : Enables easy connection between Firebase and Python
           ```sudo pip install python-firebase```
       
  #### To install all requirements, type in your terminal application:
          ```sudo pip install -R requirements.txt```

### Commands
* help ====| Displays all available commands and their descriptions
* help <command> ====| Describes the command
* listquizzes ====| Displays available local quizzes
* takequiz <quiz name> ====| Launches the local quiz quiz name
* listonline ====| Display available online quizzes
* downloadquiz <quiz source path> ====| Add a quiz to the local collection from online source
* uploadquiz ====| Add quiz to online collection
* importquiz <quiz source path> ====| Add quiz to local collection from external source

### Copyright and Licensing
MIT license. For detailed licence information, see [license] (https://github.com/emabishi/bc-7-Quiz-Application/blob/master/LICENSE)

### Contact Information
Find the author at [@emabishi] (https://github.com/emabishi) on github.



