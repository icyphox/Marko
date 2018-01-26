# icybot
A Twitter bot that generates Markov chains and tweets them.

### Installation
If you want to run this under your own account, follow these steps:
	- cloe thisrepo
	- [create your own Twitter Application](https://apps.twitter.com/app/new)
	- get your access token, access token secret, consumer token and consumer secret
	- export them as shell variables `A_TOKEN`, `A_SECRET`, `C_KEY` and `C_SECRET` respectively
	- finally
	$ pip install -r requirements.txt


### Usage

	usage: bot.py [-h] [-f FILE] [-u URL]

	A Twitter bot that tweets Markov chains.

	optional arguments:
	 -h, --help            show this help message and exit
	-f FILE, --file FILE  path to text model (.txt)
	-u URL, --url URL     urlto generate a model from

