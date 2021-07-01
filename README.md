## Flask App Heroku

It is a flask app which is ready to host on heroku

## Usage
* Make sure your virtual environment is activated.

* Add your dependencies to requirements.txt by typing in the terminal,
```shell
pip freeze > requirements.txt
```
* [Make a Heroku account](https://signup.heroku.com/)

* [Download Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli)

* In your terminal, type in
 ```shell
git init
git add .
git commit -m "first commit"

heroku login
heroku create app_name
git push heroku main

* If you make edits, then just type in the terminal,
```shell
git add .
git commit -m "edit"
git push heroku main
```
