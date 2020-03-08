# traffic
 
ここは説明です
===========
 
:Python: 3.7.3
:Django: 2.2.2
 
 
Quick start
===========
1. pipでインストールする。::
 
    pip install -U https://github.com/kenta-watanabe/traffic/archive/master.tar.gz
 
 
2. あなたのDjangoプロジェクトのINSTALLED_APPSに、"station" を足す。::
 
    INSTALLED_APPS = [
        ...
        'station',
    ]
 
3. urls.pyに以下のようにしてincludeしてください。::
 
    url(r'^', include('station.urls')),
 
4. `python manage.py migrate`
 
5. `python manage.py runserver`
 
6. http://127.0.0.1:8000 へアクセス!
