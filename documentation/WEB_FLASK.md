# HolbertonBnB - Web Flask :globe_with_meridians:

 Built in Python Flask and using Jinja2. Html files are only rendered using jinja2 an engine of flask 

[Source code.](../web_flask)

## Dependencies :couple:

Application:

| Tool/Library | Version |
| ------------ | ------- |
| Python       | ^3.6.4  |
| Flask        | ^1.0.3  |

## Usage :eyes:

Assuming the above dependencies have been installed, the app server can be started using the following command:

```
python3 -m web_flask.hbnb
```
although, note that this only display a web static page.Here we have not yet connected with our api.

<p align="center">
  <img src="https://github.com/Johnteh/final_Airbnb_clone/blob/master/assets/web%20flask.png"
       alt="HolbertonBnB logo"
       width="750"
  >
</p>


Of course, the server is truly only functional in conjunction with the [HolbertonBnB API](./API.md).

## Files :file_folder:

* [templates](../web_flask/templates): The HTML5 content for HolbertonBnB.
  * [templates/index.html](../web_flask/templates/index.html): The root page of HolbertonBnB.
* [static](../web_flask/static): Static content included in [templates/index.html](../web_flask/templates/index.html).
  * [static/images](../web_flask/templates/static/images): Image files.
  * [static/scripts](../web_flask/templates/static/scripts): JavaScript scripts (uses jQuery).
  * [static/images](../web_flask/templates/static/styles): CSS3 stylesheets.

## Routes :light_rail:

* `/hbnb`: Serves [templates/index.html](../web_flask/templates/index.html), the root page of HolbertonBnB.

## Author :black_nib:

* __Brennan D Baraban__ - <[bdbaraban](https://github.com/bdbaraban)>
