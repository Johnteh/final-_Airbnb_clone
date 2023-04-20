<h1 align="center">Holbertonbnb</h1>
<p align="center">An Airbnb clone.</p>

<p align="center">
  <img src="https://github.com/Johnteh/final_Airbnb_clone/blob/master/assets/hbnb-logo.png"
       alt="Holbertonbnb logo"
       width="500"
  >
</p>

## Description :house:

Holbertonbnb is a complete full-stack web application, integrating a MySQL database and Flask RESTful API with a dynamic
HTML5/CSS3/jQuery front-end.

<p align="center">
  <img src="https://github.com/Johnteh/final_Airbnb_clone/blob/master/assets/hbnb-stack.png"
       alt="Holbertonbnb logo"
       width="750"
  >
</p>



This project was a complete web application by A.L.X Africa. The project involved cloning some code bases given to us then pair programm with a peer to come up with required outcome. We created four versions of the project.This repo being the fifth hoping not the last version :sweat_smile: believe in continuous improvement :smiley:

You can check the last version of the project from the repo below

1. [AirBnB_clone_v4](https://github.com/Johnteh/AirBnB_clone_v4)

what this is the only version?...we want to see the start.where does all this begin :sweat_smile: :sweat_smile:
if you are interested on the previous projects you can as well check out the below versions and maybe have a look on the journey
2. [AirBnB_clone_v2](https://github.com/Johnteh/AirBnB_clone_v2)
3. [AirBnB_clone](https://github.com/Johnteh/AirBnB_clone)


This versioning process was a great experience in pair programming and working on unfamiliar, developed codebases. Yet, it was not so great from a portfolio perspective and the want of a central, organized repository where I could show off all the work I coded and learned over the course of this clone.

This repository is just the above - an organized, cleaned up version of Holbertonbnb. Call it a minified build, if you will.

I started this repository as a duplicate of [AirBnB_clone_v4](https://github.com/Johnteh/AirBnB_clone_v4) Since then, I have:

- Cut out all irrelevant code, organizing just that needed to deploy the application.
- Pieced together each of the front-end, back-end and API with strictly _my_ code, copying in the personal implementations of each that I worked on across all four versions.


### What this repository does include:

- Models class system built in Python.

  - [Source code](./models)
  - [Documentation](./documentation/MODELS.md)

- Python console to manage back-end models

  - [Source code](./console.py)
  - [Documentation](./documentation/CONSOLE.md)

- Flask web application server rendering HTML templates with Jinja2

  - [Source code](./web_flask)
  - [Documentation](./documentation/WEB_FLASK.md)

- RESTful Flask API

  - [Source code](./api)
  - [Documentation](./documentation/API.md)
  - Swagger documentation - [bdbnb.site/apidocs](https://bdbnb.site/apidocs)

- Automatic deployment scripts.
  - [fabfile.py](./fabfile.py)
  - [setup_server.pp](./setup_server.pp)
  - [Documentation](./documentation/DEPLOYMENT.md)

### What this repository does not include:

- Test suite

Unfortunately, the test suite did not hold up well over the course of four different codebases, and was a bit much to justifiably refactor for this minified repo. Which is too bad, because this project involved a significant amount of time spent developing an unittest test suite testing the entire back-end. If you're interested in looking at tests I was involved in writing, my most signficant test work occurred in [AirBnB_clone](https://github.com/bdbaraban/AirBnB_clone).

## Dependencies :couple:

Application:

| Tool/Library | Version |
| ------------ | ------- |
| Python       | ^3.6.4  |
| MySQL        | ^5.6.0  |
| Flask        | ^1.0.3  |
| flasgger     | ^0.9.2  |
| Flask-Cors   | ^3.0.8  |
| mysqlclient  | ^1.3.10 |
| SQLAlchemy   | ^1.3.5  |

View the complete list of app dependencies in the [requirements.txt](./requirements.txt).

Deployment:

| Tool/Library | Version |
| ------------ | ------- |
| Python       | ^3.7.3  |
| gunicorn     | ^19.9.0 |
| Fabric       | ^2.4.0  |
| Puppet       | ^5.4.0  |

## Documentation :book:

In case you missed it - I've documented this entire repository! [Please do check it out!](./documentation)

## Author :black_nib:

- **John miiri** - <[@miirijohn08@gmail.com](https://github.com/Johnteh)>

## License :lock:

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
