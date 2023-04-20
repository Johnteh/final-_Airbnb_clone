# HolbertonBnB - Models Class System :cl:

HolbertonBnB supports the following classes:

* [BaseModel](../models/base_model.py)
* [User](../models/user.py)
* [State](../models/state.py)
* [City](../models/city.py)
* [Amenity](../models/amenity.py)
* [Place](../models/place.py)
* [Review](../models/review.py)

<p align="center">
  <img src="https://github.com/Johnteh/final_Airbnb_clone/blob/master/assets/hbnb-models.png"
       alt="HolbertonBnB logo"
       width="750"
  >
</p>

[Source code.](../models)

## Storage :open_file_folder:

I have implemented an abstracted engine as [DBStorage](../models/engine/db_storage.py).
However, the above classes are implemented by the following two storage engines
depending on the call - [FileStorage](../models/engine/file_storage.py) or
[DBStorage](../models/engine/db_storage.py).


### FileStorage

The default mode.

In `FileStorage` mode, every time the backend is initialized, HolbertonBnB
instantiates an instance of `FileStorage` called `storage`. The `storage`
object is loaded/re-loaded from any class instances stored in the JSON file
`file.json`. As class instances are created, updated, or deleted, the
`storage` object is used to register corresponding changes in the `file.json`.

### DBStorage

Run by setting the environmental variables `HBNB_TYPE_STORAGE=db`.

In `DBStorage` mode, every time the backend is initialized, HolbertonBnB
instantiates an instance of `DBStorage` called `storage`. The `storage` object
is loaded/re-loaded from the MySQL database specified in the environmental variable
`HBNB_MYSQL_DB`, using the user `HBNB_MYSQL_USER`, password `HBNB_MYSQL_PWD`, and
host `HBNB_MYSQL_HOST`. As class instances are created, updated, or deleted, the
`storage` object is used to register changes in the corresponding MySQL database.
Connection and querying is achieved using SQLAlchemy.

Note that the databases specified for `DBStorage` to connect to must already be
defined on the MySQL server. This repository includes scripts
[setup_mysql_dev.sql](../mysql/setup_mysql_dev.sql) and [setup_mysql_test.sql](../mysql/setup_mysql_test.sql)
to set up `hbnb_dev_db` and `hbnb_test_db` databases in a MySQL server,
respectively.

## Author :black_nib:

* __John Miiri__ - <[@miirijohn08@gmail.com](https://github.com/Johnteh)>
