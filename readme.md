# Mobions 

A web app that can classify musical genre using convolutional neural network (CNN). At the moment the CNN can only identify 4 musical genres such as pop, rock, hip-hop and classical. 


Live demo: [https://mobions.herokuapp.com/](https://mobions.herokuapp.com/ ) 

(**Warning!** mobions app is still under improvement, it can take a while to load or sometimes it will lead to crashed. When this problem occurs, please reload the page)

## Installation

1. Clone or download all the file from the repository in path: "music_classification/**flask_app**" or copy the file from USB stick “**flask_app**” to local machine (e.g Desktop)

(This application use Python 3)

2. Open the chosen terminal or windows powershell (for windows)

3. Check if pip (python package manager) is installed. It can be check by using this code interminal/windows powershell:
```bash
pip -V
```
It should show information about the pip path. Which means the pip packages installed.  
If the pip does not exist, please refer to the official document, [here](https://pip.pypa.io/en/stable/installation/)

3. Make sure the machine (Mac, Windows, Linux) have virtualenv (virtual environment) or your chosen virtual environment. Python3 should already come with a pre-installed virtual environment (virtualenv)

```bash
pip install virtualenv
```


4. Go to the root folder (flask_app)
	For example: 

```bash
cd flask_app

or

cd Desktop/flask_app

or

cd path/to/your/app
```


5. Activate the virtual environment at the root flask_app folder 
```bash

Install the virtualenv to existing folder with the command line:

virtualenv venv

and activate the virtual environment:
mac:

source ./bin:activate

windows:

./Scripts/activate
```

6. Use the package manager pip3 install the requirements.txt.

```bash
mac : pip3 install -r requirements.txt
windows: pip install -r requirements.txt
```

7. Activate the local server

```bash
mac: python3 server.py
windows: python server.py
```

8. Open the chosen browser (chrome/firefox) and insert the local url “http://127.0.0.1:5000/”


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
