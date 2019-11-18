# Source Django
[LongBlog](http://www.longblog.info/)

# Cài đặt
Đầu tiên, tải repository về máy tính:
```bash
$ git clone https://github.com/Longdh57/source-django.git
```  
Cài đặt requirements:
```bash
$ cd source_django
$ virtualenv -p python3 .venv
$ source .venv/bin/activate
$ pip install -r requirements.txt
```
Chạy migrate:
```bash
$ cp .env.sample .env
$ python manage.py migrate 
``` 
Runserver:
```bash
$ python manage.py runserver 
``` 
Check tại [http://127.0.0.1:8000/](http://127.0.0.1:8000/)