# Get Started
Open two command line terminals
```
cd ui
```
```
yarn install 
```
```
yarn start
```

You can now go to localhost:3000 to see that the UI is up and running. But it won’t interact with the Flask service which is still not up.

To start flask go to the second terminal and input: 
```
pip install virtualenv 
```
```
virtualenv -p python medhacksenv1
```
```
source medhacksenv1/bin/activate
```
```
pip install -r requirements.txt
```
```
FLASK_APP=app.py flask run
```

This will start up the service on 127.0.0.1:5000.


