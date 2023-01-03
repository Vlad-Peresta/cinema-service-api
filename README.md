# Cinema Service API

API service for cinema management  written on DRF

## Installation
Python3 should be installed

#### Download the code
```angular2html
git clone https://github.com/Vlad-Peresta/cinema-service-api
cd cinema-service-api
```

#### Set Up for Unix, macOS
```angular2html
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

#### Set Up for Windows
```angular2html
python3 -m venv venv
.\env\Scripts\activate
pip3 install -r requirements.txt
```

#### Set Up environment variables and Database for Windows
```angular2html
set POSTGRES_HOST=<your db hostname>
set POSTGRES_DB=<your db name>
set POSTGRES_USER=<your db username>
set POSTGRES_PASSWORD=<your db user password>
set SECRET_KEY=<your secret key>
  
python3 manage.py makemigrations
python3 manage.py migrate
```

#### Set Up environment variables and Database for Unix, macOS
```angular2html
export POSTGRES_HOST=<your db hostname>
export POSTGRES_DB=<your db name>
export POSTGRES_USER=<your db username>
export POSTGRES_PASSWORD=<your db user password>
export SECRET_KEY=<your secret key>
  
python3 manage.py makemigrations
python3 manage.py migrate
```

#### Start the app
```angular2html
python3 manage.py runserver
```

#### Run with docker
Docker should be installed
```angular2html
docker-compose build
docker-compose up
```

## Features

* JWT authenticated
* Admin panel /amin/
* Documentation is located at /api/doc/swagger/
* Managing order and tickets
* Creating movies with genres ang actors
* Creating cinema halls
* Adding movie sessions
* Filtering movies and movie sessions

## Getting access
* create user via /api/user/register/
* get access token /api/user/token/

## Project screenshots
![Знімок екрана з 2023-01-03 13-30-21](https://user-images.githubusercontent.com/106173314/210350072-2f7eba27-470a-46d5-ac99-747eb23bb853.png)
![Знімок екрана з 2023-01-03 13-30-54](https://user-images.githubusercontent.com/106173314/210350095-acfdefa9-a9ad-4c54-b19b-6c2eaa2fa8c9.png)
![Знімок екрана з 2023-01-03 13-31-49](https://user-images.githubusercontent.com/106173314/210350121-73ab20d1-85cf-4f14-ade8-bc10c8a98aca.png)
