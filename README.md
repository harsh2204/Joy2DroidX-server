# Joy2DroidX

This fork adds and allows more flexible usage of j2dx server, specifically with [socketjoy](https://github.com/harsh2204/socketjoy).

Instructions to run:

* Clone the repo
* Edit `j2dx/__init__.py` file and change #L99 `cors_allowed_origins='http://192.168.2.92:8000'` value to your socket joy address.
* Run `pip install -I <repo-dir>`. I recommend doing this in a virtual env.
* Follow the instructions on usage from the original repo or socketjoy.