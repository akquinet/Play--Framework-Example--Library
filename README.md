Introduction
============
This projects is a simple example using the Play! framework. It's a basic library without any fancy feature but illustrates a couple of Play! features such as:

* The template engine
* The JPA support
* The CRUD module

Running the application
=======================
First download the Play! Framework from [the download page](http://www.playframework.org/download) and install it by following the instructions from [the installation guide](http://www.playframework.org/documentation/1.2.1/install).

Then, clone the repository and start the application:

    git clone git@github.com:akquinet/Play--Framework-Example--Library.git Play-Framework-Example-Library
	cd Play-Framework-Example-Library
	play dependencies
	play run .
	
Once launched, you should see:

    ~        _            _ 
	~  _ __ | | __ _ _  _| |
	~ | '_ \| |/ _' | || |_|
	~ |  __/|_|\____|\__ (_)
	~ |_|            |__/   
	~
	~ play! 1.2.1, http://www.playframework.org
	~
	~ Ctrl+C to stop
	~ 
	Listening for transport dt_socket at address: 8000
	12:12:01,565 INFO  ~ Starting /Users/clement/Projects/Play-Example-Library
	12:12:01,569 INFO  ~ Module crud is available (/opt/play-1.2.1/modules/crud)
	12:12:02,192 WARN  ~ You're running Play! in DEV mode
	12:12:02,294 INFO  ~ Listening for HTTP on port 9000 (Waiting a first request to start) ...
	12:12:08,243 INFO  ~ Connected to jdbc:h2:/Users/clement/Projects/Play-Example-Library/db/h2/play;MODE=MYSQL
	12:12:08,939 INFO  ~ Application 'Play Framework Example - Library' is now started !
	

Then, open a browser on http://localhost:9000. 

