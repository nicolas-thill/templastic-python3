# templastic-python3

A repository template for Python projects using Docker & Python 3

## Setup

* Install docker: https://docs.docker.com/engine/installation/
* Install docker-compose: https://docs.docker.com/compose/install/
* Build the docker image: `./docker-compose.sh build`
* Start the stack: `./docker-compose.sh up`

## Notes

* Install Python3 venv: `sudo apt-get install python3-venv`
* Configure a virtual Python 3 env: `python3 -m venv env`
* Enter virtual env: `source env/bin/activate`
* Install modules: `pip install ...`
* Generate requirements: `pip freeze > src/requirements.txt`
* Leave virtual env: `deactivate`
