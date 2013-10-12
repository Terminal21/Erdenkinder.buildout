Erdenkinder CMS buildout
========================

Buildout script for the Erdenkinder CMS

## Setup the Erdenkinder CMS

Clone repository

> git clone https://github.com/Terminal21/Erdenkinder.buildout.git

> cd Erdenkinder.buildout

Create environment

> virtualenv .

> ./bin/pip install --upgrade setuptools

Prepare buildout

> ./bin/python bootstrap.py

Run buildout

> ./bin/buildout

Run application server

> ./bin/pserve app.ini

## Administration

open your browser and navigate to [http://localhost:5000]

The initial credentials are 'admin:qwerty'
