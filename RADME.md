# Django

## 0. setting

- `.gitignore`
- 가상환경 설정
- `README.md`



## 1. Djanggo 프로젝트
1. django 설치
```shell
pip install django
```


2. 프로젝트 생성
```shell
 django-admin startproject <first_pjt> <path>
 ```

 3. 서버실행(종료 : `ctrl + c`)
```shell
python manage.py runserver
```

4. 앱 생성
```shell
django-admin startapp <app-name> #경로 설정 안 하면 현재 폴더에 생성됨
```

3. 앱 등록(`settings.py`)
```python
INSTALLED_APPS = [
    ''',
    <app name>,
] 
```

