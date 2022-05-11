## Initial Setup
```
$ mkdir http-load-balancer
$ cd http-load-balancer
$ python3.9 -m venv env
$ source env/bin/activate

(env)$ python -V
Python 3.9.0

(env)$ pip install flask pytest
```

## Run this to activate the Python Env
```
source env/bin/activate
```

## Run this to run all tests. Those are files that start with 'test_###'
```
python -m pytest
```

## The command prompt should look like
```
(env) ➜  http-load-balancer python -m pytest 
```