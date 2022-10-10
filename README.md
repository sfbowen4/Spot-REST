# Spot-REST
A REST wrapper for the Boston Dynamics Spot API

## Quick Start

### Install
From the root directory, run pip to install all necessary requirements.
```bash
pip install -t 'requirements.txt'
```

### Start
From the root directory, start the server using the following command.  
**Note that the server must be connected to Spot's wireless network.*
```bash
python main.py
```
The following should show the flask server running:
```
* Serving Flask app 'SpotAPI' (lazy loading)
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: on
 * Running on http://X.X.X.X:8080/ (Press CTRL+C to quit)
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: XXX-XXX-XXX
 ```

Subsequent requests to the server will be displayed on this terminal.