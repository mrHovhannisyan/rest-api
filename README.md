# REST API

## DEVELOPMENT SERVER ## 
**_For running development server you have two options_**

**_1st option._ (with VM and Vagrant)**
1) Clone project code from this repository.
2) Open terminal and change your working directory to the project directory.
3) Run `vagrant up`.
4) Run `vagrant ssh` for connecting to local development server(LDS).
5) For creating virtual environment run `python -m venv ~/env` on _LDS_.
6) For virtual environment activation run `source ~/env/bin/activate`. You must see 
`(env) vagrant@ubuntu-bionic:/vagrant$`
7) Now, for starting _LDS_ `python manage.py runserver 0.0.0.0:8000` and hit in your browser `localhost:8000`
8) Enjoy!.



**_2nd option._ (on your local machine)**
1) Repeat steps _1_ and _2_ from _1st option_
2) Run `pipenv install`
3) Run `pipenv shell`
4) Run `python manage.py runserver` and hit in your browser `localhost:8000`
5) Enjoy!
