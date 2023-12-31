# Clone project
```bash
git init
git clone https://github.com/truonganhvu205/little-lemon-booking-system-django.git
cd little-lemon-booking-system-django
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

## Install Django & frameworks
```bash
# Django
pipenv install django

# Frameworks
pipenv install mysqlclient
```

## Connect to MySQL
```bash
mysql -u root -p
create database reservations;

create user 'admindjango'@'localhost' identified by 'employee@123!';
grant all on *.* to 'admindjango'@'localhost';
flush privileges;

exit
```

# Run server
```bash
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py runserver
```

## Account required
```bash
Django
  admindjango
  employee@123!

MySQL
  admindjango
  employee@123!
```

## Deactivate virtual environment
```bash
exit
```

# Preview project
<table align='center'>
  <tr align='center'>
    <td>Before Booking</td>
    <td>After Booking</td>
    <td>All Reservations</td>
  </tr>
  <tr align='center'>
    <td>
      <img src='https://github.com/truonganhvu205/little-lemon-booking-system-django/blob/main/little-lemon-booking-system-django/little-lemon-booking-system-django-pic-1.png' />
    </td>
    <td>
      <img src='https://github.com/truonganhvu205/little-lemon-booking-system-django/blob/main/little-lemon-booking-system-django/little-lemon-booking-system-django-pic-2.png' />
    </td>
    <td>
      <img src='https://github.com/truonganhvu205/little-lemon-booking-system-django/blob/main/little-lemon-booking-system-django/little-lemon-booking-system-django-pic-3.png' />
    </td>
  </tr>
</table>
