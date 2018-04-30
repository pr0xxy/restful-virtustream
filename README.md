# restful-virtustream
Building RESTful web service using Python & Flask

## Getting Started

These are instructions for cloning this repository to build and deploy/run a RESTful web service on your local machine. The web service will accept requests and respond to them as appropriate . See Deployment for notes on how to deploy the project on a live system.

### Prerequisites

This can be run on Windows, Unix or Mac. The RESTful webservice will run in a virtual environment using Python and Flask

```
python 2 or python 3
virtualenv
Flask
```

### Installing

Instructions on how to install the RESTful service on Python Virtualenv using Flask

On the Windows, UNIX/Linux or MAC system running Python
Python 3 comes bundled with the venv module to create virtual environments. If you’re using a modern version of Python, you can continue on to the next section.

If you are using Python 2, the venv module is not available. Instead, install virtualenv.

#### -Install virtualenv

```
sudo pip install virtualenv
```

On Linux, virtualenv is provided by your package manager:

```
# Debian, Ubuntu
sudo apt-get install python-virtualenv

# CentOS, Fedora
sudo yum install python-virtualenv

# Arch
sudo pacman -S python-virtualenv
```

If you are on Mac OS X or Windows, download get-pip.py, then:

```
sudo python2 Downloads/get-pip.py
sudo python2 -m pip install virtualenv
```

On Windows, as an administrator:

```
\Python27\python.exe Downloads\get-pip.py
\Python27\python.exe -m pip install virtualenv
```
## Create an environment

Create a venv called "fibonacci". You'd preferably run the following commands in your project root dir:

Unix Commands

```
# python3 -m venv fibonacci
# ls
fibonacci
```
On Windows:

```
py -3 -m venv venv
```

If you needed to install virtualenv because you are on an older version of Python, use the following command instead:
```
virtualenv venv
```
On Windows:

```
\Python27\Scripts\virtualenv.exe venv
```

## Activate the environment
Before you work on your project, activate the corresponding environment:
```
. fibonacci/bin/activate
```
On Windows:
```
venv\Scripts\activate
```
Your shell prompt will change to show the name of the activated environment.

### Install Flask
Within the activated environment, use the following command to install Flask:

```
pip install Flask
```


### Cloning the github repository

Once you have successfully installed Flask within your activated environment backout of the "venv" directory into the "fibonacci" directory.
```
cd fibonacci
git clone https://github.com/pr0xxy/restful-virtustream.git
python3 restful-virtustream/Fibonacci1.py
```

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system
