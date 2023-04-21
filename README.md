# LearnZ 
E-learning platform to promote online learning. It acts as a connector between students and teachers. Provides well organized study material uploaded by educators and auto recommendation to reference material on YouTube. It is a web application that provides the services of a Learning Management System. Educators can log in and upload the relevant materials on the respective course page. Students also can log in and access the materials uploaded by their educators as well as find relevant most viewed YouTube videos based on the material uploaded by the educator.

## Features

- <b>All-In-One Platform:</b> 


An all-in-one E-learning platform for students and teachers where students can access materials posted by educators.
- <b>User friendly and intuitive learner interface:</b> 


A well structured educational environment with a pleasant user experience. 
- <b>Automatic reference materials suggestions:</b> 


Students will be able to obtain relevant youtube video links for the selected course.
- <b>Variety of learning resources:</b> 


Students can access resources like quizzes, syllabus, online lectures etc.
- <b>E-learning:</b>


Contributing to the advancement of e-learning.

## Tech Stack

**Frontend** : HTML5, CSS3, JavaScript, JQuery.

**Backend** : Django, SQLite3.

**Deployement** : Git, Docker, Jenkins, AWS.

**Testing** : Selenium


![My Skills](https://skills.thijs.gg/icons?i=html,css,js,jquery,django,python,sqlite,git,docker,jenkins,aws,selenium&perline=3)

## Getting Started 

Clone the project

```
git clone https://github.com/Astraxx04/LearnZ
```

Change directory to the LearnZ folder

```
cd LearnZ
```

Install required dependencies 

```
pip install -r requirements.txt 
```
- Make sure that dependencies are installed successfully.

Migrate changes to sqlite3 db before running

```
python manage.py migrate
```

Run the django server locally

```
python manage.py runserver
```

Visit the webiste on local host using any web browser

```
http://127.0.0.1:8000/
```

##### Local Administration

You need a superuser to access http://127.0.0.1:8000/admin which has the interface to administrative tasks.

To create a new super user run

```
python manage.py createsuperuser
```

Then visit http://127.0.0.1:8000/admin and login by the created credentials to access the administrator panel.

### Running using docker
Docker can also be used for execution. After Cloning the project Run the docker compose file.
```
docker-compose up -d --build 
```
Next access the website at http://127.0.0.1:5001

After using, you can kill the docker-container using:
```
docker kill devops-my-container-1 
```
If you get any error such as 
```
port has already been allocated or address already in use
```
Then change the port number 5001 in both dockerfile and docker-compose file to any empty port number on your system. 
