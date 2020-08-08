# INCUBED ETH ADDRESS SCRIPT

This is a python script to investigate information from the registry for a particular given eth address. In this script this address is passed to the script from within the code and an interactive Menu shows giving the user options to visualize information about this address from the registry.

## USAGE

The python script comes in two forms, as a Docker image and a general python script. Below are ways to run both options.

### DOCKER IMAGE
1. Install docker by following these instructions for Windows/Mac/Linux https://docs.docker.com/get-docker/

2. Pull the docker image by executing this command:
$ docker pull chinyati/incubed_network
![Second Image](https://github.com/chinyati/incubed_registry_investigation/blob/master/Screenshot%20from%202020-08-08%2019-15-19.png)
3. After pulling the docker image execute this command to run the python script:
$ docker run -ti chinyati/incubed_network
4. A menu with four options will come up as shown below, choose options and interact with Menu
![First Image](https://github.com/chinyati/incubed_registry_investigation/blob/master/Screenshot%20from%202020-08-08%2019-15-00.png)


### NATIVE PYTHON SCRIPT
1. Install python on machine
2. Download zipped incubed_network python folder
3. From within the folder open command line interface and install the requirements by executing:
pip install requirements.txt
4. After installing requirements run the python script by executing:
$ python incubed_network.py
