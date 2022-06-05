## Instagram Clone

Instagram clone using python django with a lot of Instagram features.

## Features

- User authentication(Sign up and sign in).
- Posting images.
- Follow others and see thier photos.
- Like and comment on a post.

### Installation

- Make sure Python is installed.
- Clone https://github.com/VaniliKate/insta-clone.git and cd into insta-clone.
- Install requirements using following command.

```
pip install -r requirements.txt
```

### Usage

- Create a virtual environment.

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

- Make migrations.

```
python manage.py migrate
```

- Commit the migrations.

```
python manage.py makemigrations
```

- Create a super user.

```
python manage.py createsuperuser
```

- Run the app.

```
python manage.py runserver
```

- This opens the app at `localhost:8000` or `http://127.0.0.1:8000/`

## Authors

- **Kate Vanili(2022)**

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

Live Application `shorturl.at/szPW8`
Incase of browser warning just proceed and click visit unsafe.
