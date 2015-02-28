# INTRODUCTION

[zFlaskClub](http://flaskbb.org) is a forum software written in python using the micro framework Flask.

This project fork from [flaskbb](https://github.com/sh4nks/flaskbb)


## FEATURES

* A Bulletin Board like FluxBB or DjangoBB in Flask
* Private Messages
* Admin Interface
* Group based permissions
* BBCode Support
* Topic Tracker
* Unread Topics/Forums
* i18n Support
* Completely Themeable
* Plugin System



## INSTALLATION

For a complete installation guide please visit the installation documentation
[here](https://flaskbb.readthedocs.org/en/latest/installation.html).

* Create a virtualenv
* Install the dependencies
    * `pip install -r requirements.txt`
* Configuration (_adjust them accordingly to your needs_)
    * For development copy `flaskbb/configs/development.py.example` to `flaskbb/configs/development.py`
* Create the database & populate it
    * `python manage.py populate`
* Run the development server
    * `python manage.py runserver`
* Visit [localhost:8080](http://localhost:8080)


## DOCUMENTATION

The documentation is located [here](http://flaskbb.readthedocs.org/en/latest/).


## ACKNOWLEDGEMENTS

[flask](http://reddit.com/r/flask), [Flask](http://flask.pocoo.org), it's [extensions](http://flask.pocoo.org/extensions/) and everyone who has helped me!
