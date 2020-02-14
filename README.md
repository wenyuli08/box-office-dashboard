# Box Office Dashboard

## Installation

1. Run `pip install -r requirements.txt` in a Python 3.7+ virtual environment
2. Set the `FLASK_APP=dashboard.py` environment variable
3. Run `flask run` and navigate to `localhost:5000`

## Running the app

1. Only one authorized user: "admin", "plaintextboo"
2. if logged in as an unauthorized user, you will be constantly prompted to enter username and password until you are the authorized one. Click "cancel" will result in a 401 error with a message.
3. "Top 10 by Studio" default select is the first studio; default table is nothing.
4. Average gross is rounded to two decimal places.