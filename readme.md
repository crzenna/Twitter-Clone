# Fullstack Twitter Clone

Project for the Advanced Web Technologies of Edinburgh Napier University



### General info

Code refactoring of a Twitter clone project by Saumya-Bhatt, intended to improve the structure and design of the code/project while preserving its functionalities, as part of a university project.



### Getting started and run project on your machine
1. Create virtual environment ```python3 -m venv venv```
2. Activate venv ```source venv/bin/activate```
3. Install dependencies ```pip3 install -r requirements.txt```
4. Run application ```python3 run.py```



### Test User Credentials

1. Username : JaneDoe
2. Email : test@test.com
3. Password : Admin123



### Test coding quality

* Lint: ```pylint $(git ls-files '*.py')```
* Lint configuration file ```pylint --generate-rcfile > .pylintrc```
* Sort all imports ```isort .``` after have installed isort via ```pip3 install isort```
* Format code by using autopep8 ``` autopep8 --in-place --aggressive --aggressive $(git ls-files '*.py')```
* To test all the implemented unit tests: ```pytest``



### Possible future implementations and additional details

1. 1-1 chat messages between users
2. Block user possibility

Additional info on this project are contained on the report as part of the Coursework 2 submission