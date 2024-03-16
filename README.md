# django react todo app

## Overview

Follow 

https://www.digitalocean.com/community/tutorials/build-a-to-do-application-using-django-and-react

<div align="center">
<img src="./content/django.png" alt="django" height=400px/>
<img src="./content/react.png" alt="react" height=400px/>
</div>

## Requirements

To use the scripts, these need to be installed:
- pip3
- pylint
- gh (github cli)
- git

## Setup

You can either use Makefile 

```bash
make venv
make install
make lint
make clean
```

(Note that ``make clean`` removes the virtual environment.)

or do the following:

To set up a virtual environment and install dependencies, run the following commands:

1. Create a virtual environment

```bash
python3 -m venv ./venv
source ./venv/bin/activate
```

2. Install the dependencies

```bash
pip install --no-cache-dir -r requirements.txt
```

Note: You can delete the unnecessary folders via

```bash
rm -rf 
```

<div style="text-align:center; margin-top: 40px;">

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/frattini)

</div>

