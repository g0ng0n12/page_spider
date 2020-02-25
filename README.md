# Page Spider
A Small python scrapper app that get words from different urls defined by the user and save them in a sqlite db.

## Getting started

### PreRequisites
    * python3
    * pip3
    * SQLLite DB browser [download here](https://sqlitebrowser.org/)

### Running the App.
* 1 - clone the repository
* 2 - Open a terminal an go to the path where you cloned the repo
* 3 - run  `pip3 install -r requirements.txt` to install the dependencies
* 4 - edit the `input.txt file with the urls that you want to get the wording list
* 5 - to run the app run in the terminal ` python3 page_spider.py --database DATABASENAME -i input.txt` where DATABASE NAME is the database name where you want to save the words. If you add a name with a db that doesn't exist the program will create a new database for you
