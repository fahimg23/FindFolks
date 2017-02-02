FindFolks README

FindFolks is a social network which allows users to organize groups of people with common interests, groups to host and announce events, and users to gather feedback on events (just to name of a few of the features).

The web application was built using python and the flask framework. To run the application you'll need an IDE that supports flask (pycharm, python tools plugin for visual studio, etc). You'll also need some software package that has MySQL and a web server. WAMP/MAMP was used for this project, as it comes with those and phpMyAdmin, and its free.

You'll need to have python added to your environment variables. Next you'll need to install pip: https://pypi.python.org/pypi/pip. Run the following commands in your terminal (applies to Windows and Mac):

pip install flask

pip install pymysql

pymysql is needed for the app to connect to the database. Run “mysqld” in the command line to start the mysql daemon.

If you are unable to run mysql do the following:

Mac – Add the path to mysqld using the following: export PATH=${PATH}:/usr/local/mamp/mysql/bin/

You will have to modify the path to match how it’s installed in your system. 

Windows – Add mysqld to environment variables: C:\wamp\bin\mysql\mysql5.6.17\bin.

This needs to be added to PATH in environment variables. Once again, this path might be different on your machine.

Don't forget to add some data to some of the tables (like location) before using features that interact with them!
