# Find trending news from different sources all around the world
>## Author: [El-rophi Skwaila](https://github.com/Elrophi/News-Highlight)
---

>Description
### THis is a simple app to look up thousands of sources of news and updates around the world
---

## Technology Used: 
>Bootstrap

>Python

>Flask

>NEWS_API(RESTFUL API)
---

## Installation and setup locally
## Pre-requisites
- Python3
- Virtual environment
- bootstrap
- flask

## Cloning and opening on compiler
#### On your terminal run

    $ git clone https://github.com/Elrophi/News-Highlight.git
    $ cd news-app
    $ code .
##  Setting up the virtual environment and activating it
    $ python -m venv <name of virtual environment>
    $ source <name of virtual environment>/bin/activate

##  Install flask and modules needed
       $ python3 -m pip install flask
       $ python3 -m install flask-bootstrap
       $python3 -m install flask-script
       
## Set up API
 - Go to [News API](https://newsapi.org/)
 - Create an account to get API-KEY
 - Copy the API-KEY generated

 ## Creating the start.sh file to tun the app
 - Create a file and name it start.sh
 - in the file add this

       export NEWS_API_KEY=<you api key>
       python3 manage.py server

## Run the app now
On your terminal run

        $ chmod +x start.sh
        $ ./start.sh


    


   