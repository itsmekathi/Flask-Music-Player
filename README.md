Music Visualization
======

 Implement a music visualization website
 <br/>

## Functions
- Music Playing
- Music Visualization

## Usage
Before running this project, the dependency should be installed first.

###Install dependency
install requirement pakages which is define in requirement.txt, with command ```pip install -r requirement.txt```


###Run server:
```python run.py```


##Structure
manage.py: provide commands like 'shell' and 'runserver'
config.py: configuration file
requirements.txt: dependency libraries
app folder: contain main source code
- main: sub-module for main functions
- templates: html file
- static: js, css files and store images
- __init__.py: initialize the application
- models.py: database related information

Each sub-module contains itself's __init__.py, views.py and forms.py
- views.py: connect back-end route functions to the front-end html file 
- forms.py: provide information for flask-wtf (a form extension)



## Reference
the main page front-end refer to [imooc course](http://www.imooc.com/learn/366)

The back-end following Miguel grinberg's book to implement login and register functions.

Cloned and modified from repo : https://github.com/y4h2/Flask-Music-Player
