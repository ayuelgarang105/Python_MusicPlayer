# MUSIC PLAYER

Author:[Gabriel Ayuel](https://github.com/ayuelgarang105/Python_MusicPlayer.git)  
  
# Description  
Music Player is a web appliction that music listeners can use to listen to songs.

## User Story  
As a user, I would like to:

* Sign in with the application to start using.
* Add album
* Remove album
* Add songs
* Delete song
  
## Setup and installations
* Fork the data .
* git clone the gallery repo.
* Activate a virtual environment on terminal: `source virtual/bin/activate`
* Install all the requirements found in requirements file.
* On your terminal run `python3.8 manage.py runserver`



## Getting started

### Prerequisites
* python3.8
* virtual environment
* pip

#### Clone the Repo 
```bash
git clone https://github.com/ayuelgarang105/Python_MusicPlayer.git
```
#### Initialize git and add the remote repository
```bash
git init
```
```bash
git remote add origin <your-repository-url>
```

#### Create and activate the virtual environment
```bash
python3 -m venv virtual
```

```bash
source virtual/bin/activate
```

#### Setting up environment variables
Create a `.env` file and paste paste the following filling where appropriate:
```
SECRET_KEY='**'
DEBUG=True
DB_NAME='****'
DB_USER='<your database name>'
DB_PASSWORD='<password to your database>'
DB_HOST='127.0.0.1'
MODE='dev'
ALLOWED_HOSTS='.localhost', '.herokuapp.com', '.127.0.0.1'
DISABLE_COLLECTSTATIC=1
```

#### Install dependancies,
Install dependancies that will create an environment for the app to run
`pip install -r requirements.txt`

#### Make and run migrations
```bash
python3 manage.py check
python manage.py makemigrations 
python3 manage.py sqlmigrate app 0001
python3 manage.py migrate
```

#### Run the app
```bash
python3 manage.py runserver
```
Open [localhost:8000](http://127.0.0.1:8000/)



## Testing the Application
`python manage.py test music`
## Technologies Used

* [Python3.8](https://docs.python.org/3/)
* Django 
* JavaScript
* Postgresql 
* Boostrap
* HTML
* CSS

## Contact Information   
Please email me at ayuelgarang105@gmail.com for any question or contributions,
  
## License 

[MIT](LICENSE.md)  <br>
Copyright 2021 © by Gabriel Ayuel
