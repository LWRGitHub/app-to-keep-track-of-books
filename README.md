# App to Keep Track of Books
The app is a great place to keep track of all of your books!

## Tech Used
- Python
- SQL
- SQLAlchemy
- HTML/CSS
- Jinja2
- Flask
- Flask-WTF
- python-dotenv
- unittest

## Setup/Install

1. `pip3 install -r requirements.txt`
2. `makdir .env`
- Add:
  ```
  SQLALCHEMY_DATABASE_URI=sqlite:///database.db
  SECRET_KEY=some_secret
  ```
3. `python3 app.py`

***Tests With***

```
python3 -m unittest discover
```

(Make sure you have unittest installed.)

***To run all tests from a single file***

```
python3 -m unittest books_app.main.tests
```

***To run one specific test***

```
python3 -m unittest books_app.main.tests.MainTests.test_homepage_logged_in
```

## Img

***Home***

![Image of main page](https://raw.githubusercontent.com/LWRGitHub/app-to-keep-track-of-books/master/assets/home.png)

***Sign Up***

![Image of sign up page](https://raw.githubusercontent.com/LWRGitHub/app-to-keep-track-of-books/master/assets/sign-up.png)

***Log In***

![Image of Log In page](https://raw.githubusercontent.com/LWRGitHub/app-to-keep-track-of-books/master/assets/log-in.png)

***Profile***

![Image of profile page](https://raw.githubusercontent.com/LWRGitHub/app-to-keep-track-of-books/master/assets/profile.png)

***Create Book***

![Image of Create Book page](https://raw.githubusercontent.com/LWRGitHub/app-to-keep-track-of-books/master/assets/create-book.png)

***Create Author***

![Image of Create Author page](https://raw.githubusercontent.com/LWRGitHub/app-to-keep-track-of-books/master/assets/create-author.png)

***Create Genre***

![Image of Create Genre page](https://raw.githubusercontent.com/LWRGitHub/app-to-keep-track-of-books/master/assets/create-genre.png)