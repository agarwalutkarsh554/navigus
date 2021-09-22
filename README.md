Create Virtual Env and Install the requirements:

```bash
cd django-schools
python -m venv env
source ./env/bin/activate
pip install -r requirements.txt
```

Create the database and run the development server:

```bash
cd django_school
python manage.py migrate
python manage.py loaddata datas.json
python manage.py runserver
```

The project will be available at http://127.0.0.1:8000, Login using::

**Teacher**

+ username: `teacher`
+ password: `teacher`

**Student**

+ username: `student`
+ password: `student`



![image](https://user-images.githubusercontent.com/37051428/134399769-bfb85bf0-3d7f-4014-bd7b-91856dad8d5c.png)
![image](https://user-images.githubusercontent.com/37051428/134399890-f05e325c-e586-4fb2-9340-e61efc317f73.png)
![image](https://user-images.githubusercontent.com/37051428/134399943-9029be8a-d311-4e34-b76e-d570eb24995b.png)



## License

The source code is released under the [MIT License](https://github.com/sibtc/django-multiple-user-types-example/blob/master/LICENSE).
