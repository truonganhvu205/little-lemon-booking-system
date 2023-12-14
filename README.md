# Clone project
```bash
mkdir littlelemonAPI

cd littlelemonAPI

git init

git clone https://github.com/truonganhvu205/little-lemon-API.git
```

## Install pipenv
```bash
pip3 install pipenv
```

## Activate virtual environment
```bash
pipenv --python 3.10
pipenv shell
```

## Install Django
```bash
pipenv install django
```

## Connect to MySQL
```bash
sudo mysql -u root -p OR mysql -u root -p
CREATE DATABASE reservations;
CREATE USER 'admindjango'@'localhost' IDENTIFIED BY 'employee@123!';
GRANT ALL ON *.* TO 'admindjango'@'localhost';
FLUSH PRIVILEGES;
exit
```

# Run server
```bash
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py runserver
```
