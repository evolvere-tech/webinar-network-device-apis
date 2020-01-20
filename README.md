# Connecting to Network Device APIs using Python

Most modern devices/software versions support HTTP based APIs. Using these APIs is much quicker and more reliable that using SSH.

## Scripts

### arista-ssh.py
 
* Example uses netmiko module to connect via SSH.
* CLI response is unstructured text data.
* Python string handling used to parse data.

### arista-api.py

* Uses requests module.
* Structured data returned (JSON).

### nexus-api.py

* Uses requests module to connect to Nexus 9k.

## Running scripts
Clone this repository
Create a virtualenv

```
virtualenv -p python3 venv3
```
Source the virtualenv

```
source venv3/bin/activate
```
Install the dependancies

```
pip install -r requirements.txt
```
