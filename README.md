[![Build Status](https://travis-ci.com/alovega/StackOverflow-Lite.svg?branch=developv1)](https://travis-ci.com/alovega/StackOverflow-Lite)  [![Coverage Status](https://coveralls.io/repos/github/alovega/StackOverflow-Lite/badge.svg?branch=developv1)](https://coveralls.io/github/alovega/StackOverflow-Lite?branch=developv1)  [![Maintainability](https://api.codeclimate.com/v1/badges/1af8345792e8e28e40cd/maintainability)](https://codeclimate.com/github/alovega/StackOverflow-Lite/maintainability)

#StackOverflow-lite
This is pre-bootcamp challenge project that creates a Flask-api that allows a user to create a question and post answer to the question also retrieve a question

##Prerequisites
    pip
    virtualenv
    python 3.6
    
##installation
    clone this repo:
    ```
    git clone https://github.com/alovega/StackOverflow-Lite.git
    ```
    create virtual environment:
    ```
    virtualenv <name of your env>
    ```
    activate your virtualnv:
    ```
    $source <name of your env>/Scripts/activate (in bash)
    ```
    install dependencies:
   ```
   $pip install -r requirements.txt
   ```
   To run the application:
   ```
   $python run.py
   ```
      

## Running the tests
  The tests for StackOverflow-lite  are written using the python module unittests. The tests are found in the folder test
  .<br>
  To run the tests:
      
   ```
   $nosetests test/
   ```
  To show coverage:
   ```
   $nosetests test/ --with-coverage
   ```

## Built with 
   Flask-restful, a python framework
   
## Authors
[Alwavega Kevin](https://github.com/alovega)