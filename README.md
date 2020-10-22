# django_tutorial

- Check your current version of python and pip
	- If you don't have python use "sudo apt install python3"
	- If you don't have pip use "sudo apt install python3-pip"

- sudo apt-get install python3-venv
- python3 -m venv environment_directory_name

- Use default postgres user for tutorial
- sudo apt-get install postgresql
- sudo apt-get install python-psycopg2
- sudo apt-get install libpq-dev

- Activate venv
- pip install 
	django	
	djangorestframework (Rest API)
	django-cors-headers (Allow frontend to communicate with backend)
	djangorestframework-simplejwt (For our JSON web tokens)
	Pillow (image uploads)

- pip install 
	--upgrade wheel
	--upgrade setuptools
	psycopg2 (For communicating with postgres DB)
	psycopg2-binary (For communicating with postgres DB)
