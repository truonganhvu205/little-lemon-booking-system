# Clone project
```bash
mkdir little-lemon-booking-system

cd little-lemon-booking-system

git init

git clone https://github.com/truonganhvu205/little-lemon-booking-system.git
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
