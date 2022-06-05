## Instagram Clone
Instagram clone using python django with a lot of Instagram features.

## Features
- User authentication(Sign up and sign in).
- Posting images.
- Follow others and see thier photos.
- Like and comment on a post.

### Installation
- Make sure Python is installed.
- Clone the repository and change your directory to Insta_clone.
- Install requirements using following command.
```
pip install -r requirements.txt
```
### Usage
- Create a ``.env`` file.
```
python3 -m venv venv
. venv/bin/activate
```

- Declare following environment variables in the .env file.
```
> SECRET_KEY = 'secret key'
> DEBUG = True
> EMAIL_USERNAME = 'your email address'
> EMAIL_PASSWORD = 'your password' 
```
- Now make the migrations.
```
python manage.py migrate
```
- Commit the migrations.
```
python manage.py makemigrations
```
- Create a super user.
```
python manage.py createsuper
```
- Run the app.
```
python manage.py runserver
```
- Open the app at `localhost:8000` or `http://127.0.0.1:8000/`

## Contact Me 
### 
