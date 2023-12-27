# Clone project
```bash
git init
git clone https://github.com/truonganhvu205/little-lemon-booking-system.git
cd little-lemon-booking-system
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

<table align='center'>
  <tr align='center'>
    <td>Before Booking</td>
    <td>After Booking</td>
    <td>All Reservations</td>
  </tr>
  <tr align='center'>
    <td>
      <img src='https://github.com/truonganhvu205/little-lemon-booking-system/blob/main/little-lemon-booking-system-django-truong-anh-vu-12-15-2023.png/little-lemon-booking-system-django-truong-anh-vu-12-15-2023-pic-1.png' />
    </td>
    <td>
      <img src='https://github.com/truonganhvu205/little-lemon-booking-system/blob/main/little-lemon-booking-system-django-truong-anh-vu-12-15-2023.png/little-lemon-booking-system-django-truong-anh-vu-12-15-2023-pic-2.png' />
    </td>
    <td>
      <img src='https://github.com/truonganhvu205/little-lemon-booking-system/blob/main/little-lemon-booking-system-django-truong-anh-vu-12-15-2023.png/little-lemon-booking-system-django-truong-anh-vu-12-15-2023-pic-3.png' />
    </td>
  </tr>
</table>
