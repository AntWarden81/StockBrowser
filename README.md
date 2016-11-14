# Watson Stock Analytics

Built for CalHacks 2016. Backend system built in flask, designed to automatically query the NASDAQ api with a list of stocks and a date range. Outputs `.xml` files for each stock with date range output in filename. Later extended in a different repo to concatenate xml files, process in numpy, and pass to Watson tradeoff analytics API.

## Dependencies
Use `pip` to install the `flask`, `requests` and `io` packages.

## Backend Usage
`python runserver.py` to start backend server. To port forward, navigate to `ngrok` and run `ngrok.exe http 5000` (on windows).
