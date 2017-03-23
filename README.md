
# Overview
	
	Python sentiment analysis Rest service
	build on Flask microframework

# Requierments

	Python
	pip
	virtualenv

# how to start and install dependecies
	
	1. install virtualenv

		sudo pip install virtualenv

	2. create virtualenv

		virtualenv venv

	3. activate virtualenv

		. venv/bin/activate

	4. activate virtualenv and install dependencies

		sudo pip install -r requirements.txt

	5. start server

		python server.py

# how to use:

	go to browser and, type: localhost:5000/api/v1/sentiment/<text to calculate sentiment>

# to deactivate virtualenv

	deactivate