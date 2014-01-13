# Intro to Rails

The purpose of this project is to introduce you to Rails's different moving parts. This will happen through a series of steps in the form of branches. Each step will build on the previous one.

## installation
- clone the project:

	```bash
	git clone https://github.com/Devbootcamp/challenge-intro-to-rails.git
	```
- install gems:

	```bash
	bundle install
	```
- create database.yml file

	```bash
	touch config/database.yml
	```
- configure database.yml file by following/reading the database.example.yml file.
- create the databases:

	```bash
	rake db:create
	```
- run the server:

	```bash
	rails s
	```
- visit localhost:3000 to see Welcome to Rails page.

