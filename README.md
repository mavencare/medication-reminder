Medication Reminder Sample App
==============================

This repo contains a very simple server and client meant to be a medication reminder application.

The server has a simple rest route and model for managing medications. It also will seed the database with medications.

The client has a very basic scaffold for a front end project (from 2015). Its like a time machine, you don't need to use it if you don't want to.

## Task

Create an app (possibly starting with the one in this repo) to remind individuals of their upcoming and missed medications.

It should have the following features

1. Communicate with the provided server using REST APIs (feel free to modify as necessary)
1. Allow a user the ability to view medications for different days (one possible way is a calendar)
2. Allow a user the ability to mark medications as taken
3. Alert users (audio, visual, really anything at all) 5 minutes before medication should be taken

**YOU DO NOT NEED TO USE THE CLIENT PROVIDED**
Feel free to choose your own stack

### Getting Started

1. Install NodeJS and NPM (Use version 4.8.7)
2. Install MongoDB (brew install mongodb)
3. Start the process `mkdir -p ~/mongo/db mongod --dbpath ~/mongo/db/`
3. Clone this repository
4. npm install
5. npm install -g bower
5. bower install
6. npm install -g grunt-cli
6. grunt serve
