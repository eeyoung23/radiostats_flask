# radiostats_flask

### Cloning the repository
in a terminal window, do `git clone https://github.com/eeyoung23/radiostats_flask.git`
To start up environment:
1. `python3 -m venv venv`
2. `source venv/bin/activate`
#
### Running the app
Set environment variables (`cd` into `radiostats_flask` directory):
1. `export FLASK_APP=server_table.py`
2. `export FLASK_ENV=development`

To view the app in a browser, do:
1. `flask run` (can also use `--debug`)
2. it will probably ask you to visit http://127.0.0.1:5000 or something similar

If you want to continue running the app while you make changes:
1. Open a new terminal window and start up the environments again (`python3 -m venv venv`, `source venv/bin/activate`)
2. `export FLASK_APP=server_table.py`
3. `export FLASK_ENV=development`

