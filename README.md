# IBM Back-end Capstone Application

This is the Django website for the band. Connects to pictures and song microservices.
[Photos Microservice](https://github.com/jakeleesh/Back-End-Development-Pictures)
[Songs Microservice](https://github.com/jakeleesh/Back-End-Development-Songs)

## Description

- Developed using Python and Django.
- Create models.
- Migrate the model to create tables in the SQLite database.
- Implement controllers to send data to pre-defined templates.
- Create the songs page that lists all the titles of the songs.
- Craete the photos page that displays pictures from past events.
- Allow users to log in and see concerts.
- Use Docker to containerize Django application.
- Deploy on IBM Kubernetes Services (IKS).

## Installation

Use the script to install virtual environment.
```bash
cd /Back-end-Development-Capstone
bash ./bin/setup.sh
```

## Usage
```bash
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
curl -s -o /dev/null -w "%{http_code}" http://localhost:8000

python manage.py createsuperuser
```
## Visuals
![Capstone Architecture](https://github.com/user-attachments/assets/6f65f541-fca8-48be-9bc4-46c6a5b56a23)
