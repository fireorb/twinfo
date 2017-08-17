=================
1. Installation
=================

1.1 Windows
=================
Python 2.7.12
https://www.python.org/downloads/

[ Optional : pip-Win 1.8  ]

	pip install tweepy
	pip install pillow
	pip install exifread

pyexiv2 0.3.2 
http://tilloy.net/dev/pyexiv2/download.html
https://launchpad.net/pyexiv2

	pip install pyopenssl
	pip install jinja2
	[ Optional : pip install ndg-httpsclient ]


1.2 Linux
=================
Install PIP
$ sudo apt-get install python-pip python-dev build-essential 
$ sudo pip install --upgrade pip 
$ sudo pip install --upgrade virtualenv 

pip install tweepy
apt-get install python2.7-dev
pip install pillow
pip install --upgrade exifread
apt-get install python-pyexiv2
apt-get install python-openssl
pip install jinja2

Note:
To solve the error message "InsecurePlatformWarning":
pip install pyopenssl ndg-httpsclient pyasn1


=================
2. Configuration
=================
OAuth Settings
How to obtain the API key:

1) Go to https://apps.twitter.com/
2) Signin
3) Create new app
4) Go to "Keys and Access Tokens"
5) Copy "Consumer Key (API Key)" to CONSUMER_KEY (file: tinfoleak.conf)
6) Copy "Consumer Secret (API Secret)" to CONSUMER_SECRET (file: tinfoleak.conf)
7) Go to "Create mi access token"
8) Copy "Access Token" to ACCESS_TOKEN (file: tinfoleak.conf)
9) Copy "Access Token Secret" to ACCESS_TOKEN_SECRET (file: tinfoleak.conf)

