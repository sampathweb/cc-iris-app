# IRIS Web Application

Sample Flask web App that uses API Service to predict IRIS Flower.

## Setup Environment on Local Machine

* Verify you have anaconda or miniconda installed by typing `conda` in your terminal window.
* install cookiecutter by typing `pip install cookiecutter`

### Installation

```
cookiecutter https://github.com/sampathweb/cc-iris-app

cd <repo>  # cd iris-app

# Install Packages
python env/create_env.py
source activate env/venv  # Windows users: activate env/venv
python env/install_packages.py

# Run the App
python run.py

````

> The above step assumes that you have IRIS API Server running locally at port 9000.  
> Otherwise, change the location at app/config.py


### Test App

1. Open Browser:  [http://localhost:5000](http://localhost:9000)

## Credits:

Template from https://github.com/sampathweb/cc-iris-app


### The End.